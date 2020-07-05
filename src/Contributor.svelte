<script>
  export let name;
  export let rank;
  export let image;
</script>

<div>
  <img src={image} alt="{name}_{rank}" />
  {name}
</div>
