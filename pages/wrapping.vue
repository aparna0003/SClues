<template>
  <v-container class="grey lighen-0">
    <v-row >  <!--removed the gutter-->
      <v-col cols="3">
        <v-card         
          class="pa-6"
          outlined
          tile
        >
          .col-9
        </v-card>
      </v-col>
      <v-col cols="3">
        <v-card            
          class="pa--10"  
          outlined  
          tile
        >
          .col-4<br>Since 9 + 5= 14 &gt; 12, this 4-column-wide div gets wrapped onto a new line as one contiguous unit.
        </v-card>
      </v-col>
      <v-col cols="12">
        <v-card
          class="pa-2"
          outlined
          tile                 
        >
          .col-6<br>Subsequent columns continue along the new line.<br>what to dod whaty to doooooooooooo
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>