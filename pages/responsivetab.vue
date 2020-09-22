<template>
  <v-container class="grey lighten-5">
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        md="4"
      >
        <v-card
          class=" ms-3 pa-md-2"
          outlined
          tile
        >
           <v-img
           height="550"
           src="https://images.unsplash.com/photo-1577720086684-eb7be1e40721?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"
         ></v-img>
        </v-card>
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
