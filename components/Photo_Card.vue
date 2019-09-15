<template>
	<div class="bg-black rounded-lg overflow-hidden">
    <div class="p-6">
    <img :src="property.imageURL" :alt="property.imageAlt">
    </div>
  </div>
</template>

<script>
	export default {
		name: "Photo_Card",
      props :['property'],
	}
</script>

<style scoped>

</style>
