<script>
    let count = 2;
</script>

<button class="btn" on:click={() => (count += 1)}>
    Clicked {count}
    {count === 1 ? "time" : "times"}
</button>

<style>
    .btn {
        color: royalblue;
        font-size: 15px;
    }
</style>
