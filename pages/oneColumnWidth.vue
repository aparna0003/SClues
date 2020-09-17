<template>
  <v-container class="grey lighten-5">
    <v-row
      class="mb-6"
      no-gutters
    >
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 6 : undefined"
        <breadcrumb/>
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 3 {{ n === 1 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <carousel/>
      >
       <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <card/>
      >
       <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <toolbar/>
      >
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <avatar/>
      >
       <v-col
        v-for="n in 2"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <breadcrumb/>
      >
       <v-col
        v-for="n in 2"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <hover/>
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 3 {{ n === 2 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
     <v-row
      class="mb-6"
      no-gutters
    >
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 6 : undefined"
        <breadcrumb/>
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 3 {{ n === 1 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <loader/>
      >
       <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <tab/>
      >
       <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <button/>
      >
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <breadcrumb/>
      >
       <v-col
        v-for="n in 2"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <breadcrumb/>
      >
      >
       <v-col
        v-for="n in 2"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <slideGroup/>
         <v-col
        v-for="n in 2"
        :key="n"
        :cols="n === 2 ? 5 : undefined"
        <icon/>
      >
        <v-card
          class="pa-3"
          outlined
          tile
        >
          {{ n }} of 3 {{ n === 2 ? '(wider)' : '' }}
        </v-card>
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
          {{ n }} of 3 {{ n === 2 ? '(wider)' : '' }}
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
        <slideGroup/>
      >  
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 3 {{ n === 1 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>