<template>
  <div class="w-full bg-gray-100 py-4">
    <div class="container mx-auto">
      <div class="flex justify-between justify-items-center">
        <guest-logo-component/>
        <div class="flex items-center">
          <nav>
            <ul class="flex gap-2 items-center font-semibold">
              <li><a href="">Ana Sayfa</a></li>
              <li><a href="">Teknoloji</a></li>
              <li><a href="">Eğitim</a></li>
              <li><a href="">Sağlık</a></li>
              <li><a href="">Gündem</a></li>
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
