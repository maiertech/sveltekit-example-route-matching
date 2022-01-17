<script>
	import { page } from '$app/stores';
</script>

<h1 style={`color: ${$page.params.colour};`}>
	This route is {$page.params.colour}
</h1>

<p>
	This route is served from <code>{$page.url.pathname}</code> and is processed by
	<code>routes/[colour]/index.svelte</code>.
</p>

<a href="/">back</a>
