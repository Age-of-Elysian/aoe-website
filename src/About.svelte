<script>
  import Contributor from "./Contributor.svelte";
</script>

<style>
@font-face{
  font-family: Quartz;
  src: url('/fonts/Backshlash.ttf');
}
  h2 {
    font-family: Quartz;
  }
</style>

<div class="container text-light">
  <div class="text-center align-middle">
    <h2 class="m-4 text-center font-weight-bold">Department Heads</h2>
  </div>

  <div class="row justify-content-center">
    <Contributor
      imagepng="/images/contributors/png/qalle.png"
      imagewebp="/images/contributors/webp/qalle.webp"
      name="Qalle"
      rank="Tec-Admin"
      rankcolor="rankcolor rank-tecadmin" />
    <Contributor
      imagepng="/images/contributors/png/hunk.png"
      imagewebp="/images/contributors/webp/hunk.webp"
      name="HunkyHenry"
      rank="Head-Builder"
      rankcolor="rankcolor rank-hbuild" />
    <Contributor
      imagepng="/images/contributors/png/gonzo.png"
      imagewebp="/images/contributors/webp/gonzo.webp"
      name="DrGonzo"
      rank="Head-Admin"
      rankcolor="rankcolor rank-dev" />
  </div>

  <div class="text-center align-middle">
    <h2 class="m-4 text-center font-weight-bold">Developers</h2>
  </div>
  <div class="row justify-content-center">
    <Contributor
      imagepng="/images/contributors/png/dp.png"
      imagewebp="/images/contributors/webp/dp.webp"
      name="DeathlyPandas"
      rank="ExtraGear Dev"
      rankcolor="rankcolor rank-dev" />
    <Contributor
      imagepng="/images/contributors/png/alex.png"
      imagewebp="/images/contributors/webp/alex.webp"
      name="AlexLander123"
      rank="Plugin Dev"
      rankcolor="rankcolor rank-dev" />
    <Contributor
      imagepng="/images/contributors/png/linox.png"
      imagewebp="/images/contributors/webp/linox.webp"
      name="Linox"
      rank="Slimefun Dev"
      rankcolor="rankcolor rank-dev" />
  </div>

  <div class="text-center">
    <h2 class="m-4 text-center font-weight-bold">Administrators</h2>
  </div>

  <div class="row justify-content-center">
    <Contributor
      imagepng="/images/contributors/png/nopower.png"
      imagewebp="/images/contributors/webp/nopower.webp"
      name="NoPower"
      rank="Towny Admin"
      rankcolor="rankcolor rank-admin" />
    <Contributor
      imagepng="/images/contributors/png/zach.png"
      imagewebp="/images/contributors/webp/zach.webp"
      name="Zacharymj"
      rank="Towny Admin"
      rankcolor="rankcolor rank-admin" />
    <Contributor
      imagepng="/images/contributors/png/steven.png"
      imagewebp="/images/contributors/webp/steven.webp"
      name="StevenD85"
      rank="Web Admin"
      rankcolor="rankcolor rank-admin" />
    <Contributor
      imagepng="/images/contributors/png/nard.png"
      imagewebp="/images/contributors/webp/nard.webp"
      name="NardGD"
      rank="Towny Admin"
      rankcolor="rankcolor rank-admin" />
  </div>

  <div class="text-center">
    <h2 class="m-4 text-center font-weight-bold">Moderators</h2>
  </div>

  <div class="row justify-content-center">
    <Contributor
      imagepng="/images/contributors/png/nagatake.png"
      imagewebp="/images/contributors/webp/nagatake.webp"
      name="Nagatake"
      rank="Towny Mod"
      rankcolor="rankcolor rank-mod" />
    <Contributor
      imagepng="/images/contributors/png/linox.png"
      imagewebp="/images/contributors/webp/linox.webp"
      name="Linox"
      rank="Discord Mod"
      rankcolor="rankcolor rank-mod" />
  </div>

  <div class="text-center">
    <h2 class="m-4 text-center font-weight-bold">Builders</h2>
  </div>

  <div class="row justify-content-center">
    <Contributor
      imagepng="/images/contributors/png/alph.png"
      imagewebp="/images/contributors/webp/alph.webp"
      name="Alphacca"
      rank="Builder"
      rankcolor="rankcolor rank-build" />
    <Contributor
      imagepng="/images/contributors/png/xilos.png"
      imagewebp="/images/contributors/webp/xilos.webp"
      name="XilosYT"
      rank="Builder"
      rankcolor="rankcolor rank-build" />
    <Contributor
      imagepng="/images/contributors/png/tavangar.png"
      imagewebp="/images/contributors/webp/tavangar.webp"
      name="Tavangar"
      rank="Builder"
      rankcolor="rankcolor rank-build" />
  </div>
</div>
