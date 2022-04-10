<script lang="ts">
  import PermaLink from "$lib/PermaLink.svelte";
  import Github from "@icons-pack/svelte-simple-icons/src/components/Github.svelte";
</script>

<div class="container">
  <img src="/img/cringe.svg" alt="Cringe Logo" />
  <div class="topic">
    <PermaLink>
      <h2 id="proof-of-cringe-protocol">Proof of Cringe protocol</h2>
    </PermaLink>
    <p>
      you know, we see people are making power and we use it for Proof of Work. Now there is a lot
      of cringe nowadays so let's kinda propose Proof of Cringe protocol
    </p>
    <div>
      <PermaLink>
        <h2 id="cringe-blockchain">Cringe blockchain</h2>
      </PermaLink>
      <p>basically whoever is cringe is allowed to add new blocks to the chain</p>
      <p>
        if the user makes money from the project while keeping their private key on centralized
        platforms, we prioritize them
      </p>
    </div>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="decentralized-autonomous-cringe">Decentralized Autonomous Cringe</h2>
    </PermaLink>
    <p>
      if you disagree and you think you have a better idea than mine then don't make a pull request
      or create an issue. Just host it yourself. This name is listed on <a
        href="https://www.namebase.io/domains/proofofcringe"
        target="_blank">Namebase</a
      > lol
    </p>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="source-code">Source code</h2>
    </PermaLink>
    <p>
      <Github size={22} />
      <a href="https://github.com/Noxturnix/proofofcringe" target="_blank"
        >Noxturnix/proofofcringe</a
      >
    </p>
  </div>
</div>

<style>
  img {
    width: 22rem;
    align-self: center;
  }

  h2 {
    font-size: 1.4rem;
    align-items: stretch;
  }

  p {
    margin-top: 0.5rem;
    font-style: normal;
  }

  a {
    color: #000;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }

  .container > div div,
  p {
    margin-left: 1rem;
  }

  .topic {
    margin-top: 1rem;
  }

  .topic div {
    margin-top: 1rem;
  }

  .topic p :global(svg) {
    vertical-align: bottom;
  }
</style>
