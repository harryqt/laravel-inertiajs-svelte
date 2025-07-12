<script>
    let count = $state(0);

    function increment() {
        count += 1;
    }
</script>

<button
    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
    onclick={increment}
>
    Clicked {count}
    {count === 1 ? "time" : "times"}
</button>
