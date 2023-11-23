<script>
	import Navigation from '../components/Navigation.svelte';
	import './styles.css';
</script>

<div class="app">
	<Navigation />

	<main class="d-flex flex-grow-1">
		<slot />
	</main>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
	}
</style>
