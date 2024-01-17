<script>
  export let mode = false;
</script>

<footer>
  <div class="right">
    <div class="title">Jama'at musulmane Ahmadiyya</div>
    <div><img class="logo" src="./logo.png" /></div>
  </div>
</footer>

<style>
  footer {
    display: flex;
    align-items: center;
    padding: 1rem;
    color: black;
    background-color: white;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    box-sizing: border-box;
  }

  .right {
    display: flex;
    gap: 1rem;
    text-align: right;
    margin-left: auto;
  }

  .title {
    font-weight: bold;
  }

  .logo {
    width: 3rem;
    height: 3rem;
    background-color: black;
    border-radius: 100%;
  }
</style>
