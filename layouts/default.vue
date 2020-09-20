<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
    
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
          ><toolbar/>
         </v-col>
         </v-row>
      <catagory/>
    </v-app-bar>

    <!-- Body -->
    <v-content light>
      <nuxt /> 
    </v-content>
    
    <!-- Footer -->
    <v-footer color="#55BCC9" app>
      <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   #inspire {
    background-color: azure;
  }
</style>