<template>
 <div>
  <p>This is detail page</p>
<p>{{sendData}}</p>
<p>{{city}}</p>
<p>{{returnDate}}</p>

 </div>
</template>

<script>
export default {
	name: 'Detail',
	mounted:function(){
		// Normally do some initialization For aexmaple : call the API
		console.log('when page is loaded do something')
	},
	data(){
		return {
			sendData:this.$route.params.sendDate,
			returnDate:this.$route.params.returnDate,
			city:this.$route.params.city
		}
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg-black {
    background-color: black;
  }

</style>
