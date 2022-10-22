<template>
    <div class="blog">
        <div class="contents">
            <div class="row">
                    <div class="header-blog">
                        <span class="subtitle">VISIT MY BLOG AND KEEP YOUR FEEDBACK</span>
                        <h1 class="title">My Blog</h1>
                    </div>
            </div>
            <div class="row">
                <div class="col-3">
                    <div class="img">
                        <img :src="pic1" alt="">
                    </div>
                    <div class="content-col">
                        <div class="sub-col">
                            <span class="name">CANADA</span>
                            <div class="identify-time">
                                <svg width="15px" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                <span>2 min read</span>
                            </div>
                        </div>
                        <div class="infor-detail">
                            <h4><a href="">T-shirt design is the part of design
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path></svg>
                            </a></h4>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="img">
                        <img :src="pic2" alt="">
                    </div>
                    <div class="content-col">
                        <div class="sub-col">
                            <span class="name">DEVELOPMENT</span>
                            <div class="identify-time">
                                <svg width="1rem" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                <span>2 min read</span>
                            </div>
                        </div>
                        <div class="infor-detail">
                            <h4><a href="">The services provide for design
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path></svg>
                            </a></h4>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="img">
                        <img :src="pic3" alt="">
                    </div>
                    <div class="content-col">
                        <div class="sub-col">
                            <span class="name">APPLICATION</span>
                            <div class="identify-time">
                                <svg width="15px" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                <span>2 min read</span>
                            </div>
                        </div>
                        <div class="infor-detail">
                            <h4><a href="">Mobile app landing design & app maintain
                            <svg class="w-10 h-1 0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path></svg>
                            </a></h4>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
    @import '../../../assets/scss/pages/home/blog.scss';
</style>

<script>
export default {
    data(){
        return{
            pic1:'https://inbio-react.netlify.app/static/953f09919eb224ffd8d5ada9ac38150b/d0f18/blog-big-01.webp',
            pic2:'https://inbio-react.netlify.app/static/24178887690433586b7481f2588d4cad/d0f18/blog-02.webp',
            pic3:'https://inbio-react.netlify.app/static/4302dce3a785c626c0756545d42f860c/d0f18/blog-03.webp'
        }
    }
}
</script>