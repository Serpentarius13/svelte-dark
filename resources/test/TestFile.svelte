<script lang="ts">

    const a = 1;

    $: b = a * 2;

    function svelte() {
        return "something"
    }

    const store = $writable()
</script>


<div>
    <div transition:flip>
        123
    </div>
</div>


<style lang="scss">

    a {
      color: red;
      font-size: calc(1.8 * 1.2rem);

</style>