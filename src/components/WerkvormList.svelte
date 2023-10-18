<script>
    const data = fetch('http://localhost:8055/items/Werkvorm')
        .then(response => response.json())
        .then(data => {
            console.log(data)
        })
        .catch(error => {
            console.error(error)
        })

    console.log(data)

</script>

<ul>
    <!-- {#each werkvormen as werkvorm}
    <li>
        <h3>{werkvorm.title}</h3>
    </li>
    {/each} -->
</ul>