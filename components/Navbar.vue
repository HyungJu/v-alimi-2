<template>
  <nav
    class="flex flex-row items-center justify-between bg-alimiblack py-5 px-10 border-b-2 border-gray-800"
  >
    <div class="flex text-white">
      <p class="text-lg" style="font-family: GmarketSansBold, sans-serif">
        E알리미
      </p>
    </div>
    <div
      class="flex flex-row text-white"
      style="font-family: GmarketSansMedium, sans-serif"
    >
      <div class="ml-4 text-gray-600">받은 알리미</div>
      <div class="ml-4">학급 알리미</div>
      <div class="ml-4 text-gray-600">도움말</div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style>
@font-face {
  font-family: 'GmarketSansBold';
  src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansBold.woff')
    format('woff');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'GmarketSansMedium';
  src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansMedium.woff')
    format('woff');
  font-weight: normal;
  font-style: normal;
}
</style>
