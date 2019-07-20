<template>
    <v-stepper v-model="e1">
      <v-stepper-header>
        <v-stepper-step :complete="e1 > 1" step="1">Name of step 1</v-stepper-step>
  
        <v-divider></v-divider>
  
        <v-stepper-step :complete="e1 > 2" step="2">Name of step 2</v-stepper-step>
  
        <v-divider></v-divider>
  
        <v-stepper-step step="3">Name of step 3</v-stepper-step>
      </v-stepper-header>
  
      <v-stepper-items>
        <v-stepper-content step="1">
            stepper content 1
        </v-stepper-content>
  
        <v-stepper-content step="2">
            stepper content 2
        </v-stepper-content>
  
        <v-stepper-content step="3">
            stepper content 3
        </v-stepper-content>
      </v-stepper-items>
    </v-stepper>
</template>
