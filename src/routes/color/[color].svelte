<script>
	import { page } from '$app/stores';
</script>

<h1 style={`color: ${$page.params.color};`}>
	This route is {$page.params.color}
</h1>

<p>
	This page's path is <code>{$page.url.pathname}</code> and it is processed by
	<code>src/routes/color/[color].svelte</code>.
</p>

<a href="/">back</a>
