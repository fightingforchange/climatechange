<script>
	import Header from './Header.svelte';
	import '@picocss/pico';
	import './styles.css';
</script>

<div class="app" style="min-height:100vh; display:flex; flex-direction:column; 
justify-content:space-between;">
	<div>
		<Header />

		<main>
			<slot />
		</main>

	</div>

	<footer>
		<small>&copy; 2023 Isaiah Rice and Elliot Werner</small>
	</footer>
</div>

<style>
	.app {
		padding: 1.5rem;
	}
</style>