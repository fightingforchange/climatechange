<script>
	import Header from './Header.svelte';
	import '@picocss/pico';
	import './styles.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<footer>
		<small>&copy; 2023 Isaiah Rice and Elliot Werner</small>
	</footer>
</div>

<style>
	.app {
		padding: 1.5rem;
	}
</style>
