
<main>
  <section id="container">
    <slot></slot>
  </section>
</main>

<style>
  main{
    width: 100vw;
    height: 100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    
  }
  #container{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0 !important;
    padding: 0 !important;
    width:100%;
    height: 100%;
    color: #fff;
    z-index: 999999;
    
  }
</style>