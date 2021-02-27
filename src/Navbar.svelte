<script>
  let carouselHeight;
</script>

<style>
  .navbar {
    position: absolute;
    z-index: 10;
    max-width: 100%;
    min-width: 100%;
  }

  .carousel img {
    object-fit: cover;
  }
</style>

<nav
  class="navbar navbar-expand-lg navbar-dark px-2"
  style="-webkit-transform: translate3d(0, 0, 1px); transform: translate3d(0, 0,
  1px)"
  bind:clientHeight={carouselHeight}>
  <a class="navbar-brand" href="/#/">
    <img src="/images/png/logo.png" alt="" height="49px" style="width: 49px" />
  </a>
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarToggler"
    aria-controls="navbarToggler"
    aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="navbar-toggler-icon" />
  </button>

  <div class="collapse navbar-collapse" id="navbarToggler">
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
      <li class="nav-item">
        <a class="nav-link" href="/#/">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/#/vote">Vote</a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="https://www.ageofelysianmc.com/shop"
          target="_blank">
          Donate
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="http://dynmap.ageofelysian.com/"
          target="_blank">
          Dynmap
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/#/resource-pack">Resource Pack</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/#/discord">Discord</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/#/dungeons">Dungeons</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/#/about">About</a>
      </li>
    </ul>
  </div>
</nav>

<div id="carousel" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img
        class="d-block w-100"
        style="height: {carouselHeight}px"
        src="/images/carousel/png/slide_1.png"
        alt="this looks nice"
        draggable="false" />
    </div>
    <div class="carousel-item">
      <img
        class="d-block w-100"
        src="/images/carousel/png/slide_2.png"
        alt="this also does"
        style="height: {carouselHeight}px"
        draggable="false" />
    </div>
    <div class="carousel-item">
      <img
        class="d-block w-100"
        src="/images/carousel/png/slide_3.png"
        alt="you really shouldn't be reading this..."
        style="height: {carouselHeight}px"
        draggable="false" />
    </div>
    <div class="carousel-item">
      <img
        class="d-block w-100"
        src="/images/carousel/png/slide_4.png"
        alt="you really shouldn't be reading this..."
        style="height: {carouselHeight}px"
        draggable="false" />
    </div>
    <div class="carousel-item">
      <img
        class="d-block w-100"
        src="/images/carousel/png/slide_5.png"
        alt="you really shouldn't be reading this..."
        style="height: {carouselHeight}px"
        draggable="false" />
    </div>
    <div class="carousel-item">
      <img
        class="d-block w-100"
        src="/images/carousel/png/slide_6.png"
        alt="you really shouldn't be reading this..."
        style="height: {carouselHeight}px"
        draggable="false" />
    </div>
  </div>
</div>
