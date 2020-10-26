<template>
  <!--Your App Starts Here -->
  <v-app id="inspire" light>
    
    <!--Header -->
    <!--<v-app-bar color="red" dark fixed app>
      <v-toolbar-title>Application</v-toolbar-title>-->
       <!-- Component Example -->
       <v-row
         
          no-gutters
          col="12"
         
         >
          <v-col
           
           class=" col-xs-1 col-sm-2 col-md-2 col-lg-3 light"
          >
          <v-card
             
              class="cyan lighten-5 "
               pa="2" 
               tile
               max-height="500"
               >
              <VuetifyLogo/>  <!--persistant tool bar is added-->
          </v-card>
         </v-col>
        
         <v-col
           class="  col-xs-3 col-sm-10 col-md-9 col-lg-9 light"
           v-offset="2"
          ><toolbar/>  <!--persistant tool bar is added-->
         </v-col>
         </v-row>
      <catagory/>     <!--catagory bar for all pages is-->
    </v-app-bar>

    <!-- Body -->
    <v-content light>
      <nuxt /> 
    </v-content>
          
    <!-- Footer -->
    <v-footer color="grey" 
    light> <!--colour of the footer is changed-->
    <!--footer content is added-->
     <v-container>
      <v-row>

      <v-col>
      <h5>Shopper Central</h5>
     <p> Easy Returns & Replacement </p>
     <p> Our Policies</p>
     <p> CluesBucks</p>
     <p> Payment Options</p>
     <p> ShopClues Surety</p>
      <p> FAQs (Help) </p>
      <p> Service Centers </p>
      <p> User Agreement </p>
      <p> Refer & Earn </p>
      </v-col>
       
      <v-col>
      <h5>Merchant Central </h5>
      <p> Merchant Panel </p>
      <p> How To Sell </p>
      <p> Commission Structure </p>
      <p> Fullfillment Policy </p>
      <p> Policies & Rules </p>
      <p>User Agreement </p>
      <p>Testimonials </p>
      <p>Seller Summit</p>
      <p> Merchant Blog </p>
      <p> Developer Resources </p>
      </v-col>


      <v-col>
      <h5>About Us</h5>
       <p>History </p>
       <p> Band of Trust </p>
       <p> Brand Guidelines </p>
      <p> TV Commercials </p>
      <p> In the News </p>
      <p> Awards </p>
      <p> Careers </p>
      <p> Blog </p>
      </v-col>


      <v-col>
        <h5>Contact Us</h5>
         <p> Merchant Support </p>
         <p> Bulk Orders </p>
         <p> Press </p>
      </v-col>
      </v-row >
      <v-row>
      <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
      </v-row>
      </v-container>
    </v-footer>

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .black--text {
    border: 1px solid;
  }

   #inspire {
    background-color:white ;
    color: black;
  }
</style>