<template>
  <v-container class="black col-xs-6">
    
    <v-row
      class="col-lg-6  col-sm-12 col-xs-12"
      
    >  <!--breadcrumb is added-->
    
      <v-col 
      classs= "col-lg-12">
       <breadcrumb/>
        
      </v-col>
      
    </v-row>
    <v-row
      class="mb-6"
      
    >
        <!--to insert the picture-->
         <v-col   
         md="1"
         offset-md="1"
         

         




<template
class= "  col-sm-6 col-md-6 col-lg-6 col-xl-4 "
offset="0"
 justify="left">

  <v-row
   style= "margin-right:-100; margin-left:-100;">
   
   
    <v-col cols="12" sm="6" offset-sm="3">
      <v-card>
        <v-container fluid>
          <v-row>
            <v-col
              v-for="n in 3"
              :key="n"
              class="d-flex child-flex"
              cols="12"
            >
              <v-card flat tile class="d-flex">
                <v-img
                
                  :src="'https://picsum.photos/500/300?image'"
                  aspect-ratio="1"
                  class="grey lighten-2 "
                >
                  <template v-slot:placeholder>
                    <v-row
                      class="fill-height ma-0"
                      align="center"
                      justify="center"
                    >
                      <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                    </v-row>
                  </template>
                </v-img>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-col>
  </v-row>
</template>








      </v-col><!-- to place the rest of the code---->
       <v-col  
       no-gutter
         
         class=" col-12  col-sm-4 col-md-12 col-lg-12 "
         
         style= "height:210px; width:200; margin-right:20 ;"
         offset-md="2"
         
         <v-img
          height="440"
          width="220"
           src="https://www.jasemx.com/wp-content/uploads/2019/10/product1.jpg"
            justify="center"
         ></v-img>
          
      </v-col>
    <!--to insert the card with details-->
      <v-col   
         class=" col-md-2 col-lg-12 col-sm-12"
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
      class="mb-6" 
      >  <!---the area to enter comments are added-->
      <v-col>
          Click to enter your queries 
         <input/>
      </v-col>
    </v-row>

    
  
  </v-container>
  </template>