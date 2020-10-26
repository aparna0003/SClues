<template>
  <v-card
    class="mx-auto light"
    flat
    outline
     color="#EDF8F9"
    elivation="0"
    width="1200"
  >
    
    <v-divider></v-divider>

    <v-virtual-scroll
      :items="items"
      :item-height="50"
      height="300"
    >
      <template v-slot:default="{ item }">
        <v-list-item
           >
         

          <v-list-item-content>
            <v-list-item-title
               class="grey--text text--darken-4"
               bold
            >
            {{ item.question }}            
            
            </v-list-item-title>

            <v-list-item-title
               class="dark grey--text"               
            >
            {{ item.review }}
            
            </v-list-item-title>
          </v-list-item-content>

          <v-list-item-action>
            
          </v-list-item-action>
        </v-list-item>
      </template>
    </v-virtual-scroll>
  </v-card>
</template>

<script>
  export default {
    data: () => ({
      colors: ['#2196F3', '#90CAF9', '#64B5F6', '#42A5F5', '#1E88E5', '#1976D2', '#1565C0', '#0D47A1', '#82B1FF', '#448AFF', '#2979FF', '#2962FF'],
      names: ['Are you varified', 'Is there any hidden cost', 'is iPencil compatible with iPhone 11 ', 'Can you provide more detailed info', 'When to expect for delivery after purcgase ?'],
      surnames: ['Sure. Please contact us in 15525415528', 'No. it is not', 'Sure actions will be taken according to the situation', 'No. We make sure of that'],
    }),

    computed: {
      items () {
        const namesLength = this.names.length
        const surnamesLength = this.surnames.length
        const colorsLength = this.colors.length

        return Array.from({ length: 10000 }, (k, v) => {
          const name = this.names[this.genRandomIndex(namesLength)]
          const surname = this.surnames[this.genRandomIndex(surnamesLength)]

          return {
            color: this.colors[this.genRandomIndex(colorsLength)],
            question: `${name} `,
            review: ` ${surname}`,
            initials: `${name[0]} ${surname[0]}`,
          }
        })
      },
    },

    methods: {
      genRandomIndex (length) {
        return Math.ceil(Math.random() * (length - 1))
      },
    },
  }
</script>