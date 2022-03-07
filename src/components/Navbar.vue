<template>
  <div class="navbar">
    <div class="navbarContainer">
      <img
        src="https://ipfs.moralis.io:2053/ipfs/QmRnbkmvYthsi6bXpZ5j14yZyfuxgVD3SaokXNRrBRsyQw"
        alt="logo"
        class="logo"
      />
      <div class="name">spect tribes</div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Navbar",
};
</script>

<style>
.navbar {
  color: #eaeaea;
}

.name {
  font-size: 1.2em;
  font-weight: 500;
  letter-spacing: 1px;
}

.navbarContainer {
  padding: 1rem 4rem;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.logo {
  width: auto;
  height: 2.5rem;
  margin-right: 1rem;
}
</style>
