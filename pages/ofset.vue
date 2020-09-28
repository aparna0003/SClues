<template>
  <v-container class=" col-xs-6">
     <v-row
       class="col-lg-6  col-sm-12 col-xs-12"
      
      >  <!--breadcrumb is added-->
    
     <v-col 
      classs= "col-lg-12">
       <breadcrumb/>
        
      </v-col>
      
     </v-row>
 
     <v-row 
     <v-row >
      <v-col
      fluid alt="Responsive image"
        class= "  col-sm-1  col-md-2 col-lg-2   "
        cols="12"
        md="1"
      
        >
         <!--images for the thumbnails-->
        <v-row>  
           <v-col       
             col="12" >
             <v-card
         
               ><v-img
        
                   src="https://images.unsplash.com/photo-1570891836654-d4961a7b6929?ixlib=rb-1.2.1&w=1000&q=80" fluid alt="Responsive image"
                ></v-img>
         
             </v-card>
           </v-col>
        </v-row>
       
        <v-row>  
          <v-col>        
             <v-card
      
              ><v-img
                   src="https://cdn.keepo.me/images/post/lists/2020/05/29/main-list-image-4001f1ab-d528-4ac2-bc55-b39cc6139f9c-4.jpg" fluid alt="Responsive image"
                  ></v-img>
              </v-card>
           </v-col>
        </v-row>

        <v-row>  
           <v-col>        
               <v-card
       
                   ><v-img
                        src="https://images.unsplash.com/photo-1570273282451-b22438331ba3?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjEyMDd9" fluid alt="Responsive image"
                   ></v-img>
         
                </v-card>
           </v-col>
        </v-row>
          
        <!--the diaplay image-->
      </v-col>
      <v-col
          col="12"
          sm="3"
          class="  col-sm-5 col-md-5 col-lg-5 col-xl-6 ">        
          <v-card
              ><v-img
                 src="https://cdn.keepo.me/images/post/lists/2020/05/29/main-list-image-4001f1ab-d528-4ac2-bc55-b39cc6139f9c-4.jpg"fluid alt="Responsive image"
              ></v-img>
         
            </v-card>
        </v-col>
       <v-col
          col="12">        
          <v-card
              class="  sm-12 sx-12 md-6 lg-12 col-12 "
              ><card/>
           </v-card>
        </v-col>
     </v-row>

     <v-row>
         <tab/>
     </v-row>
     <v-row>
     <v-col
     md="12">
     <h2 class="brandcol">Chat with Retailers </h2>
          <scroll/>
     </v-col>
     </v-row>
     <v-row
         class="mb-6" 
         >  <!---the area to enter comments are added-->
         <v-col light
          md="12"
          sm="12">
             Click to enter your queries 
             <input/> <!--input for the queries-->
         </v-col>
     </v-row>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      //
    }),
  }
  
</script>