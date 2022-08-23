<script>
export default {

}
</script>

<template>
  <main>
    <!--header-->
    <header class="md:mx-auto md:w-[80%] items-center py-[30px] px-[20px] md:px-[10px] flex justify-between">
      <div></div>
      <!---->
      <div class="hidden lg:flex">
        <ul class="flex space-x-[40px]">
          <li>
            <div id="control" class="font-semibold text-[15px] cursor-pointer">Why Mono <i class="las la-angle-down"></i></div>
            <ul class="w-[30%] absolute ml-[-100px] shadow-2xl shadow-gray-300 px-[30px] py-[40px] mt-[2px]" id="drop">
              <div class="space-y-[20px] flex flex-col">
                <div class="flex space-x-[20px]">
                  <div><img src="icon1.svg" class="w-[70px]" alt=""></div>
                  <div><span class="font-bold">Why Choose Mono</span>
                    <div>Here's why 250+ Businesses & Developers use Mono APIs</div>
                  </div>
                </div>
                <div class="flex space-x-[20px]">
                  <div><img src="icon2.svg" class="w-[70px]" alt=""></div>
                  <div><span class="font-bold">Pricing</span>
                    <div>Affordable pricing for developers, SMEs, and enterprises</div>
                  </div>
                </div>
                <div class="flex space-x-[20px]">
                  <div><img src="icon3.svg" class="w-[50px]" alt=""></div>
                  <div><span class="font-bold">See a Demo</span>
                    <div>Experience Mono APIs in action</div>
                  </div>
                </div>
              </div>
            </ul>
          </li>
          <!--second li-->
          <li class="font-semibold text-[15px] cursor-pointer">Products <i class="las la-angle-down"></i></li>
          <!--third li-->
          <li>
            <div class="font-semibold text-[15px] cursor-pointer">Learn <i class="las la-angle-down"></i></div>
            <ul class="w-[20%] absolute ml-[-120px] shadow-2xl shadow-gray-300 px-[30px] py-[40px] mt-[2px]" id="drop">
              <div class="space-y-[20px] flex flex-col">
                <div class="flex items-center space-x-[20px]">
                  <div><img src="learn1.svg" class="" alt=""></div>
                  <div class="font-bold">About us</div>
                </div>
                <!---->
                <div class="flex items-center space-x-[20px]">
                  <div><img src="learn2.svg" class="" alt=""></div>
                  <div class="font-bold">Blog</div>
                </div>
                <!---->
                <div class="flex items-center space-x-[20px]">
                  <div><img src="learn3.svg" class="" alt=""></div>
                  <div class="font-bold">Tutorials</div>
                </div>
                <!---->
                <div class="flex items-center space-x-[20px]">
                  <div><img src="learn4.svg" class="" alt=""></div>
                  <div class="font-bold">Coverage</div>
                </div>
              </div>
            </ul>
          </li>
          <!--forth li-->
          <li>
            <div class="font-semibold text-[15px] cursor-pointer">Developers <i class="las la-angle-down font-bold"></i></div>
            <ul class="w-[20%] absolute ml-[-120px] shadow-2xl shadow-gray-300 px-[30px] py-[40px] mt-[2px]" id="drop">
              <div class="space-y-[20px] flex flex-col">
                <div class="flex items-center space-x-[20px]">
                  <div><img src="d-icon.svg" class="" alt=""></div>
                  <div class="font-bold">Overview</div>
                </div>
                <!---->
                <div class="flex items-center space-x-[20px]">
                  <div><img src="docs-icon.svg" class="" alt=""></div>
                  <div class="font-bold">Documentation</div>
                </div>
              </div>
            </ul>
          </li>
          <!--end li-->
        </ul>
      </div>
      <!--signin btn-->
      <div class="hidden lg:flex">
        <button class="bg-blue-700 text-white py-[10px] px-[15px] rounded-md btn">
          Sign in
        </button>
      </div>
      <!--open menu-->
      <div class="lg:hidden text-black">
        <div class="text-[40px]">
          <i class="las la-bars"></i>
        </div>
      </div>
    </header>
  </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Open+Sans:wght@500&display=swap');
header {
  font-family: 'Lato', sans-serif;
}
li #drop {
  display: none;
  background: #fff;
  border-radius: 10px;
  cursor: pointer;
}

li:hover > #drop {
  display: flex;
}

.btn {
  font-family: 'Open Sans', sans-serif;
  font-size:15px;
  font-weight: medium;
}
</style>