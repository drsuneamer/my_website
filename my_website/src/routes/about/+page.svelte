<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<section>
	<div class="text-column">
	<div class="board">
		<div class="part">
			<h2>what I love</h2>
			<div class="tags">
				<div class="tag1">desert</div>
				<div class="tag1">cactus</div>
				<div class="tag1">The Little Prince</div>
				<div class="tag1">waking up late</div>
				<div class="tag1">Wes Anderson</div>
				<div class="tag1">The Beatles</div>
				<div class="tag1">traveling alone</div>
				<!-- <div class="tag1"></div> -->
			</div>
		</div>
		<div class="part">
			<h2>what I hate</h2>
			<div class="tags">
				<div class="tag2">morning</div>
				<div class="tag2">bell pepper</div>
				<div class="tag2">romance movies</div>
			</div>	
		</div>
	</div>
</div>
</section>


<style>
	section {
		font-family: 'KyoboHandwriting2021sjy';
	}

	h2 {
		font-weight: 900;
	}

	.board {
		display: flex;
		justify-content: center;
		align-items: start;
	}

	.part {
		width: 30vw;
		text-align: center;

	}

	.tags {
		display: flex;
		flex-wrap: wrap;
	} 

	.tag1 {
		font-family: 'Uiyeun';
		background-color: #ECA0D3;
		border-radius: 5px;
		color: white;
		padding: 3px;
		margin: 2px;
		font-size: 20px;
	}

	.tag2 {
		font-family: 'Uiyeun';
		background-color: #9F9F9F;
		border-radius: 5px;
		color: white;
		padding: 3px;
		margin: 2px;
		font-size: 20px;
	}

</style>