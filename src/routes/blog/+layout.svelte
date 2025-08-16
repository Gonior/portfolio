<script lang="ts">
    import { resolve } from '$app/paths'
    let { children } = $props();
</script>
<h1>halaman blog</h1>
<a href="{resolve('/blog/hello-world')}">blog hello world</a>

{@render children()}