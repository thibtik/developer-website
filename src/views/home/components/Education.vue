<template>
    <div class="experience">
        <div class="content">
            <div class="row">
                <!-- <div class="col-lg-12"> -->
                    <div class="header-experience">
                        <span class="subtitle">PHD, MASTER AND BACHELOR</span>
                        <h1 class="title">Education</h1>
                    </div>
                    <div class="experience-card" v-for="experience,index in educations" :key="index">
                    <!-- <b-card border-variant="light"> -->
                    <div class="experience-col" >
                            <div class="experience-left">
                                <div class="experience-img">
                                    <img :src="experience.image" alt="">
                                </div>
                                <div class="experience-center">
                                    <span class="date">{{ experience.date }}</span>
                                    <h3 class="title">{{experience.title}}</h3>
                                    <h6 class="position">{{experience.position}}</h6>
                                    <p class="description">{{experience.description}}</p>
                                </div>
                            </div>
                            <div class="experience-right">
                                <button class="contact-btn" border-variant="light">CONTACT ME</button>
                            </div>
                    </div>
                    <!-- </b-card> -->
                    </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    props:['educations']
}
</script>

<style lang="scss">
     @import '../../../assets/scss/pages/home/experience.scss';
</style>