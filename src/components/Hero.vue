<template>
  <div class="text-white">
    <div
      class="text-[1em] sm:text-[2em] md:text-[2.5em] lg:text-[3em] flex lg:ml-16 ml-12"
    >
      <div>Organize the&nbsp;</div>
      <div class="tribe">&nbsp;Chaos&nbsp;</div>
      <div>&nbsp;In your DAO&nbsp;</div>
    </div>
    <Graphics />
    <Actions />
  </div>
</template>

<script lang="ts">
import Actions from "./Actions.vue";
import Graphics from "./Graphics.vue";
export default {
  name: "Hero",
  components: { Actions, Graphics },
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
