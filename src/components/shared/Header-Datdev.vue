<template lang="">
  <div class="container mx-auto">
    <div
      class="z-10 block max-w-screen-lg my-0 xl:max-w-screen-xl sm:flex sm:justify-between sm:items-center"
    >
      <div class="flex items-center justify-between">
        <div>
          <router-link :to="{ name: 'Home' }" class="flex items-center justify-between">
            <img src="@/assets/logo.svg" class="w-14" alt="logo" />
            <span class="nav__item__logo__text">TienDatPhong</span>
          </router-link>
        </div>
      </div>
    </div>
    <div class="items-center justify-center mt-2 ml-3 sm:ml-4 sm:mt-3 sm:flex">
      <router-link :to="{ name: 'ProjectsMe' }" class="nav__item"> Project </router-link>
      <router-link :to="{ name: 'AboutMe' }" class="nav__item"> About me </router-link>
      <router-link :to="{ name: 'ContactMe' }" class="nav__item"> Contact </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header-Datdev'
}
</script>
<style lang=""></style>
