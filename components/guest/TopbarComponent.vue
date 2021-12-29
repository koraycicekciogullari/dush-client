<template>
  <div class="bg-gradient-to-r from-purple-900 via-purple-700 to-purple-900 p-4">
    <div class="container mx-auto">
      <div class="flex justify-between justify-items-center text-white">
        <div class="flex gap-2 items-center text-xs font-semibold">
          <strong class="bg-orange-400 px-4 py-2 rounded">Trending</strong>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A adipisci, aliquam aut consectetur</p>
        </div>
        <div class="flex gap-2 items-center text-xs font-semibold">
          <a href="" class="bg-purple-700 px-4 py-2 rounded transition hover:bg-purple-600">Oturum Aç</a>
          <a href="" class="bg-purple-700 px-4 py-2 rounded transition hover:bg-purple-600">Kayıt Ol</a>
          <div class="flex gap-4 items-center pl-2 text-purple-400">
            <a href="">
              <lazy-icons-facebook-icon class="w-4 h-4 fill-current transition hover:text-white"/>
            </a>
            <a href="">
              <lazy-icons-twitter-icon class="w-4 h-4 fill-current transition hover:text-white"/>
            </a>
            <a href="">
              <lazy-icons-instagram-icon class="w-4 h-4 fill-current transition hover:text-white"/>
            </a>
            <a href="">
              <lazy-icons-youtube-icon class="w-4 h-4 fill-current transition hover:text-white"/>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TopbarComponent"
}
</script>
