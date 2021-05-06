<template>
     <div class="container">
          <img class="logo" src="../../icons/logo.svg" alt="" />
          <img class="logo_title" src="../../icons/logo_title.svg" alt="" />
     </div>
</template>

<script>
export default {
     name: 'Navbar',
     props: {
          logged_in: Boolean,
          default: false,
     },
}
</script>

<style scoped>
.container {
     background-color: #6eb4ac80;
}

.logo {
     width: 50px;
     display: inline-block;
}

.logo_title {
     padding-left: 15px;
     padding-bottom: 1%;
     width: 170px;
     display: inline-block;
     padding-bottom: 15px;
}
</style>
