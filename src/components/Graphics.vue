<template>
  <div class="container-fluid mt-4">
    <div class="row">
      <div class="col-7">
        <div class="row">
          <div class="col d-flex flex-column align-items-center">
            <iframe
              src="https://my.spline.design/tasks-b89e87193da0254ceea2874fe7254e5f/"
              frameborder="0"
              width="100%"
              height="100%"
              class="graphicsContainer"
            />
            <div class="fs-5">Manage tasks</div>
          </div>
          <div class="col d-flex flex-column align-items-center">
            <iframe
              allowtransparency="true"
              src="https://my.spline.design/epoch-ba24e2c70b4613c0f48949fe37944545/"
              frameborder="0"
              width="100%"
              height="100%"
              class="graphicsContainer"
            />
            <div class="fs-5">Value Contributions</div>
          </div>
          <div class="col d-flex flex-column align-items-center">
            <iframe
              src="https://my.spline.design/coins-1492e7e9b586a0009d2276bec9c0fa73/"
              frameborder="0"
              width="100%"
              height="100%"
              class="graphicsContainer"
            />
            <div class="fs-5">Pay in crypto</div>
          </div>
        </div>
      </div>
      <div class="col-5">
        <div class="col d-flex flex-column align-items-center">
          <iframe
            width="600"
            height="380"
            src="https://www.youtube.com/embed/IOfvhV31Hos"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
            class="mb-2"
          />
          <div class="fs-5">See it to believe it</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Graphics",
};
</script>

<style>
.graphicsContainer {
  height: 24rem;
  background-color: transparent;
}
</style>
