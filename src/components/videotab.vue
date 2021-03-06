<template>
  <div id="videotab">
        <div class="video">
            <video id="vid" >
                <source src="https://www.w3schools.com/html/mov_bbb.ogg" type="video/mp4">
            </video><a href="#" id="play" onClick="test"><i class="fa fa-play-circle fa-4x" aria-hidden="true"></i></a>

                <div class="details-div">
                    <h1 class="title">Digital Marketing 101</h1>
                    <div class="details">
                        <span><i class="fa fa-user-o" aria-hidden="true"></i>By Shashank Mittal</span>
                        <span class="mobile"><i class="fa fa-calendar-o" aria-hidden="true"></i>Feb 4, 2021</span>
                        <span class="desktop"><i class="fa fa-tag" aria-hidden="true"></i>12 lectures</span>
                        <span class="desktop"><i class="fa fa-clock-o" aria-hidden="true"></i>9:00 AM to 11:00 AM</span>
                        <span class="mobile"><i class="fa fa-clock-o " aria-hidden="true"></i>1.5hours</span>
                        <span class="desktop"><i class="fa fa-calendar-o " aria-hidden="true"></i>Last updated Nov 25,2020</span>
                        <span class="mobile"><i class="fa fa-tag" aria-hidden="true"></i>12 lectures</span>
                    </div>
                    
                </div>
                <div class="video-tab-btn">
                        <button class="btn book-btn desktop"> Book Now</button>
                        <button class="btn enroll-btn mobile"> Enroll for a Group Class</button>
                    </div>
            

        </div>
        <div class="instructor">
            <div class="box">
                <img class="inst-img" src="@/assets/profile.jpg" />
                <h1 class="inst-title">Shashank Mittal</h1>
                <p class="inst-des">Master Marketeer</p>
                <p class="tags"><span class="fmcg">FMCG Marketing</span><span>SEO</span><span>SMM</span><span>CRO</span><span>Branding</span></p>
                <p class="description">Hi! I'm Shashank. I have spent the last 40 years working in Marketing around the world.I've worked in advertising agencies,
                    FMCG companies, Automotive, Luxury cars and even the Indian rural market.<br>Marketing is a mindset, and I embody it.
                    <a href="#">Read More...</a>
                </p>
            </div>
        </div>
  </div>
</template>

<script>

export default {
mounted(){

    document.getElementById("play").onclick = function (){
        document.getElementById('vid').play();
    }
    
    },

}

</script>
