<script>
export default {
    data() {
        return {
            buildTitle: "Build for the future of digital finance.",
            followTitle: "Bring tomorrow's solutions to life, with our customer-focused solutions, today.",
        }
    },
}
</script>

<template>
    <section class="w-[100%] md:w-[80%] mx-auto px-[20px] md:px-[10px]">
        <div class="btitle mt-[90px] w-[90%] md:w-[90%] lg:w-[50%]">
            <div class="text-[27px] md:text-[40px] lg:text-[60px] font-bold">{{buildTitle}}</div>
            <div class="mt-[20px] md:mt-[20px] text-[16px] md:text-[20px] lg:text-[25px]">{{followTitle}}</div>
        </div>
        <!--illustrate part-->
        <div class="btitle mt-[90px] h-[400px] md:h-[400px] text-white md:w-full rounded-2xl bg-blue-700 py-[30px] px-[25px] md:py-[50px] md:px-[40px] lg:px-[60px]">
            <div class="md:w-[60%] lg:w-[30%] mt-[30px]">
                <div>
                    <img src="img/collect.svg" class="" alt=""/>
                    <div class="font-bold mt-[20px] text-[25px] md:text-[40px]">Connect</div>
                    <div class="mt-[15px] font-bold text-[16px] md:text-[16px]">Securely access financial accounts for statements, transactions, and identity</div>
                    <div class="btitle mt-[30px]">
                        <button class="bg-white font-bold text-blue-700 px-[20px] py-[10px] rounded-xl">Start with Connect <i class="las la-arrow-right"></i></button>
                    </div>
                </div>
            </div>
        </div>
        <!--moving to the next two build futures-->
        <div class="btitle md:flex md:justify-between mt-[30px]">
            <div class="md:w-[48%] h-[500px] md:h-[650px] w-full rounded-2xl py-[30px] px-[25px] md:py-[30px] bg-gray-200 md:px-[40px]">
                <div><img src="img/dpay.svg" alt=""/></div>
                <div class="mt-[20px] md:mt-[20px] text-black text-[25px] md:text-[40px] font-bold">DirectPay</div>
                <div class="mt-[20px] md:mt-[20px] font-bold text-gray-900 md:w-[80%] text-[18px]">Collect bank payments in your web or mobile app. No cards. No chargebacks</div>
                <div class="mt-[20px] md:mt-[20px]">
                    <button class="bg-blue-800 text-white rounded-xl font-bold px-[20px] py-[10px]">Start with DirectPay <i class="las la-arrow-right"></i></button>
                </div>
                <div class="mt-[20px] flex w-fit h-fit bg-gray-50 py-[10px] px-[20px] rounded-full">
                    In Partnership with <img src="img/flutter-logo.svg" class="w-[100px] ml-[10px]" alt=""/>
                </div>
            </div>
            <!--second phase-->
            <div class="mt-[30px] md:mt-[0px] md:w-[48%] h-[500px] md:h-[650px] w-full rounded-2xl py-[30px] px-[25px] md:py-[30px] bg-black md:px-[40px]">
                <div class="w-[35px]"><img src="img/per.svg" class="w-full" alt=""/></div>
                <div class="mt-[20px] md:mt-[20px] text-white text-[25px] md:text-[40px] font-bold">Percept</div>
                <div class="mt-[20px] md:mt-[20px] font-bold text-gray-100 md:w-[80%] text-[18px]">Money operations and reconciliation for all your corporate accounts, in one dashboard</div>
                <div class="mt-[20px] md:mt-[20px]">
                    <button class="bg-zinc-900 text-white rounded-xl font-bold px-[20px] py-[10px]">Request access <i class="las la-clock"></i></button>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.btitle {
    font-family: 'Lato', sans-serif;
}
</style>