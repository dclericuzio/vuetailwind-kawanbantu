<template>
    <div class="w-full relative">

        <!-- bg -->
        <div class="relative">
            <!-- left -->
            <img src="@/assets/bgtopleft.svg" alt="atas kiri" class=" absolute top-28 left-20 z-[-99999] xs:left-0"/>
            <!-- right -->
            <img src="@/assets/bgtopleft.svg" alt="bawah kanan" class=" absolute top-[800px] right-14 z-[-99999]"/>
            <img src="@/assets/bgtopleft.svg" alt="atas kanan" class=" absolute top-10 -right-10 z-[-99999]"/>
            <img src="@/assets/bgtopright.svg" alt="atas bunder kanan" class=" absolute -top-48 right-0 z-[-99999]"/>

        </div>

        <!-- header -->
        <div class="container text-center">
            <h1 class="text-[48px] text-[#07335E] tracking-wide">Ayo Kawan, Bantu Mereka!</h1>
        </div>

        <!-- content -->
        <!-- <div class="flex flex-column justify-center pt-24 pb-24">
            <div class="flex flex-row space-x-14">
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 right-[25%] ">Pendidikan</h1>
                    </div>
                </div>

                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Non-profit</h1>
                    </div>
                </div>
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] text-center ">
                        <h1 class="text-[32px] text-[#FFFFFF] ">Tempat</h1>
                        <h1 class="text-[32px] text-[#FFFFFF] ">Ibadah</h1>
                    </div>
                </div>
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Lambaga Amal</h1>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex flex-column justify-center pb-36">
            <div class="flex flex-row space-x-14">
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Organisasi</h1>
                    </div>
                </div>
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Komunitas</h1>
                    </div>
                </div>
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Kampanye aksi sosial</h1>
                    </div>
                </div>
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Perusahaan</h1>
                    </div>
                </div>
            </div>
        </div> -->



        <!-- <div class="flex justify-between px-[120px] w-full max-h-96">
            <div class="bg-[url('@/assets/1.png')] relative w-{calc((100vw - 280px - 40px)/3)} h-{calc((100vw - 280px - 40px)/3)} bg-[length:100%_100%]">
                <div class="flex-column">
                    adadad
                </div>
            </div>
        </div> -->


        <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-y-28 xl:grid-cols-4 px-16 pt-32 place-items-center pb-32 z-1">
                <div class="bg-[url('@/assets/1.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 right-[25%] ">Pendidikan</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Bantuan untuk sekolah, kuliah dll.</h1>
                </div>
                

                <div class="bg-[url('@/assets/2.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Non-profit</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Organisasi nirlaba, yayasan dll.</h1>
                </div>

                <div class="bg-[url('@/assets/3.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative ">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-16 right-[32%]">Tempat</h1>
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 right-[33%]">Ibadah</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Donasi untuk keberlangsungan</h1>
                    <h1 class="text-[16px] text-[#07335E] text-center">politik, dll</h1>
                </div>

                <div class="bg-[url('@/assets/4.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-16 right-[26%]">Lembaga</h1>
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 right-[37%]">Amal</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Zakat, wakaf, infaq, dll.</h1>
                </div>

                <div class="bg-[url('@/assets/5.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Organisasi</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Program sosial, bantuan</h1>
                    <h1 class="text-[16px] text-[#07335E] text-center">sosial, dll</h1>
                </div>

                <div class="bg-[url('@/assets/6.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Komunitas</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center"> Komunitas, lembaga</h1>
                    <h1 class="text-[16px] text-[#07335E] text-center">masyarakat, dll.</h1>
                </div>

                <div class="bg-[url('@/assets/7.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-16 right-[23%]">Kampanye</h1>
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 right-[25%]">aksi sosial</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Donasi untuk keberlangsungan</h1>
                    <h1 class="text-[16px] text-[#07335E] text-center">politik, dll</h1>
                </div>

                <div class="bg-[url('@/assets/8.png')] w-[281px] h-[281px] rounded-[10px] bg-no-repeat bg-cover">
                    <div class="bg-[rgba(0,0,0,0.5)] h-full rounded-[10px] relative">
                        <h1 class="absolute text-[32px] text-[#FFFFFF] bottom-6 left-[25%] ">Perusahaan</h1>
                    </div>
                    <h1 class="text-[16px] text-[#07335E] pt-4 text-center">Program sosial perusahaan </h1>
                    <h1 class="text-[16px] text-[#07335E] text-center">, CSR, dll.</h1>
                </div>


           
           
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>