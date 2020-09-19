<template>
  <div id="nav">
    <div id="nav-title">
      Jennifer Nguyen
    </div>
    <div id="nav-links">
      <div>Work</div>
      <div>About</div>
      <div>Contact</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#nav {
  @apply flex h-16 w-full bg-red-300;
}

#nav-title {
  @apply w-1/2;
}

#nav-links {
  @apply w-1/2 flex;
}
</style>
