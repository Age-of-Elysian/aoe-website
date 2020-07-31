<script>
  export let name;
  export let rank;
</script>

<style>
  .contributor {
    background: rgba(30, 30, 30) !important;
    padding: 2em;
    height: 12em;
    border-radius: 3px;
  }

  .contributor > picture > img {
    display: block;
    height: auto;
    max-width: 100%;
    max-height: 100%;
  }
</style>

<div class="col p-4 w-100">
  <div class="contributor text-center mx-auto">
    <picture class="mx-auto justify-content-center">
      <source
        srcset={`/images/contributors/webp/${name.toLowerCase()}.webp`}
        type="image/webp"
        class="mx-auto" />
      <img
        src={`/images/contributors/png/${name.toLowerCase()}.png`}
        alt="{name}_{rank}"
        class="mx-auto" />
    </picture>
    <div class="m-2">
      <span>{name}</span>
      <br />
      <span class="badge bg-success">{rank}</span>
    </div>
  </div>
</div>
