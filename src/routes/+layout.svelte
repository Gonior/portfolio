<script lang="ts">
	import { resolve } from '$app/paths'
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
	console
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<nav>
	<a href="{resolve("/")}">Home</a>
	<a href="{resolve("/about")}">About</a>
	<a href="{resolve("/blog")}">Blog</a>
</nav>
<div class="">
	{@render children?.()}
</div>
