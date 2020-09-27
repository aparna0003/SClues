<template>
  <div id="app">
    <div id='container' style="margin:50px auto 0; width:100%;">
        <br>
         <ejs-toolbar >
    <e-items>
             <e-item text='Cut' prefixIcon = 'e-cut-icon'></e-item>
             <e-item text='Copy' prefixIcon = 'e-copy-icon'></e-item>
             <e-item text='Paste' prefixIcon = 'e-paste-icon'></e-item>
             <e-item type='Separator'></e-item>
             <e-item text='Undo' prefixIcon = 'e-bold-icon'></e-item>
             <e-item text='Redo' prefixIcon = 'e-underline-icon'></e-item>
             <e-item text='Redo' prefixIcon = 'e-italic-icon'></e-item>
             <e-item type='Separator'></e-item>
             <e-item text='A-Z Sort' prefixIcon = 'e-ascending-icon'></e-item>
             <e-item text='Z-A Sort' prefixIcon = 'e-descending-icon'></e-item>
             <e-item text='Clear' prefixIcon = 'e-clear-icon'></e-item>
          </e-items>
    </ejs-toolbar>
    <link href="https://ej2.syncfusion.com/angular/demos/src/toolbar/toolbar.component.css" rel="stylesheet" />
    </div>
  </div>
</template>
<script>
import Vue from 'vue';
import { ToolbarPlugin } from "@syncfusion/ej2-vue-navigations";
Vue.use(ToolbarPlugin);

export default {
  name: 'app',
}
</script>
<style>
  @import "../../node_modules/@syncfusion/ej2-base/styles/material.css";
  @import "../../node_modules/@syncfusion/ej2-vue-buttons/styles/material.css";
  @import "../../node_modules/@syncfusion/ej2-vue-popups/styles/material.css";
  @import "../../node_modules/@syncfusion/ej2-vue-navigations/styles/material.css";

.custom_bold .e-tbar-btn-text {
    font-weight: 900;
}

.custom_italic .e-tbar-btn-text {
    font-style: italic;
}

.custom_underline .e-tbar-btn-text {
    text-decoration: underline red;
}

.e-txt-casing .e-tbar-btn-text {
    font-variant: small-caps;
}

.e-tbar-btn .e-icons {
    font-family: 'Material_toolbar';
    font-size: 16px;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
}
</style>