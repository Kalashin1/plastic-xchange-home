<script>
  import Nav from "../components/Nav.svelte";
	import Footer from "../components/Footer.svelte";
  // export let segment;
</script>

<div class="container-xxl bg-white p-0">
  <Nav />
  <slot></slot>
	<Footer />
</div>
