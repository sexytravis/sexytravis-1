<template>
	<div>
    <img :src=this.img>
  </div>
</template>

<script>
	export default {
		name: "Photo_Card",
      props :['img'],
	}
</script>

<style scoped>

</style>
