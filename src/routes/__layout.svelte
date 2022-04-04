<script lang="ts">
  import "$lib/IbmPlexMonoFont.css";
</script>

<div class="keep-center">
  <div class="maxw">
    <slot />
  </div>
</div>

<style>
  :global(*) {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "IBM Plex Mono", monospace;
  }

  :global(body) {
    background-color: rgb(225, 225, 225);
  }

  .keep-center {
    display: flex;
    flex-direction: column;
    align-items: center;
    overflow-y: hidden;
  }

  .keep-center .maxw {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 2rem;
    margin-bottom: 2rem;
    margin-left: 2rem;
    margin-right: 2rem;
    max-width: 512px;
  }
</style>
