<template>
  <v-container class="grey lighten-5">
    <v-row
     
    >
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 6 : undefined"
        <breadcrumb/>
      >
        <v-card
          class="pa-5"
          outlined
          tile
        >
          {{ n === 1 ? '(wider)' : '' }}
        </v-card>
      </v-col>
     </v-row>
     <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <card/>
      >
      
      </v-col>
    </v-row>
    <v-row
      class="mb-6"
      no-gutters
    >
     
        <v-card
          class="pa-2"
          outlined
          tile
         >
          {{ n === 2 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col
        v-for="n in 1"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <loader/>
      >    
      <v-col
        v-for="n in 1"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <form/>
      >  
       <v-col
        v-for="n in 1"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <slideGroup2/>
      >  
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n === 1 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>