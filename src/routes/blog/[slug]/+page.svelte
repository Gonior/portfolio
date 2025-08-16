<script lang="ts">
    import type { PageProps } from "./$types"
    let { data } : PageProps = $props()

</script>

<h1>{data.title}</h1>
<p>{@html data.content}</p>
<a href="/blog">kembali</a>
<a href="/">kembali ke beranda</a>