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
		<p>&copy; 2023 Isaiah Rice and Elliot Werner</p>
	</footer>
</div>

<style>
</style>
