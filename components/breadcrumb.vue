<template>
  <v-breadcrumbs :items="items">
    <template v-slot:item="{ item }">
      <v-breadcrumbs-item
        :href="item.href"
        :disabled="item.disabled"
      >
        {{ item.text.toUpperCase() }}
      </v-breadcrumbs-item>
    </template>
  </v-breadcrumbs>
</template>

<script>
  export default {
    data: () => ({
      items: [
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