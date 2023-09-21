<script>
  import Comparison from "../components/Comparison.svelte";
  import Faq from "../components/Faq.svelte";
  import Heroarea from "../components/Heroarea.svelte";
  import Testimonial from "../components/Testimonial.svelte";
</script>

<svelte:head>
  <title>Trasing landing</title>
  <meta name="description" content="Awesome landing page is here" />
</svelte:head>

<div class="overflow-hidden">
  <Heroarea />
</div>
<Comparison />
<Testimonial />
<Faq />

<style>
</style>
