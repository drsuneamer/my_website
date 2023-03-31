<script>
	import Header from './Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<footer>
		<p>2023 <span class="nickname">dr<span class="sun">sun</span>eamer</span> all rights reserved 🫠</p>
	</footer>
</div>

<style>
	.app {
		font-family: 'KyoboHandwriting2021sjy';
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	.nickname {
		color: #FFC500;
	}

	.sun {
		color: #FF9700;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
		
	}

	footer p {
		font-weight: 600;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
