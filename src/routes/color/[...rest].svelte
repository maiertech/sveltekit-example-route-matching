<script>
	import { page } from '$app/stores';
</script>

<h1>Rest parameter route</h1>

<p>
	This route is served from <code>{$page.url.pathname}</code> and is processed by
	<code>src/routes/color/[...rest].svelte</code>.
</p>
