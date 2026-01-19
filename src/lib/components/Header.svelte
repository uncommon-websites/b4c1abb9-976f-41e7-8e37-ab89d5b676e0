<script>
  export let active = "Product";
</script>

<header class="sticky top-0 z-50 w-full border-b border-gray-100 bg-white/95 backdrop-blur-sm">
  <div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-4 sm:px-6 lg:px-8">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2">
        <span class="text-2xl font-bold tracking-tight font-sans">Camu</span>
      </a>
      
      <nav class="hidden md:flex items-center gap-6">
        {#each ["Product", "Solutions", "Success Stories", "Security", "Company"] as item}
          <a href="#{item.toLowerCase()}" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
            {item}
          </a>
        {/each}
      </nav>
    </div>

    <div class="flex items-center gap-4">
      <a href="#login" class="text-sm font-medium text-gray-900 hover:text-gray-700">
        Log in
      </a>
      <a href="#demo" class="rounded-full bg-black px-4 py-2 text-sm font-medium text-white hover:bg-gray-800 transition-colors">
        Request Demo
      </a>
    </div>
  </div>
</header>
