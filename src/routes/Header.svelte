<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/favicon.webp';
</script>

<header class=header>
	<nav>
		<ul>
			<li>
				<a href="/">
					<img src={logo} alt="Logo" width="50px" height="auto" />
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
				<a href="/taking-action" role="button" class="contrast">What can you do</a>
			</li>
		</ul>
	</nav>
</header>