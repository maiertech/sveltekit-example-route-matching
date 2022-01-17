<script>
	import { page } from '$app/stores';
</script>

<h1>
	This route has no color
</h1>

<p>
	This route is served from <code>{$page.url.pathname}</code> and is processed by
	<code>routes/[nocolor].svelte</code>.
</p>

<a href="/">back</a>
