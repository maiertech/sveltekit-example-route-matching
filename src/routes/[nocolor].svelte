<script>
	import { page } from '$app/stores';
</script>

<h1>This route has no color</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with page
	<code>src/routes/[nocolor].svelte</code>.
</p>

<a href="/">back</a>
