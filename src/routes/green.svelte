<script>
	import { page } from '$app/stores';
</script>

<h1 style="color: green;">This route is green</h1>

<p>
	This route is served from <code>{$page.url.pathname}</code> and is processed by
	<code>routes/green.svelte</code>.
</p>

<a href="/">back</a>
