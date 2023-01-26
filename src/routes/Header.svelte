<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/favicon.webp';
</script>

<header class=header>
	<nav style="position:relative;">
		<ul>
			<li>
				<a href="/">
					<img class="logo" src={logo} alt="Logo" width="50px" height="50px" />
				</a>
			</li>
		</ul>
		<ul>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/extreme-weather' ? 'page' : undefined}>
				<a href="/extreme-weather">Extreme Weather</a>
			</li>
			<li aria-current={$page.url.pathname === '/dislocation' ? 'page' : undefined}>
				<a href="/dislocation">Dislocation</a>
			</li>
			<li aria-current={$page.url.pathname === '/taking-action' ? 'page' : undefined}>
				<a href="/taking-action" role="button" class="contrast" >What you can do</a>
			</li>
		</ul>
	</nav>
</header>

<style>
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

	.logo {
		min-width:50;
  	min-height:50;
	}

</style>