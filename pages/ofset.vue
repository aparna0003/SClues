<template>
  <v-container class="black">
    
    <v-row
      class="mb-12"
      no-gutters
    >
      <v-col md="1">
       <breadcrumb/>
        
      </v-col>
      
    </v-row>
    <v-row
      class="mb-6"
      
    >
       <v-col
         md="1"
         offset-md="2"
         <v-img
           height="550"
           src="https://www.jasemx.com/wp-content/uploads/2019/10/product1.jpg"
         ></v-img>
          
      </v-col>
    
      <v-col
         md="1"
         offset-md="5"
         <card/>          
      </v-col>
    </v-row>
    <v-row>
      <tab/>
    </v-row>
    <v-row>
      <scroll/>
    </v-row>
    <v-row
      class="mb-6" dark
      >
      <v-col>
           enter your queries 
         <input/>
      </v-col>
    </v-row>

    
  
  </v-container>
  </template>