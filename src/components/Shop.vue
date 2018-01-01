<template>
  <div class="product-list u__lmt">
    <sb-shop locale="en"
             :view="$route.params.view"
             :id="$route.params.id"></sb-shop>
  </div>
</template>

<script>
export default {
  name: 'Shop'
}
</script>
