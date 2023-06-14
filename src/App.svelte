<script>
  import Info from "./components/Info.svelte";
  import Hero from "./components/Hero.svelte";
  import Artists from "./components/Artists.svelte";

  let playMusic = true;

  $: console.log(playMusic);
</script>


<audio src="/jungle.mp3" autoplay loop bind:paused={playMusic} />
<button on:click={() => (playMusic = !playMusic)}>
  {#if !playMusic}
    <img src="/Headphones.gif" />
  {:else}
    <img src="/VerySmallSmilie.gif" />
  {/if}
</button>

<main>
  <Hero />
  <Info />
  <Artists />
</main>

<style>
  button {
    position: fixed;
    left: 1rem;
    top: 1rem;
    background: none;
    border: none;
    cursor: pointer;
    background: grey;
    border: 1px groove gainsboro;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50px;
    height: 50px;
    z-index: 2;
  }

  button img {
  }
</style>
