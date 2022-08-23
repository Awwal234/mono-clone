<template>
    <main>
        <div class="mt-[60px] md:mt-[80px] mx-auto w-[100%] px-[20px] md:px-[10px] md:w-[80%] lg:flex lg:justify-between lg:items-center">
            <div class="w-[95%] md:w-[80%] lg:w-[60%]">
                <router-link to="">
                <div class="kenya bg-gray-100 space-x-[10px] items-center w-fit rounded-full p-[10px]">
                    <span class="new text-[10px] text-white font-bold bg-blue-700 py-[4px] px-[8px] rounded-full">NEW</span>
                    <span class="new text-[13px] font-normal">Mono is live in Kenya</span>
                    <span class="arrow"><i class="las la-arrow-right"></i></span>
                </div>
                </router-link>
                <div class="newy mt-[30px] lg:mt-[40px] text-[40px] md:text-[70px] lg:text-[80px] font-bold">
                    <span>
                        Reliably access bank accounts
                    </span>
                </div>
                <div class="new mt-[20px] md:mt-[20px] text-[20px] md:text-[25px]">
                    <span>
                        Mono helps businesses to access high-quality 
                        financial data and direct bank payments.
                    </span>
                </div>
                <div class="space-y-[15px] md:flex mt-[40px] md:space-x-[15px] md:space-y-[0px]">
                    <div>
                        <button class="newy bg-blue-700 text-white text-[17px] md:text-[16px] font-bold rounded-xl px-[15px] py-[13px]">Get started for free <i class="las la-arrow-right"></i></button>
                    </div>
                    <div>
                        <button class="newy bg-gray-100 text-black text-[17px] md:text-[16px] font-bold rounded-xl px-[15px] py-[13px]">Contact Sales <i class="las la-arrow-right"></i></button>
                    </div>
                </div>
            </div>
            <!--lane or side 2-->
            <div class="hidden lg:block">
                <img src="monogif.webp" class="" alt="">
                <div class="newy mx-auto text-[13px] cursor-pointer w-fit mt-[8px] bg-gray-100 rounded-full p-[10px] text-gray-600">
                    Replay <i class="las la-play text-black"></i>
                </div>
            </div>
        </div>
        <div class="mt-[80px]"></div>
        <!--trusted by-->
        <div class="newy md:w-[80%] mx-auto w-[100%] px-[20px] md:px-[10px]">
            <div>
                <div class="text-gray-800">Trusted by</div>
                <div class="md:flex-wrap space-y-[13px] md:mt-[40px] md:flex md:space-x-[0px] xl:space-x-[100px] md:space-y-[0px]">
                    <img src="img/carbon-logo.svg" class="" alt=""/>
                    <img src="img/auto-logo.svg" class="" alt=""/>
                    <img src="img/flutter-logo.svg" class="" alt=""/>
                    <img src="img/credit-logo.svg" class="" alt=""/>
                </div>
            </div>
        </div>
    </main>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Open+Sans:wght@500&display=swap');
.kenya:hover > .arrow{
    margin-left: 15px;
}
.newy {
    font-family: 'Lato', sans-serif;
}
.new {
    font-family: 'Open Sans', sans-serif;
}
</style>