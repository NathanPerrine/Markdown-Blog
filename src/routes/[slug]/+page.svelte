<script lang="ts">
    import type { PageData } from './$types';

    export let data: PageData;
</script>

<svelte:head>
    <title>{data.meta.title}</title>
</svelte:head>