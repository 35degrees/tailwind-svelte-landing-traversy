<script>

  let isOpen = false
 function toggleIsOpen() {
  isOpen = !isOpen
 }

</script>

<button id="menu-btn" class="block relative ml-[360px] hamburger md:hidden focus:outline-none" class:open={isOpen} on:click={(toggleIsOpen)}>
  <span class="hamburger-top"></span>
  <span class="hamburger-middle"></span>
  <span class="hamburger-bottom"></span>
</button>

<div class="md:hidden">
  <div id="menu" class="absolute flex-col items-center self-end py-8 mt-10 space-y-6 font-bold bg-white sm:w-auto sm:self-center left-6 right-6 drop-shadow-md"  class:flex={isOpen} class:hidden={!isOpen}>
    <a href="#">Pricing</a>
    <a href="#">Product</a>
    <a href="#">About Us</a>
    <a href="#">Careers</a>
    <a href="#">Community</a>
  </div>
</div>

<style>
  .hamburger {
    cursor: pointer;
    width: 24px;
    height: 24px;
    transition: all 0.25s;
    position: relative;
    outline: none;
    user-select: none;
  }

  .hamburger-top,
  .hamburger-middle,
  .hamburger-bottom {
    position: absolute;
    top: 0;
    left: 0;
    width: 24px;
    height: 2px;
    background: #000;
    transform: rotate(0);
    transition: all 0.32s;
  }

  .hamburger-middle {
    transform: translateY(7px)
  }
  .hamburger-bottom {
    transform: translateY(14px)
  }

  .open {
    transform: rotate(90deg);
    transform: translateY(0px);

  }

  .open .hamburger-top {
    transform: rotate(45deg) translateY(6px) translate(6px);
  }
  .open .hamburger-middle {
    display: none;
  }
  .open .hamburger-bottom {
    transform: rotate(-45deg) translateY(6px) translate(-6px);
  }
</style>