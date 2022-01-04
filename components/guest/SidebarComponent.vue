<template>
  <div class="w-full py-4">
    <div class="w-full py-4 px-8 mb-4 text-white bg-gradient-to-r from-orange-500 via-orange-400 to-orange-500 relative rounded">
      <h3 class="font-semibold">Kategoriler</h3>
      <lazy-icons-category-icon class="absolute w-14 h-14 top-0 right-2 fill-current z-0 opacity-10" />
    </div>
    <nav class="font-semibold">
      <ul>
        <li class="mb-1">
          <a href="" class="block py-4 px-8 rounded relative overflow-hidden group">
            <span class="relative z-10">Teknoloji</span>
            <figure class="absolute left-0 top-0 overflow-hidden z-0 grayscale opacity-10 transition-all hover:grayscale-0 hover:opacity-30">
              <img class="w-full object-cover" src="https://images.pexels.com/photos/1432675/pexels-photo-1432675.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" width="100%" height="100%" alt="">
            </figure>
          </a>
        </li>
        <li class="mb-1">
          <a href="" class="block py-4 px-8 rounded relative overflow-hidden group">
            <span class="relative z-10">Eğitim</span>
            <figure class="absolute left-0 top-0 overflow-hidden z-0 grayscale opacity-10 transition-all hover:grayscale-0 hover:opacity-30">
              <img class="w-full object-cover" src="https://images.pexels.com/photos/147413/twitter-facebook-together-exchange-of-information-147413.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" width="100%" height="100%" alt="">
            </figure>
          </a>
        </li>
        <li class="mb-1">
          <a href="" class="block py-4 px-8 rounded relative overflow-hidden group">
            <span class="relative z-10">Sağlık</span>
            <figure class="absolute left-0 top-0 overflow-hidden z-0 grayscale opacity-10 transition-all hover:grayscale-0 hover:opacity-30">
              <img class="w-full object-cover" src="https://images.pexels.com/photos/3692887/pexels-photo-3692887.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" width="100%" height="100%" alt="">
            </figure>
          </a>
        </li>
        <li class="mb-1">
          <a href="" class="block py-4 px-8 rounded relative overflow-hidden group">
            <span class="relative z-10">Gündem</span>
            <figure class="absolute left-0 top-0 overflow-hidden z-0 grayscale opacity-10 transition-all hover:grayscale-0 hover:opacity-30">
              <img class="w-full object-cover" src="https://images.pexels.com/photos/1036936/pexels-photo-1036936.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" width="100%" height="100%" alt="">
            </figure>
          </a>
        </li>
      </ul>
    </nav>
    <div class="w-full py-4 px-8 mt-4 mb-4 text-white bg-gradient-to-r from-orange-500 via-orange-400 to-orange-500 relative rounded">
      <h3 class="font-semibold">En Son Yorumlar</h3>
      <lazy-icons-comment-icon class="absolute w-14 h-14 top-0 right-2 fill-current z-0 opacity-10" />
    </div>
    <div>
      <div class="flex gap-4 mb-4">
        <div class="flex items-center gap-4">
          <div class="w-14">
            <figure class="w-14 h-14 overflow-hidden rounded-full">
              <img class="w-full h-full object-cover" width="100%" height="100%" src="https://images.pexels.com/photos/7983603/pexels-photo-7983603.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="">
            </figure>
          </div>
          <div class="text-sm">
            <strong class="font-semibold">John Doe</strong>
            <p class="text-xs text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima quasi, voluptates.</p>
          </div>
        </div>
      </div>
      <div class="flex gap-4 mb-4">
        <div class="flex items-center gap-4">
          <div class="w-14">
            <figure class="w-14 h-14 overflow-hidden rounded-full">
              <img class="w-full h-full object-cover" width="100%" height="100%" src="https://images.pexels.com/photos/9064774/pexels-photo-9064774.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="">
            </figure>
          </div>
          <div class="text-sm">
            <strong class="font-semibold">John Doe</strong>
            <p class="text-xs text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima quasi, voluptates.</p>
          </div>
        </div>
      </div>
      <div class="flex gap-4 mb-4">
        <div class="flex items-center gap-4">
          <div class="w-14">
            <figure class="w-14 h-14 overflow-hidden rounded-full">
              <img class="w-full h-full object-cover" width="100%" height="100%" src="https://images.pexels.com/photos/3763188/pexels-photo-3763188.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="">
            </figure>
          </div>
          <div class="text-sm">
            <strong class="font-semibold">John Doe</strong>
            <p class="text-xs text-sm text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima quasi, voluptates.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="w-full py-4 px-8 mt-4 mb-4 text-white bg-gradient-to-r from-orange-500 via-orange-400 to-orange-500 relative rounded">
      <h3 class="font-semibold">Editörün Seçtiği</h3>
      <lazy-icons-cup-icon class="absolute w-14 h-14 top-0 right-2 fill-current z-0 opacity-10" />
    </div>
    <div>
      <div>
        <a href="">
          <figure class="">
            <img class="w-full h-40 object-cover rounded mb-4" src="https://images.pexels.com/photos/147413/twitter-facebook-together-exchange-of-information-147413.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" width="100%" height="100%" alt="">
            <figcaption>
              <h2 class="font-semibold text-lg mb-2 transition hover:text-purple-800">Security Isn’t Just a Technology Problem</h2>
              <p class="text-sm text-gray-500">“Herobrine” is an urban legend associated with Minecraft, who first appeared as a single image on 4chan’s /v/ board. According to rumors, Herobrine appears in players’ worlds and builds strange constructions.</p>
            </figcaption>
          </figure>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SidebarComponent"
}
</script>
