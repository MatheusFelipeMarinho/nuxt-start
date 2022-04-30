<template>
  <nav class="relative px-2 py-3 bg-pink-500 mb-3">

  </nav>
</template>

<script>
export default {
  name: "pink-navbar",
  data() {
    return {
      showMenu: false
    }
  },
  methods: {
    toggleNavbar: function(){
      this.showMenu = !this.showMenu;
    }
  }
}
</script>