<script>
  import Qr from "./QR.svelte";
</script>

<footer>
  <div class="left">
    <div><img class="logo" src="./logo.png" /></div>
    <div>
      <div class="title">Jama'at musulmane Ahmadiyya</div>
      <div style="text-decoration: underline; font-size: 0.8rem;">
        https://islam-ahmadiyya.org/
      </div>
    </div>
  </div>
  <div class="right">
    <Qr />
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

  .left {
    display: flex;
    gap: 1rem;
    align-items: center;
  }

  .right {
    display: flex;
    gap: 1rem;
    align-items: center;
    margin-left: auto;
    height: 4rem;
    width: 4rem;
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
