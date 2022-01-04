<template>
  <div>
    <div class="container mx-auto">
      <div class="grid grid-cols-4 gap-4">
        <div class="col-span-3">
          <div class="w-full py-4">
            <div class="w-full py-4 px-8 text-white bg-gradient-to-r from-purple-900 via-purple-700 to-purple-900 relative rounded">
              <h3 class="font-semibold">Contact Page</h3>
              <icons-trend-icon class="absolute w-14 h-14 top-0 right-2 fill-current z-0 opacity-10" />
            </div>
          </div>
          <article>
            <p class="text-gray-700">
              This is a contact page.
            </p>
          </article>
        </div>
        <guest-sidebar-component/>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'StandardPage',
  layout: 'guest',
}
</script>
