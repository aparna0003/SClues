<template>
  <div>
    
    <!--dimention of the scroll bar card-->
    <v-card
      elevation="0"
      max-width="1550"
      pa="0"
      ma="0"
      class="mx-auto"
    >
      <v-virtual-scroll
        :bench="benched"
        :items="items"
        height="300"
        item-height="64"
      >
        <template v-slot="{ item }">
          <v-list-item :key="item">
            <v-list-item-action>
              <v-btn
                fab
                small
                depressed
                color="primary"
              >
                {{ item }}
              </v-btn>
            </v-list-item-action>
            <!--to add the content in the scroll-->
            <v-list-item-content>
              <v-list-item-title>
                
                <strong> When will the next batch of products be available {{ }}</strong><br>
                 Ans:The product will be available within a month <strong> {{ }}</strong>
              </v-list-item-title>
            </v-list-item-content>

            
          </v-list-item>

          <v-divider></v-divider>
        </template>
      </v-virtual-scroll>
    </v-card>
  </div>
</template>

<script>
  export default {
    data: () => ({
      benched: 0,
    }),
    computed: {
      items () {
        return Array.from({ length: this.length }, (k, v) => v + 1)
      },
      length () {
        return 7000
      },
    },
  }
</script>