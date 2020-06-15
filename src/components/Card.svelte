<script>
  import Comments from './Comments.svelte';
</script>

<div class="Card">
  <div class="Card-container">
    <div class="Card-header">
      <div class="Card-user">
        <img src="http://resource.intidev.info/Undraw_svg/doggy.png" alt="">
        <h2>
          Pet.name
          <span>CDMX</span>
        </h2>
      </div>
      <div class="Card-settings">
        <i class="fas fa-ellipsis-h"/>
      </div>
    </div>
    <div class="Card-photo">
      <figure>
        <img src="http://resource.intidev.info/Undraw_svg/doggy.png" alt="">
      </figure>
    </div>
    <div class="Card-icons">
      <div class="Card-icons-first">
        <i class="fas fa-heart"/>
        <i class="fas fa-paper-plane"/>
      </div>
      <div class="Card-icons-second">
        <i class="fas fa-bookmark"/>
      </div>
    </div>
    <div class="Card-description">
      <h3>Pet.name</h3>
      <span>¡Hola! :D</span>
    </div>
    <Comments/>
  </div>
</div>