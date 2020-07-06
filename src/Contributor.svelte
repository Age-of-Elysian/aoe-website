<script>
  export let name;
  export let rank;
  export let image;
</script>

<style>
  .contributor {
    background: rgba(30, 30, 30) !important;
    padding: 2em;
    height: 12em;
    border-radius: 3px;
    display: inline-block;
  }
  .contributor > img {
    display: block;
    height: auto;
    max-width: 100%;
    max-height: 100%;
  }
</style>

<div class="container p-4">
  <div class="contributor text-center">
    <img src={image} alt="{name}_{rank}" />
    {name}
    <br />
    {rank}
  </div>
</div>
