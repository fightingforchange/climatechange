<script>
	
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Home" />
</svelte:head>

<div class="text-column">
	<header style="padding: 10px 0px; display: flex; justify-content:center; ">
		<h2>Raising Awareness About Climate Change</h2>
	</header>

<article> 
	Climate change is a big problem. As greenhouse gas emissions blanket the Earth, they trap the sun’s heat. This leads to global warming and climate change. The world is now warming faster than at any point in recorded history.
</article>

	<details style="padding-top: 20px;">
		<summary role="button">Why is climate change bad?</summary>
		<ul>
			<li>Extreme weather like droughts, huricanes, and floods are more common.</li>
			<li>Green house gasses from fossil fuels break down the ozone layer</li>
			<li>Ice melts causing sea level rise</li>
		</ul>
	</details>
</div>


<div style="display: flex; flex-direction:row; justify-content: center;">
	<a href="/taking-action" role="button" class="contrast" style="width: 100%;">What you can do</a>
</div>


<style>
	h2 {
		padding: 0;
		margin: 0;
	}
	.contrast {
		background-color:rgb(215,215,215);
		border-color:rgb(215,215,215);
		transition: background-color 0.15s;
		transition: color 0.15s;
	}
	.contrast:hover {
		background-color:rgb(175,175,175);
		border-color:rgb(175,175,175);
	}

</style>