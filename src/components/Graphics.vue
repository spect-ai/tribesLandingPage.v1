<template>
  <div class="grid sm:grid-cols-1 xl:grid-cols-5">
    <div class="col-span-3">
      <div class="grid md:grid-cols-7 sm:grid-cols-1">
        <div class="md:col-span-2 flex flex-col justify-center items-center">
          <div class="graphicsContainer">
            <iframe
              src="https://my.spline.design/tasks-a6ad2faee70628e9036030d14d9d1d64/"
              frameborder="0"
              width="100%"
              height="100%"
              class="responsive-iframe"
            />
          </div>
          <div class="text-xl">Manage tasks</div>
        </div>
        <div class="md:col-span-3 flex flex-col justify-center items-center">
          <div class="graphicsContainer">
            <iframe
              allowtransparency="true"
              src="https://my.spline.design/epoch2-f586b2682c76a4b5cd4a48c3a5abe3f5/"
              frameborder="0"
              width="100%"
              height="100%"
              class="responsive-iframe"
            />
          </div>
          <div class="text-xl">Value Contributions</div>
        </div>
        <div class="md:col-span-2 flex flex-col justify-center items-center">
          <div class="graphicsContainer">
            <iframe
              src="https://my.spline.design/coins2-15a02bbe78d293f166ec18b74a085dca/"
              frameborder="0"
              width="100%"
              height="100%"
              class="responsive-iframe"
            />
          </div>
          <div class="text-xl">Pay in crypto</div>
        </div>
      </div>
    </div>
    <div
      class="col-span-2 flex flex-col justify-center items-center mt-16 sm:mt-8 xl:mt-4 ml-[5.5rem] md:mx-32 lg:mx-16 lg:mx-0"
    >
      <div class="videoContainer">
        <iframe
          src="https://www.youtube.com/embed/IOfvhV31Hos"
          allowfullscreen
          class="responsive-iframe"
        />
      </div>
      <div class="text-xl pt-4">See it to believe it</div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Graphics",
};
</script>

<style>
/* .graphicsContainer {
  height: 24rem;
  background-color: transparent;
} */
.graphicsContainer {
  position: relative;
  overflow: hidden;
  width: 100%;
  height: 24rem;
}

.videoContainer {
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%;
}
/* Then style the iframe to fit in the container div with full height and width */
.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
  padding-right: 1rem;
  background-color: transparent;
}
</style>
