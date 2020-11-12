<template>
  <div>
    <vs-navbar type="gradient" v-model="navActiveItem" class="nabarx mt-2">
      <div slot="title">
        <vs-navbar-title>
          Checklist
        </vs-navbar-title>
      </div>
      <vs-navbar-item index="0">
        <a href="#">Home</a>
      </vs-navbar-item>
      <vs-navbar-item index="1">
        <a href="#">News</a>
      </vs-navbar-item>
      <vs-navbar-item index="2">
        <a href="#">Update</a>
      </vs-navbar-item>
    </vs-navbar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      navActiveItem: "0",
    }
  },
}
</script>