<template>
	<div v-if="motor">
		<p>{{motor.name}}</p>
		<img v-bind:src="motor.img" width="500px">
		<p>{{motor.location}}</p>
		<p>{{motor.year}}</p>
		<p>{{motor.description}}</p>

	</div>
</template>

<script>
export default {
	name: 'Car',
	mounted:function(){
		// Normally do some initialization For aexmaple : call the API
		console.log('when page is loaded do something')
		let url = 'https://api.sheety.co/4db58997dd33ab7eaa3d621c48bdea06/motors/sheet1/'+this.id;
		fetch(url)
		.then((response) => response.json())
		.then(json => {
 
  this.motor = json.sheet1
});
	},
	data(){
		return {
			id:this.$route.params.id,
			motor:null
			// sendData:this.$route.params.sendDate,
			// returnDate:this.$route.params.returnDate,
			// city:this.$route.params.city
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
