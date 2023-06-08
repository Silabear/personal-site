<script lang="ts">
    import "../app.postcss";
  import Navbar from "../components/Navbar.svelte";
</script>

<svelte:head>
    <title>Silabear</title>
</svelte:head>

<div class="bg-stone-900 w-full min-h-screen font-brand text-orange-100">
    <Navbar />
    <div class="mx-10 lg:mx-48 mt-5">
        <slot />
    </div>
</div>