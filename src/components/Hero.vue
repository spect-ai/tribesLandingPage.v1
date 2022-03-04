<template>
  <div class="heroContainer">
    <div class="heroText">
      <div>Manage your&nbsp;</div>
      <del>DAO</del>
      <div class="tribe">&nbsp;Tribe&nbsp;</div>
      <div>with ease</div>
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
