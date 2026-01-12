<script lang="ts">
  let isScrolled = $state(false);

  $effect(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 50;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<header class="w-full bg-white text-gray-900 sticky top-0 z-50 transition-all duration-300">
  <!-- Top Bar -->
  <div class="border-b border-gray-100 hidden md:block">
    <div class="max-w-[1600px] mx-auto px-6 h-10 flex justify-end items-center gap-6 text-[11px] font-medium tracking-wide text-gray-500 uppercase">
      <a href="#" class="hover:text-black transition-colors">Club Partnerships</a>
      <a href="#" class="hover:text-black transition-colors">About</a>
      <a href="#" class="hover:text-black transition-colors">Contact</a>
      <button class="hover:text-black transition-colors flex items-center gap-1">USD <span class="text-[8px]">▼</span></button>
    </div>
  </div>

  <!-- Main Nav -->
  <div class="border-b border-gray-100">
    <div class="max-w-[1600px] mx-auto px-6 h-20 flex justify-between items-center relative">
      <!-- Logo -->
      <div class="w-32">
        <a href="/" class="block w-8 h-8 text-black hover:text-gray-600 transition-colors">
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M10.1214 2.40967C11.0087 2.40967 11.7683 3.04566 11.9242 3.91908L12.1482 5.17341C12.3042 6.04681 13.0638 6.68282 13.951 6.68282H15.47C17.83 6.68282 19.7432 8.59595 19.7432 10.9559C19.7432 12.3696 19.0567 13.6229 17.999 14.4007C18.4424 14.5514 18.7925 14.7906 19.0496 15.1048C19.3141 15.4514 19.5031 15.9439 19.6165 16.5641C19.6354 16.7283 19.6591 16.8879 19.6827 17.0475C19.7063 17.2071 19.7299 17.3667 19.7488 17.5309C19.7685 17.7014 19.783 17.8473 19.7951 17.9686C19.8062 18.0809 19.8153 18.1721 19.8244 18.2423C19.8622 18.7531 19.9189 19.1726 19.9945 19.4827C20.0742 19.9188 20.2352 20.3438 20.4633 20.7231H17.2352C17.084 20.4313 16.9895 20.0847 16.9139 19.7016C16.8489 19.3722 16.7979 18.9617 16.7368 18.4704C16.7268 18.3904 16.7166 18.3083 16.706 18.2241L16.5926 17.385C16.4981 16.7465 16.3847 16.2905 16.2713 15.9986C16.139 15.725 15.9312 15.5244 15.6476 15.4149C15.3453 15.3055 14.8917 15.2291 14.2491 15.2291H14.1037C13.2164 15.2291 12.4568 14.5931 12.3009 13.7197L12.0769 12.4653C11.9209 11.5919 11.1613 10.9559 10.274 10.9559H7.53417V15.8395H4.48193V2.40967H10.1214ZM16.6909 10.9559C16.6909 11.6302 16.1443 12.1769 15.47 12.1769H13.951C13.0638 12.1769 12.3042 11.5408 12.1482 10.6674L11.9242 9.41312C11.7683 8.53971 11.0087 7.9037 10.1214 7.9037H7.53417V5.46189H10.274C11.1613 5.46189 11.9209 6.0979 12.0769 6.97131L12.3008 8.22563C12.4568 9.09904 13.2164 9.73505 14.1037 9.73505H15.47C16.1443 9.73505 16.6909 10.2817 16.6909 10.9559Z"
              fill="currentColor"
            />
          </svg>
        </a>
      </div>

      <!-- Center Nav -->
      <nav class="hidden md:flex items-center gap-10 text-[13px] font-medium tracking-wide uppercase">
        <a href="#" class="hover:text-gray-600 transition-colors">Shop</a>
        <a href="#" class="hover:text-gray-600 transition-colors">Collections</a>
        <a href="#" class="hover:text-gray-600 transition-colors">Our Story</a>
        <a href="#" class="hover:text-gray-600 transition-colors">Lookbook</a>
      </nav>

      <!-- Right Icons -->
      <div class="w-32 flex justify-end items-center gap-6">
        <button aria-label="Search" class="hover:text-gray-600">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
            <path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
          </svg>
        </button>
        <button aria-label="Cart" class="hover:text-gray-600 relative">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 10.5V6a3.75 3.75 0 1 0-7.5 0v4.5m11.356-1.993 1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 0 1-1.12-1.243l1.264-12A1.125 1.125 0 0 1 5.513 7.5h12.974c.576 0 1.059.435 1.119 1.007ZM8.625 10.5a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm7.5 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Z" />
          </svg>
          <span class="absolute -top-1 -right-1 bg-gray-900 text-white text-[9px] w-3.5 h-3.5 flex items-center justify-center rounded-full">0</span>
        </button>
      </div>
    </div>
  </div>
</header>
