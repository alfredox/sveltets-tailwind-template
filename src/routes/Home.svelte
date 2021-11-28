<script lang="ts">
  import logo from '../assets/svelte.png'
  import Counter from '../lib/Counter.svelte'
</script>

<img src={logo} alt="Svelte Logo" class="inline-block w-64 h-64"/>
<h1 class="uppercase text-7xl text-red-600 font-thin my-8 mx-auto max-w-xs sm:max-w-none">Hello Typescript!</h1>

<Counter />

<p class="max-w-xs sm:max-w-none my-4 mx-auto leading-normal">
  Visit <a class="text-blue-800" href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
  apps.
</p>
<p class="max-w-xs sm:max-w-none my-4 mx-auto leading-normal">
  This is an application test. Should review the package.json to see the things related to TS.
</p>
<p class="max-w-xs sm:max-w-none my-4 mx-auto leading-normal">
  Check out <a class="text-blue-800" href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
  the officially supported framework, also powered by Vite!
</p>
<p class="max-w-xs sm:max-w-none my-4 mx-auto leading-normal">
  This branch implements the <a class="text-blue-800" href="https://github.com/ItalyPaleAle/svelte-spa-router">svelte-spa-router</a>. Review documentation on how to use it.
</p>
<p class="max-w-xs sm:max-w-none my-4 mx-auto leading-normal">
  The added routes are Lorem that manages parameters: for instance <a class="text-blue-800" href='/#/lorem/1'>/#/lorem/1</a>, and <a class="text-blue-800" href='/#/lorem/4'>/#/lorem/4</a>.
  Also implements the fallback route NotFound, in case no route is found, for instance. <a class="text-blue-800" href='/#/not-defined'>/#/not-defined</a>.
</p>
