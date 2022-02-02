<script>
	import { page } from '$app/stores';
</script>

<h1 style={`color: ${$page.params.color};`}>
	This route is {$page.params.color}
</h1>

<p>
	This route is served from <code>{$page.url.pathname}</code> and is processed by
	<code>routes/color/[color].svelte</code>.
</p>

<a href="/">back</a>
