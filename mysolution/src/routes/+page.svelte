<script>
  import Image from "./Image.svelte";
  import Text from "./Text.svelte";
</script>

<div class="center-hor">
  <div class="center-ver">
    <div class="qr-box">
      <Image />
      <Text />
    </div>
  </div>
</div>

<style>
  .qr-box {
    background-color: hsl(0, 0%, 100%);
    border-radius: 20px;
    display: block;
    padding: 15px;
    box-shadow: 0px 0px 19px hsl(220deg 15% 55%);
  }

  .center-hor {
    width: 100vw;
    display: flex;
    justify-content: center;
  }

  .center-ver {
    height: 100vh;
    display: flex;
    justify-content: center;
    flex-direction: column;
  }
</style>