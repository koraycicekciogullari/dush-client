<template>
  <div class="w-full bg-gray-100 py-4">
    <div class="container mx-auto">
      <div class="flex justify-between justify-items-center">
        <guest-logo-component/>
        <div class="flex items-center">
          <nav>
            <ul class="flex gap-4 items-center text-gray-700 font-semibold">
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Ana Sayfa
                </a>
              </li>
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Teknoloji
                </a>
              </li>
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Eğitim
                </a>
              </li>
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Sağlık
                </a>
              </li>
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Gündem
                </a>
              </li>
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Yazılım
                </a>
              </li>
              <li>
                <a href="" class="relative transition-all hover:text-purple-700 hover:after:w-5/6 after:w-0 after:transition-all after:h-1 after:bg-purple-700 after:absolute after:rounded after:left-0 after:-bottom-2">
                  Ürünler
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent"
}
</script>
