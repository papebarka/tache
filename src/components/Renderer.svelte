{#if title}
    { title }
{:else}
    <h1>Pas de titre</h1>
{/if}

<div class="">
    {#if content}
        {content}
    {:else}
        <p>Pas de contenu</p>
    {/if}

</div>


<script>
    export let title = ''
    export let content = ''
</script> 