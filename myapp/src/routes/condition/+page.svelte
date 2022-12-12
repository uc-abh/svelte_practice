<script>
    import Myapp from '../../Components/Myapp.svelte'
    import Footer from '../../Components/Footer.svelte'
    const num="5";
</script>

<main>
{#if num===0}
<h2>This is zero</h2>
{:else if num <0}
<h2>Number is negative number</h2>
{:else if num>0}
<h2>This is positive number</h2>
{:else}
<h2>This is not a nuumber</h2>
{/if}
</main>
<Myapp/>

<Footer/>

<style>
    
</style>