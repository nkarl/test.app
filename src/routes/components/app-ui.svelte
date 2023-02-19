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
		<h2>State List DropDown</h2>
		<select id="data-option-list" name="">
			<option id="item01" value="">State 01</option>
			<option id="item02" value="">State 02</option>
			<option id="item03" value="">State 03</option>
			<option id="item04" value="">State 04</option>
			<option id="item05" value="">State 05</option>
		</select>
		<h2>City List</h2>
		<div class="card">Card 2</div>
	</div>
	<div class="panel">
		<h2>City List DropDown</h2>
		<select id="data-option-list" name="">
			<option id="item01" value="">City 01</option>
			<option id="item02" value="">City 02</option>
			<option id="item03" value="">City 03</option>
			<option id="item04" value="">City 04</option>
			<option id="item05" value="">City 05</option>
		</select>
		<h2>Business List</h2>
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
		border: 5px solid gray;
		width: 1000px;
		height: 75rm;
		margin: 5px 5px;
		padding: 2% 2%;
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

	#data-option-list {
		width: 90%;
		margin-left: 2%;
		margin-right: 2%;
		margin-bottom: 5%;
		height: 5%;
		font-size: 1rm;
	}
</style>
