<template>
  <header>
    <div class="login">
      <icon-base width="12" height="12" icon-name="lock"
        ><icon-lock />
      </icon-base>
      Login
    </div>
    <div>
      <nav>
        <ul>
          <li><a href="#">HOME</a></li>
          <li><a href="#">ABOUT</a></li>
          <li><a href="#">Logo</a></li>
          <li><a href="#">JEWELS</a></li>
          <li><a href="#">CONTACT</a></li>
        </ul>
      </nav>
    </div>
    <div class="search">
      Search
    </div>
  </header>
</template>

<script>
import IconBase from "./IconBase";
import IconLock from "./icons/IconLock";
export default {
  name: "Header",
  components: {
    IconBase,
    IconLock
  }
};
</script>

<style scoped>
header {
  height: 100px;
  background-color: cadetblue;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 10%;
}
</style>
