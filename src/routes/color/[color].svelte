<script>
	import { page } from '$app/stores';
</script>

<h1 style={`color: ${$page.params.color};`}>
	This route is {$page.params.color}
</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with
	<code>src/routes/color/[color].svelte</code>.
</p>

<a href="/">back</a>
