<template>
  <div>
    <div class="fixed z-30 inset-0 bg-gray-800 opacity-80"></div>
    <div
      class="
        px-8
        py-4
        fixed
        top-1/2
        left-1/2
        -translate-x-1/2 -translate-y-1/2
        z-40
        rounded-md
        m-auto
        w-[470px]
        max-w-xl
        bg-white
      "
    >
      <div class="flex h-full flex-col">
        <header class="mt-4">
          <h3 class="text-2xl font-semibold text-gray-600">
            <slot name="header"></slot>
          </h3>
        </header>
        <main class="mt-8">
          <slot name="main"></slot>
        </main>
        <footer class="flex items-center justify-end mt-8 mb-4">
          <slot name="footer"></slot>
        </footer>
      </div>
    </div>
  </div>
</template>
