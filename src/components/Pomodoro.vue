<template> 
    <v-card color="white">
        <v-card-title class="text-center justify-center py-6">
            <h1 class="font-weight-bold text-h2 basil--text">
                POMODORO CLOCK
            </h1>
        </v-card-title>
        <v-tabs
        v-model="tab"
        background-color="transparent"
        color="basil"
        grow>
            <v-tab
                v-for="item in items"
                :key="item"
            >
                {{ item }}
            </v-tab>
        </v-tabs>
    </v-card>
</template>
