<script lang="ts">
    import favicon from "$lib/assets/doggo.gif";
    import "../app.css";
    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <title>hactuss linktree</title>
</svelte:head>

{@render children?.()}
