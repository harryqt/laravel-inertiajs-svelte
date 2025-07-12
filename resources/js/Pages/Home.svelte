<script>
    import { Button } from "$lib/components/ui/button/index.js";

    let count = $state(0);

    function increment() {
        count += 1;
    }
</script>

<Button onclick={increment}>
    Clicked {count}
    {count === 1 ? "time" : "times"}
</Button>
