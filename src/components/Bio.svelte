<script>
  import Maket2011 from './profile/Maket2011Profile.svelte'
  import Admin from './profile/AdminProfile.svelte'

  export let author
</script>

{#if author == 'maket2011'}
    <Maket2011 />
{:else}
    <Admin />
{/if}
