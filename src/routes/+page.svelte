<script lang="ts">
    import {fade} from "svelte/transition";
    import Hero from "$lib/Home/Hero.svelte";
    import Services from "$lib/Home/Services.svelte";
    import GlobalFooter from "$lib/GlobalFooter.svelte";
</script>

<div transition:fade>
    <Hero/>
    <Services/>
    <GlobalFooter/>
</div>