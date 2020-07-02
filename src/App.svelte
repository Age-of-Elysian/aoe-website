<script>
  import Router, { link } from "svelte-spa-router";
  import Home from "./Home.svelte";
  import Vote from "./Vote.svelte";
  import Navbar from "./Navbar.svelte";
  import Footer from "./Footer.svelte";
  import Discord from "./Discord.svelte";
  import About from "./About.svelte";
  import ResourcePack from "./ResourcePack.svelte";

  const routes = {
    "/": Home,
    "/vote": Vote,
    "/discord": Discord,
    "/about": About,
    "/resource-pack": ResourcePack
  };
</script>

<Navbar />

<Router {routes} />

<Footer />
