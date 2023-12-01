<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad debitis aliquam non veniam quos beatae praesentium ducimus laboriosam sequi sed soluta, assumenda iste a libero explicabo rerum vel optio exercitationem! Nam ipsum aliquid vero dolor recusandae illo, voluptatem incidunt quas, ducimus et quos exercitationem iusto laboriosam, aperiam deleniti voluptate veniam.</p>
  </div>
</template>

<script setup>

definePageMeta({
  layout: 'products'
})

const { id } = useRoute().params

</script>

<style scoped>

</style>