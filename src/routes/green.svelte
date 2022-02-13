<script>
	import { page } from '$app/stores';
</script>

<h1 style="color: green;">This route is green</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with page
	<code>src/routes/green.svelte</code>.
</p>

<a href="/">back</a>
