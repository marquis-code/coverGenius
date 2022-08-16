<template>
    <b-container class="background p-5 d-flex justify-content-between align-items-center rounded-lg border my-5">
        <div>
            <h1 class="header text-wrap font-weight-bold text-white mb-5" style="width : 30rem;">Get Auto Insurance that fits your business needs and budget</h1>
            <button class="py-2 px-4 rounded-lg border button mt-4"><small class="text-white font-weight-light">Get Auto
                    Insurance</small></button>
        </div>
        <div>
            <div class="imageContainer1 d-flex align-items-end pb-1">
                <img src="@/static/img/client1.svg" alt="" class="pr-1" />
                <img src="@/static/img/client2.svg" alt="" class="image1 pl-1" />
            </div>
            <div class="imageContainer2 d-flex align-items-start pt-1">
                <img src="@/static/img/client3.svg" alt="" class="image1 pr-2" />
                <img src="@/static/img/client4.svg" alt="" class="pl-2" />
            </div>
        </div>
    </b-container>
</template>

<script>
export default {

} 
</script>

<style scoped>
.button {
    background-color: #439687;
}

.header {
    color: #094063;
}

.background {
    background-color:  #101828;
}

/* img{
    height: 45%;
    width : 45%;
} */

.image1 {
    height: 40%;
    width : 40%;
} 
</style>