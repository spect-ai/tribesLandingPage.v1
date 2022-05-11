<template>
  <div class="grid grid-cols-1 pb-8">
    <div class="flex flex-col justify-center items-center mt-8 mx-4 lg:mx-96">
      <div class="videoContainer">
        <iframe
          src="https://www.youtube.com/embed/xosyFKSJvjQ"
          allowfullscreen
          class="responsive-iframe"
        />
      </div>
    </div>
    <Actions />
    <div
      class="grid grid-cols-1 lg:grid-cols-2 flex flex-col justify-center items-center mt:8 lg:mt-16 mx-4 md:mx-0"
    >
      <div class="graphicsContainer md:mx-0">
        <img
          class="object-contain h-full w-full m-8 pl-16"
          src="/src/assets/board1.png"
        />
      </div>
      <div class="flex flex-row justify-center items-center">
        <div class="lg:flex flex flex-col">
          <div class="text-[1.5em] lg:text-[2em]">Manage Projects</div>
          <div class="text-[0.8em] lg:text-[1em] w-72 lg:w-96 mt-4">
            Manage your projects and bounties all in one place to increase
            visibility among your DAO contributors.
          </div>
        </div>
      </div>
    </div>
    <div
      class="grid grid-cols-1 lg:grid-cols-2 flex flex-col justify-center items-center mx-4 md:mx-0 mt:8"
    >
      <div class="hidden lg:flex flex flex-row justify-center items-center">
        <div class="lg:flex flex flex-col">
          <div class="text-[1.5em] lg:text-[2em]">Fund Contributors</div>
          <div class="text-[0.5em] lg:text-[1em] w-96 mt-4">
            Reward contributors on bounty completion and tip each other
            retroactively to incentivize great work!
          </div>
        </div>
      </div>
      <div class="graphicsContainer">
        <img
          class="object-contain m-8 pr-24 pt-16"
          src="/src/assets/epoch1.png"
        />
      </div>
    </div>
    <div class="lg:hidden flex flex-row justify-center items-center">
      <div class="lg:flex flex flex-col">
        <div class="text-[1.5em] lg:text-[2em]">Fund Contributors</div>
        <div class="text-[0.8em] lg:text-[1em] w-72 mt-4">
          Reward contributors on bounty completion and tip each other
          retroactively to incentivize great work!
        </div>
      </div>
    </div>
    <div
      class="grid grid-cols-1 lg:grid-cols-2 flex flex-col justify-center items-center mx-4 md:mx-0"
    >
      <div class="graphicsContainer">
        <img src="/src/assets/coins1.png" />
      </div>
      <div class="flex flex-row justify-center items-center">
        <div class="lg:flex flex flex-col">
          <div class="text-[1.5em] lg:text-[2em]">Use your Favorite Tokens</div>
          <div class="text-[0.8em] lg:text-[1em] w-72 lg:w-96 mt-4">
            Payout your contributors on any EVM chain with any token. You can
            even plug in your native DAO token!
          </div>
        </div>
      </div>
      <div class="flex flex-row justify-center items-center">
        <div class="lg:flex flex flex-col">
          <div class="text-[1.5em] lg:text-[2em]"></div>
          <div class="text-[1.0em] lg:text-[1em] w-72 lg:w-96 mt-4"></div>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <div class="flex flex-row justify-center items-center mt-8">
      <div class="mb-8 mr-8">Reach out to us:</div>
      <a
        class="communityButton p-2 lg:p-4 text-[0.5em] lg:text-sm mb-8 mr-2"
        href="https://discord.gg/sbPnAdKA6c"
        target="_blank"
        ><i class="fa-brands fa-discord"></i
      ></a>
      <a
        class="communityButton p-2 lg:p-4 text-[0.5em] lg:text-sm mb-8"
        href="https://twitter.com/joinspect"
        target="_blank"
        ><i class="fa-brands fa-twitter"></i
      ></a>
    </div>
  </footer>
</template>

<script lang="ts">
import Actions from "./Actions.vue";
export default {
  name: "Graphics",
  components: { Actions },
};
</script>

<style>
.graphicsContainer {
  position: relative;
  overflow: hidden;
  width: 100%;
  height: 24rem;
}
.mobileGraphicsContainer {
  position: relative;
  overflow: hidden;
  width: 80%;
  height: 24rem;
}
.videoContainer {
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%;
}
.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
  background-color: transparent;
}
</style>
