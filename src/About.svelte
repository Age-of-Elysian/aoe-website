<script>
  import Contributor from "./Contributor.svelte";
</script>

<div class="container text-light">
  <div class="text-center align-middle">
    <h2 class="m-4">Department Heads</h2>
  </div>

  <div class="row justify-content-center">
    <div>
      <Contributor
        image="/images/contributors/png/qalle.png"
        name="Qalle"
        rank="Tec-Admin" />
    </div>
    <div>
      <Contributor
        image="/images/contributors/png/hunk.png"
        name="HunkyHenry"
        rank="Head-Builder" />
    </div>
    <div>
      <Contributor
        image="/images/contributors/png/gonzo.png"
        name="DrGonzo"
        rank="Head-Admin" />
    </div>
  </div>

  <div class="text-center align-middle">
    <h3 class="m-4">Developers</h3>
  </div>
  <div class="row justify-content-center">
    <div>
      <Contributor
        image="/images/contributors/webp/dp.webp"
        name="DeathlyPandas"
        rank="ExtraGear Dev" />
    </div>
    <div>
      <Contributor
        image="/images/contributors/webp/alex.webp"
        name="AlexLander123"
        rank="Plugin Dev" />
    </div>
  </div>

  <div class="text-center align-middle">
    <h2 class="m-4">Administrators</h2>
  </div>

  <div class="row justify-content-center">
    <div>
      <Contributor
        image="/images/contributors/webp/NoPower.webp"
        name="NoPower"
        rank="Towny Admin" />
    </div>
    <div>
      <Contributor
        image="/images/contributors/webp/zach.webp"
        name="Zacharymj"
        rank="Towny Admin" />
    </div>
    <div>
      <Contributor
        image="/images/contributors/webp/steven.webp"
        name="StevenD85"
        rank="Web Admin" />
    </div>
  </div>

  <div class="text-center">
    <h3 class="m-4">Moderators</h3>
  </div>

  <div class="row justify-content-center">
    <div id="longname">
      <Contributor
        image="/images/contributors/webp/nagatake.webp"
        name="Nagatake"
        rank="Towny Mod" />
    </div>
    <div>
      <Contributor
        image="/images/contributors/webp/ajan.webp"
        name="Ajan_12"
        rank="Discord Mod" />
    </div>
  </div>

  <div class="text-center">
    <h3 class="m-4">Builders</h3>
    <div class="row justify-content-center">
      <div>
        <Contributor
          image="/images/contributors/webp/kins.webp"
          name="Kinsplai"
          rank="" />
      </div>
      <div>
        <Contributor
          image="/images/contributors/webp/alph.webp"
          name="Alphacca"
          rank="" />
      </div>
      <div>
        <Contributor
          image="/images/contributors/webp/xilos.webp"
          name="XilosYT"
          rank="" />
      </div>
      <div>
        <Contributor
          image="/images/contributors/webp/tavangar.webp"
          name="Tavangar"
          rank="" />
      </div>
    </div>

  </div>
</div>
