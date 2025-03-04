<script>
   import {Footer} from '$lib'
	let {children} = $props();
</script>

<header></header>

<main>
  {@render children()}
</main>

<Footer />

<style>
  main {
    padding: 3rem;
  }
</style>