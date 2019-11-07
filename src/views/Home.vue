<template>
    <v-container>
        <v-layout>
            <h1>Home page</h1>
        </v-layout>
        <v-layout align-center justify-center>
            <v-flex xs12 sm8 md4>
                <v-card class="elevation-12">
                    <v-toolbar dark color="purple">
                        <v-toolbar-title>Login Form</v-toolbar-title>
                    </v-toolbar>
                    <v-card-text>
                        <v-form>
                            <v-icon>mdi-account</v-icon>
                            <v-text-field

                                    name="login"
                                    label="Login"
                                    id="login"
                                    type="text"
                            ></v-text-field>
                            <v-icon>mdi-key</v-icon>
                            <v-text-field

                                    name="password"
                                    label="Password"
                                    id="password"
                                    type="password"
                            ></v-text-field>
                        </v-form>
                    </v-card-text>
                    <v-card-actions>
                        <v-spacer></v-spacer>
                        <v-btn dark color="pink">Login</v-btn>
                    </v-card-actions>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</template>
