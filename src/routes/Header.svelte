<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/logo.svg';
</script>

<header class=header>
	<nav>
		<ul class="corner">
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
			<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>
				<a href="/climate-change">Climate Change</a>
			</li>
		</ul>
	</nav>
</header>

<style>
</style>
