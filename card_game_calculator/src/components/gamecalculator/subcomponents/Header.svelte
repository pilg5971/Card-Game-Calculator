<script>
	const header = 'Featured';
	const title = 'The Game of Cribbage';
	const description =
		'Cribbage, or crib, is a card game, traditionally for two players, that involves playing and grouping cards in combinations which gain points. It can be adapted for three or four players.';
	const rules = 'https://bicyclecards.com/how-to-play/cribbage';
</script>

<div class="card mb-3">
	<div class="card-header">
		{header}
	</div>
	<div class="card-body">
		<h5 class="card-title">{title}</h5>
		<p class="card-text">{description}</p>
		<a href={rules} target="_blank" class="btn btn-primary">Game Rules</a>
	</div>
</div>

<style>
</style>
