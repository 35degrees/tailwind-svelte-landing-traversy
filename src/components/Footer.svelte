<script>

</script>

<footer class="bg-veryDarkBlue">
  <!-- main flex container  -->
   <div class="container flex flex-col-reverse justify-between px-6 py-10 mx-auto space-y-8 md:flex-row md:space-y-0">
    <!-- logo and social links  -->
     <div class="flex flex-col-reverse items-center justify-between space-y-12 md:flex-col md:space-y-0 md:items-start">
      <div class="mx-auto my-6 text-center text-white md:hidden">
        Copyright &copy; 2022, All Rights Reserved
      </div>
      <!-- logo  -->
       <div>
        <img src="https://raw.githubusercontent.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/logo-white.svg" alt="logo white" class="h-8">
       </div>
       <!-- social links  -->
        <div class="flex justify-center space-x-4">
          <!-- link 1 -->
           <a href="#">
            <img src="https://raw.githubusercontent.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/icon-facebook.svg" alt="fb">
           </a>
          <!-- link 2 -->
           <a href="#">
            <img src="https://raw.githubusercontent.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/icon-youtube.svg" alt="fb">
           </a>
          <!-- link 3 -->
           <a href="#">
            <img src="https://raw.githubusercontent.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/icon-pinterest.svg" alt="fb">
           </a>
          <!-- link 4 -->
           <a href="#">
            <img src="https://raw.githubusercontent.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/icon-instagram.svg" alt="fb">
           </a>
          <!-- link 5 -->
           <a href="#">
            <img src="https://raw.githubusercontent.com/35degrees/tailwind-svelte-landing-traversy/blob/main/src/images/icon-twitter.svg" alt="fb">
           </a>
        </div>
     </div>

     <!-- list container  -->
      <div class="flex justify-around space-x-32">
        <div class="flex flex-col space-y-3 text-white">
          <a href="#" class="hover:text-brightRed">Home</a>
          <a href="#" class="hover:text-brightRed">Pricing</a>
          <a href="#" class="hover:text-brightRed">Products</a>
          <a href="#" class="hover:text-brightRed">About</a>
        </div>
        <div class="flex flex-col space-y-3 text-white">
          <a href="#" class="hover:text-brightRed">Careers</a>
          <a href="#" class="hover:text-brightRed">Community</a>
          <a href="#" class="hover:text-brightRed">Privacy Policy</a>
        </div>
      </div>

      <!-- input container  -->
       <div class="flex flex-col justify-between">
        <form>
          <div class="flex space-x-3">
            <input type="text" class="flex-1 px-4 rounded-full focus:outline-none" placeholder="Updates in your inbox">
            <button class="px-6 py-2 text-white rounded-full bg-brightRed hover:bg-brightRedLight focus:outline-none">
              Go!
            </button>
          </div>
        </form>
        <div class="hidden text-white md:block text-center">
          Copyright &copy; 2022, All Rights Reserved
        </div>
       </div>
   </div>
</footer>