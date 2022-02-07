<script>
	import { page } from '$app/stores';
</script>

<h1>This route has no color</h1>

<p>
	This page's path is <code>{$page.url.pathname}</code> and it is processed by
	<code>src/routes/[nocolor].svelte</code>.
</p>

<a href="/">back</a>
