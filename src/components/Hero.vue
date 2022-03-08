<template>
  <div class="text-white">
    <div
      class="text-[1.3em] sm:text-[2em] md:text-[2.5em] lg:text-[3em] flex flex-row justify-center items-center"
    >
      <div>Organize the chaos In your</div>
      <div class="tribe">&nbsp;DAO</div>
    </div>
    <Graphics />
  </div>
</template>

<script lang="ts">
import Graphics from "./Graphics.vue";
export default {
  name: "Hero",
  components: { Graphics },
};
</script>

<style>
.heroContainer {
  color: #eaeaea;
  font-size: 3em;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.heroText {
  font-weight: 500;
  margin-left: 4rem;
  display: flex;
}
.tribe {
  color: #99ccff;
}
</style>
