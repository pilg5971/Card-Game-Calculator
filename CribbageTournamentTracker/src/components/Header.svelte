<script>
	import WebsiteLogo from '../lib/images/cribbage-logo.svg';
	import BellIcon from '../lib/images/bell.svg';
	import UserIcon from '../lib/images/user.svg';
	import ExitIcon from '../lib/images/exit.svg';
</script>

<!--Header section-->
<header>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container-fluid">
			<a class="navbar-brand" href="/">
				<img
					src={WebsiteLogo}
					alt="Cribbage Tournament Tracker logo"
					width="30"
					height="24"
					class="d-inline-block pe-2"
				/>
				Cribbage Tournament Tracker
			</a>
			<button
				class="navbar-toggler"
				type="button"
				data-bs-toggle="collapse"
				data-bs-target="#navbarNav"
				aria-controls="navbarNav"
				aria-expanded="false"
				aria-label="Toggle navigation"
			>
				<span class="navbar-toggler-icon" />
			</button>
		</div>
		<!--Navigation icons-->
		<div class="collapse navbar-collapse justify-content-end w-100" id="navbarNav">
			<form class="d-flex" role="search">
				<input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
				<button class="btn btn-outline-success me-2" type="submit">Search</button>
			</form>
			<ul class="navbar-nav">
				<li class="nav-item">
					<a class="nav-link active" href="/">
						<img
							src={BellIcon}
							alt="Bell Logo"
							width="30"
							height="24"
							class="d-inline-block pe-2"
						/>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link active" href="/">
						<img
							src={UserIcon}
							alt="User Logo"
							width="30"
							height="24"
							class="d-inline-block pe-2"
						/>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link active" href="/">
						<img
							src={ExitIcon}
							alt="Exit Logo"
							width="30"
							height="24"
							class="d-inline-block pe-2"
						/>
					</a>
				</li>
			</ul>
		</div>
	</nav>
</header>

<style>
</style>
