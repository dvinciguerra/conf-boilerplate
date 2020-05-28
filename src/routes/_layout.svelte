<script>
  import Navbar from '../components/Navbar.svelte'
</script>

<svelte:head>
  <link
    rel="stylesheet"
    href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" />
</svelte:head>

<Navbar />

<main>
  <slot />
</main>
