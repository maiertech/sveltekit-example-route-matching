<script>
	import { page } from '$app/stores';
</script>

<h1 style="color: red;">This route is red</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with
	<code>src/routes/red.svelte</code>.
</p>

<a href="/">back</a>
