<template>
  <!--Your App Starts Here -->
  <v-app id="inspire" light>
    
    <!--Header -->
    <!--<v-app-bar color="red" dark fixed app>
      <v-toolbar-title>Application</v-toolbar-title>-->
       <!-- Component Example -->
       <v-row
         class md="6"
          no-gutters
         >
         <v-col
         md="1"
        ><VuetifyLogo/>
         </v-col>
         <v-col
           md="9"
           offset-md="1"
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
    <v-footer color="#55BCC9" app> <!--colour of the footer is changed-->
      <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
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
    background-color: grey;
  }
</style>