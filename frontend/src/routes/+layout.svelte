<script lang="ts">
  import Header from '../components/templates/Header.svelte'
  import '../app.css'
</script>

<Header />

<main>
  <slot></slot>
</main>

<style>
  main {
    padding: 2rem;
  }
</style>
