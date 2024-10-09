<section id="cta" class="bg-brightRed">

  <!-- flex container  -->
   <div class="container flex flex-col items-center justify-between px-6 py-24 mx-auto space-y-12 md:py-12 md:flex-row md:space-y-0">

    <!-- heading  -->
     <h2 class="text-5xl font-bold leading-tight text-center text-white md:text-4xl md:max-w-xl md:text-left">
      Simplify how your team works today
     </h2>
     <div>
      <a href="#" class="p-3 px-6 pt-2 text-brightRed shadow-2xl bg-white rounded-full baseline hover:bg-gray-300">Get Started</a>
    </div>
   </div>

</section>

<style>
  #cta {
    background-image: url('https://github.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/bg-simplify-section-desktop.svg');
    background-repeat: no-repeat;
    background-position: -10% 100%;
  }

  @media (max-width: 576px) {
    #cta {
    background-image: url('https://github.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/bg-simplify-section-mobile.svg');
    background-position: 0%;
  }
  }
</style>