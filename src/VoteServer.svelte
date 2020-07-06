<script>
  export let link;
  export let imagepng;
  export let imagewebp;
</script>

<style>
  .vote-server {
    background: rgba(0, 0, 0, 0.2) !important;
    padding: 2em;
    height: 12em;
    border-radius: 3px;
    width: 100%;

    display: table;
  }

  .vote-server > a {
    vertical-align: middle;
    display: table-cell;
  }

  .vote-server > a > img {
    display: block;
    height: auto;

    max-width: 100%;
    max-height: 100%;

    transition: 0.25s;
    filter: grayscale(100%);
  }

  .vote-server > a > img:hover {
    transition: 0.25s;
    filter: none;
  }
</style>

<div class="col-12 col-sm-6 col-md-4 col-lg-3 p-2">
  <div class="vote-server">
    <a href={link} target="_blank">
      <picture>
        <source srcset={imagewebp} type="image/webp" />
        <img class="mx-auto" src={imagepng} alt="Vote Server" />
      </picture>
    </a>

  </div>
</div>
