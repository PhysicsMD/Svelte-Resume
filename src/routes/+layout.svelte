<script lang="ts">
	import Header from './Header.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<div class="app">
	<Header />

	<main>
		{@render children() }
	</main>

	<footer>
		<p>Hosted by Alenn Wright, Powered by <a href="https://svelte.dev" target="_blank">Svelte</a></p>
	</footer>
</div>

<style>
	/* General Layout */
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		background-color: #e5e5f7;
		opacity: 1;
		background-image: linear-gradient(to right, #222222, #4f4f8b, #222222);
		color: #333;
		font-family: 'Arial', sans-serif;
	}

	/* Main Content Area */
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 2rem;
		width: 100%;
		max-width: 70rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	/* Footer Styling */
	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 1rem;
		background-color: #222222;
		color: #fff;
		font-size: 1.1rem;
	}

	footer a {
		color: #00c9a7;
		font-weight: bold;
		text-decoration: none;
	}

	footer a:hover {
		color: #ff9a00;
		text-decoration: underline;
	}

	/* Improved Typography */
	h1, h2, h3 {
		font-family: 'Roboto', sans-serif;
		font-weight: 600;
	}

	p {
		font-size: 1.1rem;
		line-height: 1.6;
	}

	/* Media Query for Responsiveness */
	@media (max-width: 768px) {
		.app {
			background-image: linear-gradient(to right, #333333, #4f4f8b, #333333);
		}

		main {
			padding: 1rem;
		}

		footer {
			font-size: 1rem;
			padding: 10px;
		}

		footer a {
			font-size: 1rem;
		}
	}

	@media (max-width: 480px) {
		footer {
			padding: 8px 0;
		}

		footer p {
			font-size: 0.9rem;
		}
	}
</style>
