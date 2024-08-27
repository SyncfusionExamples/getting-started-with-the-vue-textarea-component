<script setup>
import { TextAreaComponent as EjsTextarea } from '@syncfusion/ej2-vue-inputs';
</script>

<template>
<div class="textarea">
  <ejs-textarea width="200" :enabled="false" 
   floatLabelType="Never"
   rows="3" cols="50" resizeMode="Both"
   maxLength="8" readOnly="true" value="Comments">
  </ejs-textarea>
</div>
</template>

<style>
@import "../node_modules/@syncfusion/ej2-base/styles/fluent.css";
@import "../node_modules/@syncfusion/ej2-vue-inputs/styles/fluent.css";
.textarea {
  padding-bottom: 160px;
}
</style>
