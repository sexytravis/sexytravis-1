<template>
  <div>
    <photo_album></photo_album>
  </div>
</template>

<script>
	import Photo_Card from "../components/Photo_Card";
  import Photo_album from "../components/photo_album";
  export default {
		name: "index.vue",
	  components: {Photo_album, Photo_Card},
	  data:function() {
			return{
				pics : [
            {}
        ]
      }
    }
  }
</script>

<style scoped>

</style>
