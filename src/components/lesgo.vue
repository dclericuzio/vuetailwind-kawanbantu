<template>
    <div class="w-full relative">

        <!-- bg -->
        <div class="absolute">
            <!-- left -->
            <img src="@/assets/bgtopleft.svg" alt="atas kiri" class="top-60 left-0"/>
            <!-- right -->

        </div>

        <!-- header -->
        <div class="container text-center">
            <h1 class="text-[48px] text-[#07335E] tracking-wide">Ayo Kawan, Bantu Mereka!</h1>
        </div>

        <!-- content -->
        <div class="grid grid-cols-4 gap-y-28 px-16 pt-32 place-items-center pb-32">
            <!-- <div>
                <img src="@/assets/1.png" alt="pendidikan"/>
            </div>
            <div>
                <img src="@/assets/2.png" alt="nonprofit"/>
            </div>
            <div>
                <img src="@/assets/3.png" alt="ibadah"/>
            </div>
            <div>
                <img src="@/assets/4.png" alt="lembaga"/>
            </div>
            <div>
                <img src="@/assets/5.png" alt="organisasi"/>
            </div>
            <div>
                <img src="@/assets/6.png" alt="komunitas"/>
            </div>
            <div>
                <img src="@/assets/7.png" alt="kampanye"/>
            </div>
            <div>
                <img src="@/assets/8.png" alt="perusahaan"/>
            </div> -->
            <div v-for="dd in images" :key="dd">
                <img :src="require(`@/assets/${project.img}`)" :alt="dd"/>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    data(){
        return{
            images: [
                {
                    img: "1.png",
                    name: "pendidikan"                
                },
                {
                    img: "2.png",
                    name: "nonprofit"                
                },
                {
                    img: "3.png",
                    name: "pendidikan"                
                },
                {
                    img: "4.png",
                    name: "pendidikan"                
                },
                {
                    img: "5.png",
                    name: "pendidikan"                
                },
                {
                    img: "6.png",
                    name: "pendidikan"                
                },
                {
                    img: "7.png",
                    name: "pendidikan"                
                },
                {
                    img: "8.png",
                    name: "pendidikan"                
                }
            ]
        }
        
    },
        props: {
        image: {
            type: String,
            default: '', // example: 'imagename.svg'
        },
        },

        computed: {
        imagePath() {
            if (this.image !== '') {
            return require(`@/assets/${image}`);
            }
        }
        }
    
}
</script>

<style>

</style>