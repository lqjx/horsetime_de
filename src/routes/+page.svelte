<script lang="ts">
    import {fade} from "svelte/transition";
    import Hero from "$lib/Home/Hero.svelte";
    import Services from "$lib/Home/Services.svelte";
    import GlobalFooter from "$lib/GlobalFooter.svelte";
    import AboutUs from "$lib/Home/AboutUs.svelte";
</script>

<div transition:fade>
    <Hero/>
    <Services/>
    <AboutUs/>
    <GlobalFooter/>
</div>