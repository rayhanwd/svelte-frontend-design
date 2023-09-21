<script>
  import "../app.postcss";
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<div class="app">
  <header>
    <Header />
  </header>
  <main>
    <slot />
  </main>

  <footer>
    <Footer />
  </footer>
</div>
