<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <div class="flex flex-col my-10">
      <div class="flex justify-center">
        <g-image alt="Example image" src="~/assets/images/fathom-icon.png" width="135" />
      </div>

      <h1 class="text-4xl text-center">
        Fathom Static Site Boilerplate
      </h1>
      <h2 class="text-2xl italic text-purple-900 text-center">
        RTFM!
      </h2>
      <ul class="list-disc ml-20">
        <li>Gridsome (Vue)</li>
        <li>Tailwind CSS</li>
      </ul>
    </div>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
