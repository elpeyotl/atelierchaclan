<template>
  <div class="w-screen h-screen flex justify-center items-center">
    <div class="flex h-52">
      <div>
        <img src="/img/logo.jpg" class="h-52" alt="Atelier Chaclan" />
      </div>
      <div class="ml-8 uppercase flex flex-col">
        <div class="address">
          Jonathan Chaclàn<br />
          Architekten GMBH<br />
          ETH SIA<br />
          <a href="https://goo.gl/maps/izyGiWvwkFNxs21H9" target="_blank">
            Tössfeldstrasse 25<br />
            8400 Winterthur<br />
          </a>
        </div>
        <div class="uppercase mt-auto contact">
          <a href="tel:+41788964554">+41 78 896 45 54</a><br />
          <a href="mailto:mail@chaclan.ch">mail</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Atelier Chaclàn',
  // or, instead:
  // titleTemplate: (title) => `My App - ${title}`,
  viewport: 'width=device-width, initial-scale=1, maximum-scale=1',
  charset: 'utf-8',
  meta: [{ name: 'description', content: 'My amazing site.' }],
  link: [
    {
      rel: 'stylesheet',
      type: 'text/css',
      href: '/fonts/fonts.css',
    },
  ],
})
</script>

<style>
body {
  font-family: 'acumin-pro';
  font-weight: 700;
  letter-spacing: 4px;
}
.contact {
  margin-top: 46px;
}

.address {
  margin-top: -3px;
}

a:hover {
  @apply text-teal-500;
}
</style>
