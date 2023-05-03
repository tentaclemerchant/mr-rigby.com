<script>
  import Card from "./lib/card.svelte";
  import mrrigby from "./assets/mr-rigby.png"
  import GSAD from "./assets/GSAD.jpg"
  import GuiGui from "./assets/GuiGui.png"
  import Tim from "./assets/tim.png"
  import Twnt from "./assets/twnt.png"
  import bwbl from "./assets/bwlb.png"   
  import rigby from "./assets/images.jpg"
</script>

<main>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">

    <div class="container-fluid">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          
         
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Sections
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Top</a></li>
              <li><a class="dropdown-item" href="#">Members</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Downloads</a></li>
            </ul>
          </li>
          
        </ul>
        
      </div>
    </div>
  </nav>
  <div class=caca>

    <img src="{rigby}" alt="rigby" class="rigber">
  </div>
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
  <div class="btn-group">
    <button class="btn btn-success btn-lg dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
      Des World download
    </button>
    <ul class="dropdown-menu">
      <li><a class="dropdown-item" href="https://drive.google.com/file/d/1vQKKltfZccYKUPOs7m31Qd21hu1YmhiH/view?usp=share_link">1.16</a></li>
      <li><a class="dropdown-item" href="https://drive.google.com/file/d/1ZMrvgk0iTfqfLaRhTmQIyDoUBh4mcyTA/view?usp=share_link">1.17</a></li>
      <li><a class="dropdown-item" href="https://drive.google.com/file/d/15s6ruE9fFmfBfjmrurVK3BswEO_GWj-1/view?usp=share_link">euh jsp</a></li>
  
    </ul>
  </div> 
</main>


<style>
  .rigber{
    height: auto;
    width: 30%;
  }
  .caca {
    width: 100%;
    display: flex;
    justify-content: center;
}


</style>