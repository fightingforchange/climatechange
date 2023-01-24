<script>
		import imgclimatechange from '$lib/images/image.svg';
</script>

<svelte:head>
	<title>Extreme Weather</title>
	<meta name="description" content="Climate Change" />
</svelte:head>


	<div class="text-column">
		<header style="padding: 10px 0px;">
			<h2>Extreme Weather</h2>
		</header>
	</div>
	
	<p>
		This is an image
	</p>

	<div>
		<img src={imgclimatechange} alt="image" width="300" height="auto" />
	</div>
	

<style>
	h2, h6 {
		padding: 0;
		margin: 0;
	}
</style>
