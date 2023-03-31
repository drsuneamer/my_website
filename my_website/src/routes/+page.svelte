<script>
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>Hi, it's me sunyeong</h1>

	<div class="flex">
		<a href="https://www.github.com/drsuneamer">github</a>
		<p>&nbsp; | &nbsp;</p>
		<a href="https://blog.naver.com/cactusity">daily blog</a>
		<p>&nbsp; | &nbsp;</p>
		<a href="https://drsuneamer.tistory.com">tech blog</a>
	</div>

	<div class="board">
		<div class="contact">
			<div>📬Contact</div>
			<div>e-mail: sunyeong0412@gmail.com</div>
			<!-- <div>tech blog: <a href="https://drsuneamer.tistory.com">https://drsuneamer.tistory.com</a></div>
			<div>daily blog: <a href="https://blog.naver.com/cactusity">https://blog.naver.com/cactusity</a></div> -->
		</div>
	</div>
</section>

<style>
	section {
		font-family: 'KyoboHandwriting2021sjy';
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	.flex {
		display: flex;
	}

	.board {
		margin-top: 20px;
	}

	.contact {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	h1 {
		width: 100%;
		margin-bottom: 5px;
	}

	a {
		color: blueviolet;
	}

	p {
		margin: 0;
	}
</style>
