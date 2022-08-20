<svelte:options tag={null} />

<script lang="ts">
	import BuyMeACoffee from '../lib/BuyMeACoffee.svelte';

	let bgColor: string,
		coffeeColor: string,
		fontFamily: string,
		fontVariant: string,
		cupColor: string,
		width: number,
		height: number,
		textColor: string,
		text: string,
		scale: number,
		useText = false;
</script>

<details open>
	<summary>Options</summary>
	<div class="input-group">
		<label for="text">Text</label>
		<input type="text" id="text" bind:value={text} />
	</div>
  <details>
    <summary>Font</summary>
    <div class="input-group">
		<label for="text">Font Family</label>
		<input type="text" id="text" bind:value={fontFamily} />
	</div>
	<div class="input-group">
		<label for="text">Font Variant</label>
		<input type="text" id="text" bind:value={fontVariant} />
	</div>
  </details>
  <details open>
    <summary>Size</summary>
    <div class="input-group">
		<label for="text">Height</label>
		<input type="text" id="text" bind:value={height} />
	</div>
	<div class="input-group">
		<label for="text">Width</label>
		<input type="text" id="text" bind:value={width} />
	</div>
	<div class="input-group">
		<label for="text">Scale</label>
		<input type="text" id="text" bind:value={scale} />
	</div>
  </details>
	<details>
		<summary>Colors</summary>
    <div class="input-group flex-grow-0">
      <label for="text">Background Color</label>
      <input type="color" id="text" bind:value={bgColor} class="w-3 flex-grow-0"/>
      {#if bgColor}<span class="pl-2">{bgColor}</span>{/if}
    </div>
    <div class="input-group flex-grow-0">
      <label for="text">Text Color</label>
      <input type="color" id="text" placeholder="#ff0000" bind:value={textColor} class="w-3 flex-grow-0"/>
      {#if textColor}<span class="pl-2">{textColor}</span>{/if}
    </div>
    <div class="input-group flex-grow-0">
      <label for="text">Coffee Color</label>
      <input type="color" id="text" bind:value={coffeeColor} class="w-3 flex-grow-0"/>
      {#if coffeeColor}<span class="pl-2">{coffeeColor}</span>{/if}
    </div>
    <div class="input-group flex-grow-0">
      <label for="text">Cup Color</label>
      <input type="color" id="text" bind:value={cupColor} class="w-3 flex-grow-0"/>
      {#if cupColor}<span class="pl-2">{cupColor}</span>{/if}
    </div>
  </details>
</details>
<details open>
	<summary>Code</summary>
  <code>
  &lt;BuyMeACoffee
    {#if bgColor}bgColor={bgColor}{/if}
    {#if coffeeColor}coffeeColor={coffeeColor}{/if}
    {#if fontFamily}fontFamily={fontFamily}{/if}
    {#if fontVariant}fontVariant={fontVariant}{/if}
    {#if height}height={height}{/if}
    {#if cupColor}outlineColor={cupColor}{/if}
    {#if scale}scale={scale}{/if}
    {#if text}text={text}{/if}
    {#if textColor}textColor={textColor}{/if}
    {#if width}width={width}{/if}
  /&gt;
  </code>
</details>
<BuyMeACoffee
	{bgColor}
	{coffeeColor}
	{fontFamily}
	{fontVariant}
	{height}
	{cupColor}
	{scale}
	{text}
	{textColor}
	{width}
/>

<style>
	details {
		@apply mx-4 border my-2 p-3 bg-gray-200;
	}
  .input-group {
    @apply border border-gray-400 bg-gray-300 rounded-lg m-2 p-1 flex;
  }
  .input-group label {
    @apply mx-2 text-gray-600 w-40;
  }
  .input-group input {
    @apply border w-full;
  }
  .input-group input[type="color"] {
    @apply border w-12;
  }
  code {
    @apply m-4 p-2 bg-gray-300 block border border-gray-400 rounded-xl;
  }
</style>
