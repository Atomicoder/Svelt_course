<script>
	let name = "pepe"
	let age = 45

	function incrementAge(){
		age += 1
	}
</script>

<style>
	h1 {
		color: darkblue;
	}
</style>

<h1>Hello {name}! you are {age}!</h1>
<button on:click="{incrementAge}" >maaas!!!!</button>
