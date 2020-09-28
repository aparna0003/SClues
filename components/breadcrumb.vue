<template>
  <v-breadcrumbs :items="items" light 
   > <!--to make font visivle-->
    <template v-slot:item="{ item }">
      <v-breadcrumbs-item
        :href="item.href"
        :disabled="item.disabled"
      >
        {{ item.text.toUpperCase() }} <!--to make the text uppercase-->
      </v-breadcrumbs-item>
    </template>
  </v-breadcrumbs>
</template>

<script>
  export default {
    data: () => ({
      items: [   //assigning the parts of the breadcrum text
        {
          text: 'Home Page',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        {
          text: 'iPhone',
          disabled: false,
          href: 'breadcrumbs_link_1',
        },
        {
          text: 'iPhone X',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
  }
</script>