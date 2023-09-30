<script>
  import "../app.css";
  import Navbar from "$lib/components/Navbar.svelte"
</script>

<main class="flex flex-col">
  <Navbar />
  <slot />
</main>