<script>
  import Card from "./lib/card.svelte";
  import mrrigby from "./assets/mr-rigby.png"
  import GSAD from "./assets/GSAD.jpg"
  import GuiGui from "./assets/GuiGui.png"
  import Tim from "./assets/tim.png"
  import Twnt from "./assets/twnt.png"
  import bwbl from "./assets/bwlb.png"      
</script>

<main>
  <div class="container">
    <div class="row">
      <div class="col">
        <Card username="GUIGUI" text="SIUUUU" file="{GuiGui}" url="https://discord.com/users/693054570628251770" />
      </div>
      <div class="col">
        <Card username="bwbl" text="dd if=/dev/null of=/bwbl" file="{bwbl}" url="https://discord.com/users/1051578679593009212" />
      </div>
      <div class="col">
        <Card username="GSAD_06" text="spaghetti" file="{GSAD}" url="https://discord.com/users/691925214426300436" />
      </div>
      <div class="w-100"> </div> 
      <div class="col">
        <Card username="Mr_Rigby" text="Lebron" file="{mrrigby}" url="https://discord.com/users/692308737356201985" />
      </div>
      <div class="col">
        <Card username="ClenchedFlame35" text="raptortim" file="{Tim}" url="https://discord.com/users/691946521725501531" />
      </div>
      <div class="col">
        <Card username="severed_limbs" text="twntacles" file="{Twnt}" url="https://discord.com/users/737298633019490335" />
      </div>
    </div>
  </div>
</main>

<style>
</style>