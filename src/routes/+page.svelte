<script lang="ts">
	import { onMount } from 'svelte';
  import '../app.postcss'

  import {webAppStore } from '../store'
	import Layout from './+layout.svelte';

  const thaddiusLogoLight = new URL('$lib/img/thaddius-light.png', import.meta.url).href

  
  $: value = $webAppStore;

</script>

<div class="flex flex-col w-full justify-center">


<img class="mx-auto" src="{thaddiusLogoLight}" alt="" />

<p>Hey! Don't be a shitbird and miss out on your share of $THAD!</p>

<br />

{$value}

</div>

<style>

</style>