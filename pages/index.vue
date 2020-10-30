<!-- HEALTH:HIGH __page__home -->
<template>
  <div
    class="__page__home min-h-screen flex items-center container p-5 mx-auto"
  >
    <section
      class="md:flex md:items-stretch rounded-lg overflow-hidden shadow-2xl bg-white"
    >
      <div class="flex-1">
        <ix-img
          src="/photo-1541427468627-a89a96e5ca1d"
          sizes="(min-width: 1152px) 620px, (min-width: 922px) 420px, (min-width: 692px) 364px, (min-width: 600px) 600px, 100vw"
          alt="A cool train"
          class="object-cover h-full w-full flex-1"
        />
      </div>
      <article class="flex-1">
        <div class="p-8 flex flex-col h-full justify-between space-y-8">
          <div class="space-y-8">
            <h1
              class="font-bold text-2xl md:text-4xl leading-snug text-orange-600"
            >
              Experience a Train Like Never Before
            </h1>
            <p>
              A train is <strong>a form of rail transport</strong> consisting of
              a series of connected vehicles that generally run along a railroad
              (or railway) track to transport passengers or cargo (also known as
              "freight" or "goods"). The word <em>"train"</em> comes from the
              Old French trahiner, derived from the Latin trahere meaning "to
              pull" or "to draw".
            </p>
          </div>
          <div class="text-center md:text-right">
            <a
              href="https://github.com/daletom/nuxt-demo-basic"
              class="bg-orange-600 hover:bg-orange-700 transition-colors duration-300 ease-in-out text-white block md:inline-block px-8 py-4 font-bold rounded-lg"
              target="_blank"
              rel="noopener"
            >
              Get Back on Track
            </a>
          </div>
        </div>
      </article>
    </section>
  </div>
</template>

<script>
import VueImgix from "~/plugins/vue-imgix.js";

export default {};
</script>

<style></style>
