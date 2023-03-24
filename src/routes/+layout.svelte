<script lang="ts">
    import "../app.css";
	import Seo from "$lib/components/Seo.svelte";
    import Navbar from "./Navbar.svelte";
  </script>
  
  
<Navbar/>

<main>
    <slot/>
</main>

<style lang="postcss">
    :global(html)
    {
        scroll-behavior: smooth;
    }
</style>
<Seo/>