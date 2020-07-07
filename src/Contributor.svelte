<script>
  export let name;
  export let rank;
  export let imagepng;
  export let imagewebp;
</script>

<style>
  .contributor {
    background: rgba(30, 30, 30) !important;
    padding: 2em;
    height: 12em;
    border-radius: 3px;
    display: inline-block;
  }
  .contributor > picture > img {
    display: block;
    height: auto;
    max-width: 100%;
    max-height: 100%;
  }
</style>

<div class="container p-4">
  <div class="contributor text-center">

    <picture class="mx-auto justify-content-center">
      <source srcset={imagewebp} type="image/webp" />
      <img src={imagepng} alt="{name}_{rank}" class="mx-auto" />
      {name}
      <br />
      {rank}
    </picture>

  </div>
</div>
