<template>
  <v-container class="white">
    <v-row class="col-lg-12 col-sm-12 col-xs-12">
      <!--breadcrumb is added-->

      <v-col classs="col-lg-12">
        <breadcrumb />
      </v-col>
    </v-row>
    <v-row gutters
     >
     
      <v-col
       
      class="pa-md-2 mx-lg-2 "
      ma="0 px"><!--to add thubnail pictures-->
      <v-col
      class="pa-md-2 mx-lg-2 col-md-1 col-xs-pa-1 col-lg-1">
       
       <v-row
        md="2" 
        mx="0"
        pa="2"
        > 
        <v-img
           contain
         
           max-height="151"
           max-width="90"
           src="https://images.unsplash.com/photo-1570891836654-d4961a7b6929?ixlib=rb-1.2.1&w=1000&q=80"
          ></v-img>
        </v-row>
        <br>
         <v-row> 
          <v-img
           contain
           lazy-src="https://cdn.keepo.me/images/post/lists/2020/05/29/main-list-image-4001f1ab-d528-4ac2-bc55-b39cc6139f9c-4.jpg"
           max-height="151"
           max-width="90"
           src="https://cdn.keepo.me/images/post/lists/2020/05/29/main-list-image-4001f1ab-d528-4ac2-bc55-b39cc6139f9c-4.jpg"
          ></v-img>
           
        </v-row>
        <br>
        
          <v-row> 
        <v-img
           contain
           
           lazy-src="https://cdn.keepo.me/images/post/lists/2020/05/29/main-list-image-4001f1ab-d528-4ac2-bc55-b39cc6139f9c-4.jpg"
           max-height="151"
           max-width="90"
           src="https://images.unsplash.com/photo-1593273757264-9ff6e8ba5ee7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=675&q=80"
          ></v-img>
        </v-row>
        <br>
          <v-row
         > 
        <v-img
           contain
           lazy-src="https://images.unsplash.com/photo-1570273282451-b22438331ba3?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjEyMDd9"
           max-height="151"
           max-width="90"
           src="https://images.unsplash.com/photo-1570273282451-b22438331ba3?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjEyMDd9"
          ></v-img>
        </v-row>
        </v-col>
        </v-col>


      <v-col
        class=" col-xs-5 col-sm-5 col-md-4 col-lg-5 ">
        <!--to add product main pictures-->
       <v-list-item color="grey darken-3">
          <v-img
             class="white--text align-end"
              src="https://cdn.keepo.me/images/post/lists/2020/05/29/main-list-image-4001f1ab-d528-4ac2-bc55-b39cc6139f9c-4.jpg"
             :width="$vuetify.breakpoint.xs 
                ? '230px' 
                : ($vuetify.breakpoint.sm
                    ? '400px' 
                    : ($vuetify.breakpoint.md
                        ? '600px'
                        : ($vuetify.breakpoint.lg
                            ? '800px' 
                            : '1200px'
                        )
                    )
                )"
         ></v-img>
        </v-list-item>
      </v-col>
      <!--to add the product detail card-->
      <v-col order="10"
      class=" col-xs-5 col-sm-5 col-md-6 col-lg-5 light">
        <v-card
         color="#FFFFFF"
          class="pa-0"
          elevation="0 px"
          light
          tile
        >
        <div>
           <p class="display-1 text--black
              light">
        iPhone X (Black) (64 GB)
      </p>
      </div>
       <div>Product Code: 7866454532</div>
       
       <!--main product information-->
      <div >
          6.1-inch (15.5 cm) Liquid Retina HD LCD display
          Water and dust resistant (2 meters for up to 30 minutes, IP68) <br><br>
          Dual-camera system with 12MP Ultra Wide and Wide cameras; Night mode, Portrait mode, and 4K video up to 60fps
          well meaning and kindly.<br>

         <v-row>
         
           <v-col
             md="6"
             class="ml-md-sm-auto"
             >
             <v-card
               color="deep-orange lighten-5"
               
              
               class centered="pa-2" 
               elivation="0 px"
               flat
               class="d-flex align-center justify-center pa-4 mx-auto"
               ><div>
               <p class="font-weight-bold #707070--text">
                   SC50
               </p>
              </div>
              </v-card>
           </v-col>
           <v-col
             md="6"
             class="ml-md-auto"             
             >
              Offer can be availed till 25th June 
              The discount can be applied with GST
            </v-col>
        
          </v-row>
          <v-row>
           <v-col>
          <p class="display-1 text--black">
           Rs.68,000/-
         </p>
         </v-col>
           <v-col>
           <v-row>
            <div
            no gutter>
            <p class="font-weight-light">Rated by 15,365 users</p>
            </div>
          </v-row>
        <v-row>
        <v-btn icon light>
        <v-icon>mdi-star</v-icon>
        </v-btn>
         <v-btn icon light>
        <v-icon>mdi-star</v-icon>
        </v-btn>
         <v-btn icon light>
        <v-icon>mdi-star</v-icon>
        </v-btn>
         <v-btn icon light>
        <v-icon>mdi-star</v-icon>
        </v-btn>
        </v-row>
        </v-col>
         </v-row>
        </div>
     </v-card-text>
     <!--adding buttons-->
     <v-card-actions>
     <v-row>
           <v-col
             md="5"
             class="ml-md-auto"
             >
             <!--adding buttons-->
             <v-btn
              color="cyan lighten-1"
              dark
              large
            >
              Add to Cart
            </v-btn>
           </v-col>
           <v-col
             md="6"
             class="ml-md-auto"
             >
              <v-btn
              color="cyan lighten-1"
              dark
              large
            >
              Buy Now
            </v-btn>
            </v-col>
        
          </v-row>
      
      </v-card-actions
      >
      <v-row>
      
        <v-col
          md="3"
           class="ml-md-auto"
           >
           <v-card
             class= "pa-"
             outlined
             tile
             >
             <p> 682306 </p>
            </v-card>
         </v-col>
         <v-col
           md="6"
           class="ml-md-auto"
           >
            <p> Delivery Date: 12/11/2020 <p/>
          </v-col>
        
        </v-row>
        <p> COD, Credit, Debit, Net Banking, Wallets, EMI </p>
        <v-row>
        <v-col
          md="5"
           class="ml-md-auto"
           >
           
             <p> Return Available  </p>
              </v-col>
         <v-col
           md="6"
           class="ml-md-auto"
           >
            <p> Warranty: 1 year <p/>
          </v-col>
        
        </v-row>
        </v-card>
      </v-col>
      
    </v-row>


<!--adding other components of the page-->



    <v-row>
      <tab /> <!--to add the product description tabs-->
    </v-row>
    <br>
    <v-row>
       <doubt/> <!--to add the chat with retailer and the queries-->
    </v-row>
     <v-row>  <!--to add the the input queries-->
        <v-row
          no gutter           
          cols="12"
          sm="6"
          md="3"
        >
        <v-col>
          <v-card    
           color="#E2EFEF">
          <v-text-field
          
            class="grey--text"
            label="How was our service"
            
          ></v-text-field>
          </v-card>
        </v-col>
       
      </v-row>
    </v-row>
 
  </v-container>
</template>
