<script>
	import { page } from '$app/stores';
</script>

<h1 style={`color: ${$page.params.colour};`}>
	This route is {$page.params.colour}
</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with
	<code>src/routes/[colour]/index.svelte</code>.
</p>

<a href="/">back</a>
