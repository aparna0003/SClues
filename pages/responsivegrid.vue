<template>
  <v-card flat dark height="100%">
    <v-container fluid>
      <v-layout column>
        <v-flex>{{player.name}}</v-flex>
        <v-flex>
          <v-img class="mx-4" :src="getPlayerImageUrl()"></v-img>
        </v-flex>
        <v-flex xs2 class="caption">
          <span>
            {{getCountryByCountryId(player.country_id).name}}
            <img
              :src="getCountryImageUrl(getCountryByCountryId(player.country_id).image)"
            >
          </span>
        </v-flex>
        <v-flex class="caption">{{jsUcfirst(player.position)}}</v-flex>
        <v-flex class="caption">{{formatPrice(player.value)}}</v-flex>
        <v-flex xs1>
          <v-btn class="amber lighten-1" light @click="$emit('add-player-to-squad', player); $emit('toggle-dialog', false)">Select</v-btn>
        </v-flex>
      </v-layout>
    </v-container>
  </v-card>
</template>