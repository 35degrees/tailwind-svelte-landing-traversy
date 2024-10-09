<script>
  	import Hamburger from "../utilities/Hamburger.svelte"
	import MobileMenu from "../utilities/MobileMenu.svelte"

</script>

<nav class="relative container mx-auto p-6">
  <div class="flex items-center justify-between">
    <div class="pt-2">
      <img src="src/images/logo.svg" alt="logo">
    </div>
    <div class="hidden md:flex space-x-6">
      <a href="#" class="hover:text-darkGrayishBlue">Pricing</a>
      <a href="#" class="hover:text-darkGrayishBlue">Product</a>
      <a href="#" class="hover:text-darkGrayishBlue">About Us</a>
      <a href="#" class="hover:text-darkGrayishBlue">Careers</a>
      <a href="#" class="hover:text-darkGrayishBlue">Community</a>
    </div>
    <!-- button  -->
     <a href="#" class="hidden md:block p-3 px-6 pt-2 text-white bg-brightRed rounded-full baseline hover:bg-brightRedLight">Get Started</a>
     <Hamburger  />
   
</div>
</nav>