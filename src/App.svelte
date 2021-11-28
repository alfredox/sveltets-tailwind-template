<script lang="ts">
  import Router from 'svelte-spa-router';
  import routes from './routes';
</script>

<main class="text-center p-4 my-0 mx-auto">
  <Router {routes} />
</main>
