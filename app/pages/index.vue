<template>
    <v-app>
        <v-main>
            <v-container>
                <v-row>
                    <v-col
                        cols="12"
                    >
                        <v-text-field
                         label="Student Number"
                         variant="outlined"
                        ></v-text-field>
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="Last Name"
                            variant="outlined"
                        ></v-text-field>
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="First Name"
                            variant="outlined"
                        ></v-text-field>
                    </v-col>

                    <v-col
                        col="12"
                        md="4"
                    >
                        <v-text-field
                            label="Middle Name"
                            variant="outlined"
                        ></v-text-field>
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-combobox
                            label="Course"
                            :items="['BSCS', 'DCT']"
                            variant="outlined"
                        ></v-combobox>
                    </v-col>


                </v-row>  
            </v-container>
        </v-main>
    </v-app>
</template>