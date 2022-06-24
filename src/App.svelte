<script lang="ts">
  import Header from './lib/Header.svelte';
  import Categories from './lib/Categories.svelte';
  import Card from './lib/Card.svelte';
  import Footer from './lib/Footer.svelte';
</script>

<Header />
<main>
  <Categories />
  <div class="grid">
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
</main>
<Footer />

<style>
 main .grid {
  place-content: center;
  display: grid;
  gap: 1.5em;
  padding: 2.5em 0;
 }
</style>