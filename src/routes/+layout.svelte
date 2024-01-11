<script>
  import "../app.css";
  import Navbar from "../lib/nav/Navbar.svelte";
  import Footer from "../lib/footer/Footer.svelte";
</script>

<Navbar></Navbar>
<slot />
<Footer></Footer>
