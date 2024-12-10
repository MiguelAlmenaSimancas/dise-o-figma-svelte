<script>
    import { navigate } from 'svelte-navigator'; // Usamos svelte-navigator para la navegación
  </script>
  
  <div class="background-images">
    <button on:click={() => navigate('/retro')} class="image-button">
      <img src="path_to_retro_image.jpg" alt="Retro" class="background-image" />
      <span class="title">Retro</span>
    </button>
  
    <button on:click={() => navigate('/colaboraciones')} class="image-button">
      <img src="path_to_colaboraciones_image.jpg" alt="Colaboraciones" class="background-image" />
      <span class="title">Colaboraciones</span>
    </button>
  
    <button on:click={() => navigate('/firmadas')} class="image-button">
      <img src="path_to_firmadas_image.jpg" alt="Firmadas" class="background-image" />
      <span class="title">Firmadas</span>
    </button>
  </div>
  
 
  