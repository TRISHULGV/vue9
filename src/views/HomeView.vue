<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
    <div id="loader">
        <span class="inner-logo"></span>
    </div>
    <section id="home">
        <h1>WELCOME TO <span class="br">Homestay For You</span></h1>
    <a href="#page2" class="btn btn-light">EXPLORE MORE</a>
    </section>
    <br>
    <br>
    <section id="page2">
        <h1>Recommended Homestays</h1>
        <br>
        <br>
        <div class="img-container">
        <div class="img img1"><a href="HTML/chikmaglur/chikmaglur.html">EXPLORE NOW</a></div>
        <div class="img img3"><a href="HTML/sakleshpoora/sakleshpoora.html">EXPLORE NOW</a></div>
        <div class="img img2"><a href="HTML/coorg/coorg.html">EXPLORE NOW</a></div>
        <div class="img img4"><a href="HTML/gokarna/gokarna.html">EXPLORE NOW</a></div>
    </div>
    </section>
    <br>
    <br>
    <hr>
    <br>
    <section id="page3">
        <h1>Places To Visit</h1>
        <br>
        <br>
        <div class="img-container">
        <div class="img img5"><a href="HTML/places/chikmaglur.html">EXPLORE NOW</a></div>
        <div class="img img7"><a href="HTML/places/sakleshpoora.html">EXPLORE NOW</a></div>
        <div class="img img6"><a href="HTML/places/coorg.html">EXPLORE NOW</a></div>
        <div class="img img8"><a href="HTML/places/gokarna.html">EXPLORE NOW</a></div>
    </div>
    </section>
    <br>
    <br>
    <hr>
    <br>
    <section id="about">
        <h1>ABOUT US</h1>
        <p> The purpose of a happy vacation is to leave behind the stress of a frenetic life and enjoy a laid back atmosphere. Sometimes planning a holiday could be a stress in itself. We at Homestayforyou.com do our bit to help you with a hassle free booking experience. From choosing accommodation, places to visit and everything needed just reach us to plan your perfect get away. We offer some of the best homestays at finest locations and top service without charging our customers. <br>So all you have to do is pick what suits you best and let us worry about the rest. With assured assistance and guidance we are committed to make your stay a memorable one.</p>
    </section>
    <br>
    <hr>
    <br>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
