<script>
	import { page } from '$app/stores';
</script>

<h1 style="color: red;">This route is red</h1>

<p>
	This page's path is <code>{$page.url.pathname}</code> and it is processed by
	<code>src/routes/red.svelte</code>.
</p>

<a href="/">back</a>
