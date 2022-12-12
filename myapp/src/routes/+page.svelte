<script>
const first_name ="<b>Abhishek</b>";
const last_name ="<b>pandey</b>";
const hack = `<a href="#" onclick="alert('You have been hacked!')">Win a prize!</a>`;
const id="heading";
const disabled =true;
</script>


<main>
<h1>Hello world</h1>
<div>Channel</div>
<div>{ @html first_name}{last_name}</div>
<div>{@html hack}</div>
<div {id}>This is id</div>
<button {disabled}>This is button</button>
</main>



<style>
    main{
        text-align: center;
        margin: 0 auto;
    }
    h1{
        color: orangered;
        text-transform: uppercase;
        font-size:4rem;
        font-weight: 100;
    }

</style>