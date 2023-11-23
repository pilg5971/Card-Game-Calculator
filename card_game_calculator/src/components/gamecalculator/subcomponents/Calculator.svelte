<script>
	import CardGamePhoto from '../../../lib/images/CardGamePhoto.jpg';
</script>

<div class="card">
	<img
		src={CardGamePhoto}
		class="card-img-top"
		alt="Cribbage Hand"
		style="height: 200px; object-fit: cover;"
	/>
	<div class="card-body">
		<h5 class="card-title">Cribbage Hand Calculator</h5>
		<p class="card-text">
			Provided the basic rules of Cribbage above, please enter the following fields to calculate the <i
				>optimal</i
			> card to play.
		</p>
		<form>
			<select class="form-select form-select mb-3" aria-label=".form-select example">
				<option selected>Current Count</option>
				<option value="1">One</option>
				<option value="2">Two</option>
				<option value="3">Three</option>
			</select>
			<select class="form-select form-select mb-3" aria-label=".form-select example">
				<option selected>Number of Players</option>
				<option value="1">One</option>
				<option value="2">Two</option>
				<option value="3">Three</option>
			</select>
			<div class="mb-3 form-check">
				<input type="checkbox" class="form-check-input" id="exampleCheck1" />
				<label class="form-check-label" for="exampleCheck1">Are you currently winning?</label>
			</div>
			<button type="submit" class="btn btn-primary">Submit</button>
		</form>
	</div>
</div>

<style>
</style>
