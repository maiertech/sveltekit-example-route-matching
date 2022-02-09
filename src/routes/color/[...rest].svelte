<script>
	import { page } from '$app/stores';
</script>

<h1>Rest parameter route</h1>

<p>
	This is route <code>{$page.url.pathname}</code>, which is rendered with
	<code>src/routes/color/[...rest].svelte</code>.
</p>

<a href="/">back</a>
