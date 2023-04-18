<script>
  import { userInputStore } from "../stores";

  let eraseText = () => {
    userInputStore.set([]);
  }

</script>

<img src="/src/assets/erase.svg" alt="Erase text" class="erase-button" on:mousedown={eraseText}>

<style>
  .erase-button {
    width: 40px;
    position: relative;
    bottom: 35px;
    left: 150px;
  }
</style>
