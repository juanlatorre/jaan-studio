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
  }

  h2 {
    margin-top: 0em;
  }

  hr {
    width: 30vw;
    height: 30px;
    border-style: solid;
    border-color: #f8efba;
    border-width: 1px 0 0 0;
  }
  /* hr:before {
    display: block;
    content: "";
    height: 30px;
    margin-top: -31px;
    border-style: solid;
    border-color: #f8efba;
    border-width: 0 0 1px 0;
    border-radius: 20px;
  } */

  img {
    animation: spin 150s infinite linear;
    width: 40em;
    margin-top: -20em;
  }

  @keyframes spin {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }
</style>

<div id="hero">
  <img src="img/mandala.svg" alt="Mandala" draggable="false" />

  <h1 class="studioName is-size-1">Jaal Studio</h1>
  <hr />
  <!-- <h2>
    Destaca tu negocio con un sitio web profesional, tienda online, aplicación
    móvil o portafolio.
  </h2> -->
</div>
