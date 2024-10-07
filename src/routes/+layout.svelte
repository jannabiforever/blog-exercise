<script>
  import Header from "$lib/components/Header.svelte";
  import Footer from "$lib/components/Footer.svelte";
  import { SvelteUIProvider } from "@svelteuidev/core";
</script>

<SvelteUIProvider>
  <Header />
  <slot />
  <Footer />
</SvelteUIProvider>
