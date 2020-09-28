<template>

 
 
 
    <v-toolbar
    
    class="cyan lighten-5 "
    elevation="0px" >
      

    <!--the icons for the tab is added-->

      <v-spacer></v-spacer>

      <v-btn icon light>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon light>
        <v-icon>mdi-heart</v-icon>
      </v-btn>
      <v-btn icon light>
        <v-icon>mdi-bell</v-icon>
      </v-btn>
      <v-btn icon light>
        <v-icon>mdi-cart</v-icon>
      </v-btn>

      <v-btn icon light>
        
      </v-btn>
      
          <v-menu
            bottom
            left
          >
            <template v-slot:activator="{ on, attrs }">
              <v-btn
               
                icon
                v-bind="attrs"
                v-on="on"
                light
              >
                <v-icon>mdi-menu</v-icon>
              </v-btn>
            </template>

            <v-list>
              <v-list-item
                v-for="(item, i) in items"
                :key="i"
                
              >  <!--hamburger menu is added-->
                <v-list-item-title>{{ item.title }}</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-menu>
       
    </v-toolbar>
    </div>
 
</template>

<!--the names dropdown menu is added-->
<script>
  export default {
    data: () => ({
      items: [
        { title: 'Made In India' },
        { title: 'Men' },
        { title: 'Women' },
        { title: 'Home Furnature' },
        { title: 'Electronics' },
        { title: 'Applience' },
        { title: 'Sports and More' },
        { title: 'Daily Essentials' },
        { title: 'Setting' },
      ],
    }),
  }
</script>