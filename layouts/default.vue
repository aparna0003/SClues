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
           
           class=" col-xs-1 col-sm-1 col-md-2 col-lg-3 light"
          >
          <v-card
             
              class="cyan lighten-5 "
               pa="2" 
               tile
               max-height="500"
               elevation= "0 px"
               >
              <VuetifyLogo/>  <!--persistant tool bar is added-->
          </v-card>
         </v-col>
        
         <v-col
           class="  col-xs-4 col-sm-7 col-md-9 col-lg-9 light"
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
    <v-footer color="white" 
    light> <!--colour of the footer is changed-->
    <!--footer content is added-->
     <v-container class="menubar2">  <!--first div for the conversion of the footer-->
      <v-row class="smallbody ">
    <!--adding the colums one by one-->
      <v-col >
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

       <v-container class="menubar1"> <!--second div for the conversion of the footer-->
      <v-row>

      <v-col >
     
      <h5 class="code">Useful Links</h5>
     <p class="smallbody"> Easy Returns & Replacements  |  Privacy Policy  |  User Agreement  |
         Notes to Security Practices  |  Labor Compliance  |  Shopper Central  |
         Merchant Central  |  About Us  |  Contact Us  |  Press 
      </p>
     
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
  .menubar2 {
           display:none;
         }
  @media (min-width: 1025px) {
         .menubar1 {
           display:none;
         }
         .menubar2 {
           display:block;
         }
      }
</style>