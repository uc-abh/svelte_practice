<script>
    let count =0;
    function handleClick(){
        count=count+1;
    }
</script>

<main>
<button on:click={handleClick}>Count{count}</button>
</main>

<style>

</style>