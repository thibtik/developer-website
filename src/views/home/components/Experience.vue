<template>
    <div class="experience">
        <div class="content">
                <div class="row">
                    <div class="header-experience">
                        <span class="subtitle">OVER 10 YEARS OF EXPERIENCE</span>
                        <h1 class="title">My Experience</h1>
                    </div>
                    <div class="experience-card" v-for="experience,index in experiences" :key="index">
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
    props:['experiences']
}
</script>

<style lang="scss">
     @import '../../../assets/scss/pages/home/experience.scss';
</style>