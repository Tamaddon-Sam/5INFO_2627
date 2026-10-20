<script>
    import Counter from "#lib/components/counter.svelte";
    import DoubleCounter from "#lib/components/double_counter.svelte";
    

let contatore = 0;
let contator = 0;
</script>
<h1>Pagina Counter!!!</h1>
<h2>Il valore del contatore vale: {contatore}</h2>
<Counter bind:counter={contatore} />


<h2>Il valore del contatore vale: {contator}</h2>
<DoubleCounter bind:count={contator} />