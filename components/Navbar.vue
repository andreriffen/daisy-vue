<template>
    <nav id="navbar-wrapper" class="navbar opacity-95 outline-1 fixed w-full top-0 z-50">
    
    <div class="navbar-start">
      <div class="dropdown">
        <div tabindex="0" class="btn lg:hidden" >
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg></div>
        <ul tabindex="0" class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow rounded-box w-52">
          <li><button class="btn" href="#content">About</button></li>
          <li><button class="btn" href="#who-am-i">Who am I?</button></li>
        <li><button class="btn"><a href="#who-am-i">Contact</a></button></li>
        </ul>
      </div>
      <a class="btn btn-ghost normal-case text-xl" href="#content">Logo</a>
    </div>
   
    <div class="navbar-end hidden lg:flex">
      <ul class="menu menu-horizontal px-1"> 
        <li><button class="btn"><a href="#content">About</a></button></li>
        <li><button class="btn"><a href="#who-am-i">Who am I?</a></button></li>
        <li><button class="btn"><a href="#who-am-i">Contact</a></button></li>
      </ul>
    </div>
    <div class="navbar-end">
      <a class="btn">Button</a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar"
};
</script>
<style>
</style>