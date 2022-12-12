<script>

const list =["Abhishek", "Pandey", "is", "a", "good", "boy"];

const new_list=[
    {first:'Abhishek', last:'Pandey'},
    {first:'Ankit', last:'Pandey'},
    {first:'Jai', last:'Bajarangbali'},
    {first:'Jai', last:'shree Ram'},
    
]
</script>

<main>
{#each list as value, index}
<h2>{index+1}. {value}</h2>
{/each}
    


{#each new_list as name}
<h2>{name.first} {name.last}</h2>

{/each}
</main>


<style>

</style>