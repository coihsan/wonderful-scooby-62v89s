<template>
  <nav class="bg-gray-100 shadow-sm">
    <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
      <a
        href="/"
        class="text-3xl font-bold text-gray-800 hover:text-gray-900"
      >
        Judul Aplikasi
      </a>
      <ul class="flex justify-between mt-4">
        <li class="mr-6">
          <a href="/halaman-1" class="text-gray-800 hover:text-gray-900">
            Halaman 1
          </a>
        </li>
        <li class="mr-6">
          <a href="/halaman-2" class="text-gray-800 hover:text-gray-900">
            Halaman 2
          </a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
.navbar {
  @apply flex items-center justify-between;
}

.navbar a {
  @apply text-base;
}
</style>
