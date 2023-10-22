<script>
    export let werkvormData

    // console.log(werkvormData)
</script>

<ul>
    {#each werkvormData.data as werkvorm}
    <li>
        <h3>{werkvorm.id}</h3>
        <h3>{werkvorm.Titel}</h3>
    </li>
    {/each}
</ul>