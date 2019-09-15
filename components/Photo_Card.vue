<template>
	<div class="h-screen">
	<div class="container mx-auto flex h-full justify-center items-center">
		<img src="~/static/oFace.jpg" class="inline-block h-screen w-auto rounded-lg shadow-md mx-auto">
  </div>
	</div>
</template>

<script>
	export default {
		name: "Photo_Card",
		data : function () {
			return{
				imageURL : "~static/oFace.jpg"
			}
		}
	}
</script>

<style scoped>


</style>
