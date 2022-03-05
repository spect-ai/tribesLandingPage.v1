<template>
  <div class="actionContainer">
    <a class="waitlistButton" href="aaa">Sign up for waitlist</a>
    <a class="communityButton" href="aaa">Join Community</a>
  </div>
</template>

<script lang="ts">
export default {
  name: "Actions",
};
</script>

<style>
.actionContainer {
  display: flex;
  flex-direction: row;
  margin: 2rem 0 2rem 5rem;
}

.waitlistButton {
  background-color: #eaeaea;
  color: #00194a;
  border: 1px solid #eaeaea;
  border-radius: 2px;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 0.3em;
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 1rem 1rem;
  margin-right: 1rem;
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
  font-size: 0.3em;
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 1rem 1rem;
  transition: all 0.5s ease-in-out;
}

.communityButton:hover {
  background-color: #eaeaea;
  color: #00194a;
}
</style>
