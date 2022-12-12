<script>
const form_values={
    name:""
}
</script>

<main>
<div>
    <div>
    {JSON.stringify(form_values, null, 2)}
    </div>
    <label for="name">Name</label>
    <input type="text" name="" id="name" bind:value={form_values.name}>
</div>
</main>

<style>

</style>