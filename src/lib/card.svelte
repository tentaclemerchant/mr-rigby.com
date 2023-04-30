<script>
    export let username
    export let text
    export let file
    export let url
</script>

<div class="card container-md" style="width: 18rem;">
    <img src="{file}" class="card-img-top ratio ratio-16x9" alt="...">
    <div class="card-body">
      <h5 class="card-title">{username}</h5>
      <p class="card-text">{text}</p>
      {#if url}
      <a href="{url}" class="btn btn-primary">add on discord</a>
      {/if}
    </div>
  </div>

<style>
    .button{ 
        color:aqua;
    }
</style>