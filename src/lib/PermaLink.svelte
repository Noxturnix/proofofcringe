<script lang="ts">
  import FontAwesome from "svelte-fa/src/fa.svelte";
  import { faLink } from "@fortawesome/free-solid-svg-icons";
  import { onMount } from "svelte";

  let permalink: string = "";

  let divElement: HTMLDivElement;
  let aElement: HTMLAnchorElement;
  let slotElement: HTMLElement;
  let faElement: SVGSVGElement;

  onMount(() => {
    aElement = divElement.children.item(0) as HTMLAnchorElement;
    slotElement = aElement.children.item(0) as HTMLElement;
    faElement = aElement.children.item(1) as SVGSVGElement;

    permalink = slotElement.id;

    faElement.style.fontSize = `${
      parseFloat(window.getComputedStyle(slotElement).fontSize) / 1.25
    }px`;
  });

  const onMouseEnter = () => {
    faElement.style.visibility = "visible";
  };

  const onMouseLeave = () => {
    faElement.style.visibility = "hidden";
  };
</script>

<div bind:this={divElement} on:mouseenter={onMouseEnter} on:mouseleave={onMouseLeave}>
  <a href={`#${permalink}`}><slot /><FontAwesome class="fa" icon={faLink} /> </a>
</div>

<style>
  div :global(*) {
    display: inline-block;
  }

  div :global(svg) {
    margin-left: 0.5rem;
    visibility: hidden;
  }

  a {
    color: black;
  }
</style>
