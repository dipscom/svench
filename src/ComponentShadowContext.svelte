<script>
  import { setContext } from './util.js'

  export let Component
  export let context

  setContext(context)
</script>

<svelte:component this={Component} />
