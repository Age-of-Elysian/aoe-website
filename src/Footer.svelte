<script>
  import Clipboard from "svelte-clipboard";

  console.log(Clipboard);
</script>

<style>
  footer {
    position: fixed;
    height: 72px;
    bottom: 0;
    width: 100%;
    text-align: center;
    padding: 24px;
    background: #1d1d1d;
    color: white;
  }
</style>

<footer>
  Join us at
  <Clipboard
    text="play.ageofelysian.com"
    let:copy
    on:copy={() => {
      console.log('Has Copied');
    }}>
    <a
      href="/#"
      on:click|preventDefault={copy}
      data-toggle="tooltip"
      data-placement="top"
      title="Copy to clipboard">
      play.ageofelysian.com
    </a>
  </Clipboard>

</footer>
