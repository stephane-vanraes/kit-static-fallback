<script>
	import { page } from '$app/stores';
</script>

<header>
	<nav>
		<a href="/" aria-current={$page.pathname == '/'}>home</a>
		<a href="/about" aria-current={$page.pathname == 'about'}>About</a>
	</nav>
</header>

<slot />
