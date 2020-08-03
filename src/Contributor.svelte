<script>
  export let name;
  export let rank;
  export let rankcolor;
</script>

<style>
  .contributor {
    background: rgba(30, 30, 30) !important;
    padding: 2em;
    height: 13.5em;
    border-radius: 3px;
  }

  .contributor > picture > img {
    display: block;
    height: auto;
    max-width: 100%;
    max-height: 100%;
  }
  .rankcolor {
    opacity: 0.9;
    padding: 2px;
    padding-right: 10px;
    padding-left: 10px;
    font-size: 15px;
    border-radius: 3px;
  }
  .rank-tecadmin {
    background: #d4850f;
  }
  .rank-admin {
    background: #801313;
  }
  .rank-dev {
    background: #b51414;
  }
  .rank-hbuild {
    background: #135b9e;
  }
  .rank-build {
    background: #176ebf;
  }
  .rank-mod {
    background: #0f920f;
  }
  .rankcolor:hover {
    opacity: 1;
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
      <span class={rankcolor}>{rank}</span>
    </div>
  </div>
</div>
