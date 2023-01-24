<script>
		import imgclimatechange from '$lib/images/image.svg';
</script>

<svelte:head>
	<title>Climate Change</title>
	<meta name="description" content="Climate Change" />
</svelte:head>


	<div class="text-column">
		<header style="padding: 10px 0px;">
			<h2>Climate Change</h2>
		</header>
	</div>
	
	<p>
		This is an image
	</p>

	<img src={imgclimatechange} alt="image" width="500rem" height="auto" />

<style>
	h2, h6 {
		padding: 0;
		margin: 0;
	}
</style>
