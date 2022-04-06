<script lang="ts">
  import PermaLink from "$lib/PermaLink.svelte";
  import Github from "@icons-pack/svelte-simple-icons/src/components/Github.svelte";
</script>

<div class="container">
  <img src="/img/hnsirc-t-b-trimmed.svg" alt="HNSIRC Logo" />
  <div class="nutshell">
    <PermaLink>
      <h2 id="in-a-nutshell">In a nutshell</h2>
    </PermaLink>
    <p>HNSIRC is channels on <a href="https://letspiss.net/" target="_blank">Pissnet</a></p>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="what-is-hnsirc">What is HNSIRC?</h2>
    </PermaLink>
    <div>
      <PermaLink>
        <h3 id="for-handshakers">For Handshakers</h3>
      </PermaLink>
      <div>
        <PermaLink>
          <h4 id="what-is-irc">What is IRC?</h4>
        </PermaLink>
        <p>
          IRC is basically an old protocol that was used for group chat on the internet. In the
          current era of the internet, it is no longer used because of its complexity and only left
          with users who have brains
        </p>
      </div>
      <div>
        <PermaLink>
          <h4 id="what-is-pissnet">What is Pissnet?</h4>
        </PermaLink>
        <p>
          <a href="https://letspiss.net/" target="_blank">Pissnet</a> is an IRC network which meant
          to be a shitposting arena. But the interesting thing is its infrastructure. Anyone can
          <a href="https://wiki.letspiss.net/wiki/So_you_want_to_link_to_pissnet" target="_blank"
            >link their own server</a
          > to the network and become an IRC operator (please don't be an asshole) which makes it probably
          the most decentralized (but not totally secure) IRC network
        </p>
        <p>
          Serious conversations are always welcome, but please note that anyone can always come and
          <a href="https://wiki.letspiss.net/wiki/Pissnet_history" target="_blank"
            >piss in the channel</a
          >
        </p>
      </div>
    </div>
    <div>
      <PermaLink>
        <h3 id="for-pissnet-users">For Pissnet users</h3>
      </PermaLink>
      <div>
        <PermaLink>
          <h4 id="what-is-handshake">What is Handshake?</h4>
        </PermaLink>
        <p>
          <a href="https://handshake.org/" target="_blank">Handshake</a> aims to solve
          centralization issues in DNS systems; the root zone and certificate authority. It uses the
          blockchain technology for root zone, which means you can have your own TLDs like .hnsirc
          (usually written as hnsirc/ with slash ("/") after the TLD without leading dot (".")) and
          <a
            href="https://en.wikipedia.org/wiki/DNS-based_Authentication_of_Named_Entities"
            target="_blank">DANE protocol</a
          > for SSL
        </p>
      </div>
    </div>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="what-actually-is-hnsirc">What actually is HNSIRC?</h2>
    </PermaLink>
    <p>
      Since Handshake and its community are decentralized, anyone can create their own community
      spaces anywhere. HNSIRC is just an another option for Handshake community to communicate over
      IRC on Pissnet
    </p>
    <p>
      HNSIRC isn't meant to be the main or the best community space but a more decentralized (but
      not totally secure) alternative way for Handshake community one
    </p>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="joining-pissnet">Joining Pissnet</h2>
    </PermaLink>
    <p>There are multiple ways to join Pissnet</p>
    <ul>
      <li>
        Connect to <a href="ircs://irc.letspiss.net/">ircs://irc.letspiss.net/</a>
      </li>
      <li>
        Connect to any server from <a
          href="https://wiki.letspiss.net/wiki/Great_big-ass_server_list_of_doom"
          target="_blank">Great big-ass server list of doom</a
        >
      </li>
      <li>
        Connect to <a href="ircs://hnsirc/">ircs://hnsirc/</a>
      </li>
      <li>
        <a href="https://wiki.letspiss.net/wiki/So_you_want_to_link_to_pissnet" target="_blank"
          >Link and join your own server</a
        >
      </li>
    </ul>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="channel-naming-standard">Channel naming standard</h2>
    </PermaLink>
    <p>
      For Handshake related channels, we use #handshake-* naming standard (for example
      #handshake-hip5, #handshake-xnhns), and #handshake for general Handshake related topics
    </p>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="channel-moderation">Channel moderation</h2>
    </PermaLink>
    <p>
      Since anyone can technically become an IRC operator on Pissnet, channel statuses become almost
      useless in moderation. So, let's assume that all channels are open to everyone and not owned
      by anyone
    </p>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="other-information">Other information</h2>
    </PermaLink>
    <div>
      <PermaLink>
        <h3 id="ssl-fingerprint-sha-256">SSL fingerprint (SHA-256)</h3>
      </PermaLink>
      <p class="wrap-anywhere">
        <span class="wrap-anywhere"
          >85d020fba7c75d8848ecacfb4622d9ae21011456af6f7bef0ea5330ba5834d58</span
        >
      </p>
    </div>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="who-am-i">Who am I?</h2>
    </PermaLink>
    <p>
      I'm <a href="https://noxt.us/" target="_blank">Noxturnix</a> (<a
        href="ipns://n.xtnx/"
        target="_blank">n.xtnx/</a
      >). The one who keeps shitposting on
      <a href="https://discord.gg/dEGxW7UDME" target="_blank">Handshake Discord</a> and spamming the
      test channel on <a href="https://hnschat/" target="_blank">HNSChat</a> and probably sniped your
      names
    </p>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="supporting-hnsirc">Supporting HNSIRC</h2>
    </PermaLink>
    <p>Thanks for considering supporting HNSIRC. You can</p>
    <ul>
      <li>
        <a href="https://hnsfund.titansofdata.org/donating-to-hns-fund" target="_blank"
          >Donate to HNS Fund</a
        >
      </li>
      <li>
        <a href="https://wiki.letspiss.net/wiki/So_you_want_to_link_to_pissnet" target="_blank"
          >Link your own server to Pissnet</a
        > to keep the network up and running
      </li>
      <li>Contribute to Handshake projects</li>
      <li>
        Contribute to Pissnet's <a href="https://github.com/pissnet/pissircd" target="_blank"
          >PissIRCd</a
        >
      </li>
    </ul>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="other-community-spaces">Other community spaces</h2>
    </PermaLink>
    <ul>
      <li>
        Discord: <a href="https://discord.gg/dEGxW7UDME" target="_blank">Handshake</a>
      </li>
      <li>
        Discord: <a href="https://discord.gg/jpRBscbgDy" target="_blank">Handshake</a> by @publius
      </li>
      <li>
        Discord: <a href="https://discord.gg/KwraRYhS6n" target="_blank">Namer Community</a> by
        <a href="https://www.namebase.io/" target="_blank">Namebase</a>
      </li>
      <li>
        Telegrem: <a href="https://t.me/handshake_hns" target="_blank">@handshake_hns</a>
      </li>
      <li>
        IRC: <a href="https://web.libera.chat/#handshake" target="_blank">#handshake</a> on Libera
      </li>
    </ul>
  </div>
  <div class="topic">
    <PermaLink>
      <h2 id="page-source-code">Page source code</h2>
    </PermaLink>
    <p>
      <Github size={22} />
      <a href="https://github.com/hnsirc/hnsirc-page" target="_blank">hnsirc/hnsirc-page</a>
    </p>
  </div>
</div>

<style>
  img {
    width: 12rem;
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

  ul {
    margin-top: 0.5rem;
    list-style-position: inside;
    text-indent: -1.4rem;
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

  .container > div ul {
    margin-left: 2.5rem;
  }

  .nutshell {
    margin-top: 2rem;
    margin-bottom: 1rem;
  }

  .nutshell > p {
    align-self: center;
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

  .wrap-anywhere {
    overflow-wrap: anywhere;
  }
</style>
