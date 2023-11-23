<script>
	import GameCalculator from '../components/gamecalculator/GameCalculator.svelte';
</script>

<svelte:head>
	<title>Card Game Calculator</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="container-fluid">
	<div class="row h-100">
		<div class="col-md-3 col-sm-12 bg-secondary p-0">
			<div class="list-group rounded-0">
				<a href="/" class="list-group-item list-group-item-action active" aria-current="true"
					>Cribbage</a
				>
				<a href="/" class="list-group-item list-group-item-action">Poker</a>
				<a href="/" class="list-group-item list-group-item-action">BlackJack</a>
				<a href="/" class="list-group-item list-group-item-action">Pinochle</a>
				<a
					href="/"
					class="list-group-item list-group-item-action disabled"
					tabindex="-1"
					aria-disabled="true">Go-Fish</a
				>
			</div>
		</div>
		<div class="col-md-9 col-sm-12 bg-dark p-3">
			<GameCalculator />
		</div>
	</div>
</div>

<style>
</style>
