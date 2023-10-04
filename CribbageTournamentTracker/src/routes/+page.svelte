<script>
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="container-fluid">
  <div class="row h-100">
    <div class="col-md-3 col-sm-12 bg-secondary p-0">
      <div class="list-group">
        <a href="/" class="list-group-item list-group-item-action active" aria-current="true">Tournament 1</a>
        <a href="/" class="list-group-item list-group-item-action">A second link item</a>
        <a href="/" class="list-group-item list-group-item-action">A third link item</a>
        <a href="/" class="list-group-item list-group-item-action">A fourth link item</a>
        <a href="/" class="list-group-item list-group-item-action disabled" tabindex="-1" aria-disabled="true">A disabled link item</a>
      </div>
    </div>
    <div class="col-md-9 col-sm-12 bg-dark">
      <div class="text-center">
        <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasScrolling" aria-controls="offcanvasScrolling">Team Chat</button>
      </div>
    </div>
    <div class="offcanvas offcanvas-end" data-bs-scroll="true" data-bs-backdrop="false" tabindex="-1" id="offcanvasScrolling" aria-labelledby="offcanvasScrollingLabel" style="margin-top: 3.6rem">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasScrollingLabel">Team Chat</h5>
        <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <p>Chat Elements...</p>
      </div>
    </div>
  </div>
</div>

<style>
</style>
