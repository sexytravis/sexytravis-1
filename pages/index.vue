<template>
  <div class="mx-auto text-center">
   <Photo_Card></Photo_Card>
  </div>
</template>

<script>
	import Photo_Card from "../components/Photo_Card";
  export default {
		name: "index.vue",
	  components: {Photo_Card},
	  data:function() {
			return{
			    imageURL : "/static/oFace.jpg"
      }
    }
  }
</script>

<style scoped>

</style>
