<script>
	import { injectSpeedInsights } from "@vercel/speed-insights/sveltekit"
	injectSpeedInsights();
	import { dev } from '$app/environment';
	// @ts-ignore
	import { inject } from '@vercel/analytics';
 
inject({ mode: dev ? 'development' : 'production' });
	import Header from './Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<footer class="footer">
		<div class="content has-text-centered">
			<strong>Estonya Startup Topluluğu</strong>2023 - 2024
		</div>
	  </footer>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
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

	footer strong {
		padding: 0.5em;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
