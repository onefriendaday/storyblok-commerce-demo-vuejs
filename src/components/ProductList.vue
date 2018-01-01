<template>
  <div class="product-list u__lmt" v-editable="blok">
    <sb-shop locale="en"
             :view="$route.params.view"
             :action="$route.params.action"
             :id="$route.params.id"></sb-shop>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
