<template lang="">
  <div>
    <section class="flex flex-col items-center max-w max-h mt-15">
      <video autoplay loop muted class="w-full h-full object-cover absolute z-0">
        <source src="@/assets/huy-ngu.mp4" type="video/mp4" />
      </video>
      <div class="text-white text-2xl font-bold absolute inset-0 flex items-center justify-center">
        <div class="w-full text-left ml-20 sm:w-1/3">
          <h1
            class="text-3xl font-semibold text-center sm:text-5xl sm:text-left text-ternary-dark dark:text-primary-light"
          >
            Hi, My name TienDat
          </h1>
          <p
            class="mt-4 font-semibold leading-none text-center text-gray-400 text-2xml sm:text-4xl sm:text-left"
          >
            Professor, Ph.D. Software Development & Technology Trainer.
          </p>
          <div class="flex justify-center sm:block mg">
            <a
              href="http://joseluisgs.github.io"
              target="_blank"
              class="flex justify-center items-center w-36 sm:w-48 mt-12 mb-6 sm:mb-0 text-lg border border-indigo-200 dark:border-ternary-dark py-2.5 sm:py-3 shadow-lg rounded-xl bg-indigo-50 hover:bg-indigo-500 text-gray-500 hover:text-white"
            >
              <Icon icon="feather:arrow-down-circle" class="w-5 ml-0 mr-2 sm:ml-1 sm:mr-3 sm:w-6" />
              <span class="text-sm sm:text-lg">Download CV</span></a
            >
          </div>
        </div>
        <div class="float-right w-2/3 md:w-1/2 lg:w-1/3 mt-1 ml-1 text-right sm:w-2/3 sm:mt-0">
          <img src="@/assets/developer.svg" alt="Developer" />
        </div>
      </div>
    </section>
  </div>
</template>
<script lang="ts">
import { Icon } from '@iconify/vue'

export default {
  name: 'homeDat',

  components: {
    Icon
  }
}
</script>
<style lang=""></style>
