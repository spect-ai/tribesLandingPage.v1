<template>
  <div class="flex flex-row justify-center items-center ml-16 mt-8 pb-8 mr-16">
    <a
      class="waitlistButton p-2 lg:p-4 mr-4 lg:mr-16 text-[0.5em] lg:text-sm"
      href="https://wnowbi36d0x.typeform.com/to/UAhbB5Xy"
      target="_blank"
      >Sign up for waitlist</a
    >
    <a
      class="communityButton p-2 lg:p-4 text-[0.5em] lg:text-sm"
      href="https://discord.gg/sbPnAdKA6c"
      target="_blank"
      >Join The Community</a
    >
  </div>
</template>

<script lang="ts">
export default {
  name: "Actions",
};
</script>

<style>
.waitlistButton {
  background-color: #eaeaea;
  color: #00194a;
  border: 1px solid #eaeaea;
  border-radius: 2px;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-decoration: none;
  display: flex;
  flex-direction: row;
  align-items: center;
  transition: all 0.5s ease-in-out;
}

.waitlistButton:hover {
  background-color: transparent;
  color: #eaeaea;
}

.communityButton {
  background-color: transparent;
  color: #eaeaea;
  border: 1px solid #eaeaea;
  border-radius: 2px;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-decoration: none;
  display: flex;
  flex-direction: row;
  align-items: center;
  transition: all 0.5s ease-in-out;
}

.communityButton:hover {
  background-color: #eaeaea;
  color: #00194a;
}
</style>
