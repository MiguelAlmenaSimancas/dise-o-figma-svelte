<script>
    import { navigate } from 'svelte-navigator';
  </script>
  
  <header class="header">
    <img src="../images/balon.png" alt="Logo" class="logo" />
        <h1>Limited Football</h1>
    <div class="botones-iconos">
      <button on:click={() => navigate('/carrito')} class="button">🛒</button>
      <button on:click={() => navigate('/user')} class="button">👤</button>
    </div>
  </header>
  
