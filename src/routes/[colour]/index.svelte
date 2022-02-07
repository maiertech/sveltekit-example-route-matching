<script>
	import { page } from '$app/stores';
</script>

<h1 style={`color: ${$page.params.colour};`}>
	This route is {$page.params.colour}
</h1>

<p>
	This page's path is <code>{$page.url.pathname}</code> and it is processed by
	<code>src/routes/[colour]/index.svelte</code>.
</p>

<a href="/">back</a>
