<template>
  <v-container class="black">
    
    <v-row
      class="mb-12"
      
    >  <!--breadcrumb is added-->
      <v-col md="1">
       <breadcrumb/>
        
      </v-col>
      
    </v-row>
    <v-row
      class="mb-6"
      
    >    <v-col  
         md="1"
         class="ml-md-auto"
         offset-md="2"
         ><v-img
         height="200"
         width="300"
          
           src="https://www.jasemx.com/wp-content/uploads/2019/10/product1.jpg"
        > </v-img>
          
      </v-col>
        <!--to insert the picture
       <v-col  
         md="1"
         class="ml-md-auto"
         offset-md="2"
         <v-img
           height="400"
         width="300"
           src="https://www.jasemx.com/wp-content/uploads/2019/10/product1.jpg"
         ></v-img> -------------------------------->
          
      </v-col>
    <!--to insert the card with details-->
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
    <v-col
     class= "md=6"
     >
      <FAQ/>
    </v-col>
    </v-row>
    <v-row
      class="mb-6" dark
      >  <!---the area to enter comments are added-->
      <v-col>
          Click to enter your queries 
         <input/>
      </v-col>
    </v-row>

    
  
  </v-container>
  </template>