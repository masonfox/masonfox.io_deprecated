<template>
  <section class="bg-gray-800 p-10 md:pt-20 md:pb-14 md:px-20"> 
    <div class="w-1/2">
      <div class="text-5xl md:text-7xl text-white font-black leading-tight">
        <div class="mb-5">
            <span class="text-gray-600">ᶘ ᵒᴥᵒᶅ</span>
            <div class="sm:inline text-gray-500">
                <span class="text-4xl relative bottom-3">🠐</span> 
                <span class="font-normal text-base relative bottom-5 -left-2">The internet says this is a baby seal</span>
            </div>
        </div>
        <span class="text-green-400">Hello!</span>
        <span>I'm <span class="highlight">Mason</span> and I was told this is my website</span>
        <span class="text-gray-500 relative md:-left-3">...</span>
      </div>
    </div>

    <!-- <span class="relative z-0 inline-flex rounded-full p-3 bg-gray-700 gap-4 mt-6">
        <button type="button" class="w-32 shadow-md px-3 py-2 rounded-full border-4 border-green-500 bg-green-400 text-white border-transparent hover:bg-green-600 focus:z-10 focus:outline-none focus:ring-1 focus:ring-indigo-500 focus:border-gray-50 font-bold">
            Active
        </button>
        <button type="button" v-for="n in 3" class="w-32 shadow-md px-3 py-2 rounded-full border-4 text-white border-red-50 hover:bg-gray-50 focus:z-10 focus:outline-none focus:ring-1 focus:ring-indigo-500 focus:border-green-500 font-bold">
            Years
        </button>
    </span> -->
  </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
    .highlight {
        position: relative;
        display: inline-block;
        z-index: 10;

        &:after {
            content: '';
            position: absolute;
            bottom: 1rem;
            left: 0rem;
            @apply bg-green-500;
            height: 1.5rem;
            width: 15rem;
            display: block;
            z-index: -1;

            @media (max-width: 768px) {
                display: none;
            }
        }
    }
</style>