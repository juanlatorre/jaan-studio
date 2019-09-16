<script>

</script>

<style>
  #hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  h1 {
    padding: 0em;
    margin-bottom: 0em;
    margin-top: -0.3em;
  }

  h2 {
    margin-top: 0em;
  }

  img {
    animation: spin 150s infinite linear;
    width: 60em;
    margin-top: -30em;
    cursor: default;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
  }

  img::selection {
    background: none;
  }

  @keyframes spin {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }

  .goDown {
    font-size: 3rem;
    text-decoration: none;
    animation: mover 1s infinite alternate;
    color: #f8efba;
  }

  .goDown:hover {
    color: #eab543;
  }

  @keyframes mover {
    0% {
      transform: translateY(0);
    }
    100% {
      transform: translateY(-10px);
    }
  }
</style>

<div id="hero">
  <img src="img/mandala.svg" alt="Mandala" draggable="false" />

  <h1 class="is-size-1">Jaal Studio</h1>
  <!-- <hr /> -->
  <h2 class="is-size-3">
    Destaca tu negocio con un sitio web profesional, tienda online, aplicación
    móvil o portafolio.
  </h2>
  <a href="#" class="goDown">⮟</a>
</div>
