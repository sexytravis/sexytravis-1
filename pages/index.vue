<template>
  <div>
   <Photo_Card :src=this.UwU></Photo_Card>
  </div>
</template>

<script>
	import Photo_Card from "../components/Photo_Card";
  export default {
		name: "index.vue",
	  components: {Photo_Card},
	  data:function() {
			return{
				UwU : '/assets/oFace.jpg'

      }
    }
  }
</script>

<style scoped>

</style>
