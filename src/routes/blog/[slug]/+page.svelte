<script lang="ts">
    import { resolve } from "$app/paths";
    import type { PageProps } from "./$types"
    let { data } : PageProps = $props()

</script>

<h1>{data.title}</h1>
<p>{@html data.content}</p>
<a href="{resolve('/blog')}">kembali</a>