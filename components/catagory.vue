<template>
   <!--the tabs for main categories-->
  <v-tabs
   elevation="0 px"
   color="white"
   background-color="#55BCC9"
      center-active
    class= "centered menubar2">
    
  
    <v-tab> MADE IN INDIA  </v-tab>
    <v-tab>MEN</v-tab>
    <v-tab>WOMEN</v-tab>
    <v-tab>HOME FURNATURE</v-tab>
    <v-tab>ELECTRONICS</v-tab>
    <v-tab> APPLIANCES</v-tab>
    <v-tab>SPORT AND MORE</v-tab>
    <v-tab>DAILY ESSENTIALS</v-tab>
  </v-tabs>
 
</template>

<style>
 @media (max-width: 1024px) {
         .menubar2 {
           display:none;
         }
      }
</style>
