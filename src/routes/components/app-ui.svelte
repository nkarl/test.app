<!-- App GUI -->
<script>
	export let data = [{}, {}];
</script>

<!-- App GUI -->
<div style="text-align:center">
	<h1>Welcome to My Yelp Business Data App!</h1>
</div>
<div class="app-container">
	<!-- Welcome Message -->
	<div class="panel">
		<div class="card">Card 1</div>
		<div class="card">Card 2</div>
	</div>
	<div class="panel">
		<div class="card">Card 3</div>
		<div class="card">Card 4</div>
	</div>
</div>

<!-- Style Sheet -->
<style>
	.app-container {
		/*text-align: center;*/
		width: 95vw;
		height: 90vh;
		display: flex;
		margin-left: 2vw;
		margin-right: 2vw;
	}

	.panel {
		border: 5px solid white;
		width: 1000px;
		height: 75rm;
		margin: 5px 5px;
		padding: 5px 5px;
		flex-direction: row wrap;
		border-radius: 25px;
	}

	.card {
		width: 400px;
		height: 200px;
		border: 5px dotted red;
		margin: 10px 10px;
		padding: 10px 10px;
		border-radius: 25px;
	}
</style>
