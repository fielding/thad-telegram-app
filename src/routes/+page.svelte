<script lang="ts">
  import '../app.postcss'

  import {webAppStore } from '../store'

  const thaddiusLogoLight = new URL('$lib/img/thaddius-light.png', import.meta.url).href



</script>

<div class="flex flex-col w-full justify-center">


<img class="mx-auto" src="{thaddiusLogoLight}" alt="" />

<p class="mx-auto">Hey! Don't be a shitbird and miss out on your share of $THAD!</p>

<br />

{$webAppStore}

</div>

<style>

</style>