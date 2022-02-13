<script>
	import { page } from '$app/stores';
</script>

<h1>Error 404 (not found)</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with page
	<code>src/routes/__error.svelte</code>.
</p>

<a href="/">back</a>
