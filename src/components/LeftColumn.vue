<template>
    <!-- Left Column -->
    <div class="w3-third">
    
      <div class="w3-white w3-text-grey w3-card-4">
        <div class="w3-display-container">
          <img src="images/IMG_0107.jpg" style="width:100%" alt="Avatar">
          <div class="w3-display-bottomleft w3-container w3-text-white">
            <h2>Freddy Nygård</h2>
          </div>
        </div>
        <div class="w3-bar w3-ultra-violet">
          <router-link class="w3-bar-item w3-button" to="/">Home</router-link>
          <router-link class="w3-bar-item w3-button" to="/about">About</router-link>
          <router-link class="w3-bar-item w3-button" to="/webdev">Skills</router-link>
        </div>
        <div class="w3-container">
          <p><i class="fa fa-briefcase fa-fw w3-margin-right w3-large w3-text-ultra-violet"></i>Ingeniør</p>
          <p><i class="fa fa-home fa-fw w3-margin-right w3-large w3-text-ultra-violet"></i>Bodø, Norway</p>
          <p><i class="fa fa-envelope fa-fw w3-margin-right w3-large w3-text-ultra-violet"></i><a href="mailto:mail@freddnyg.no">mail@freddnyg.no</a></p>
          
          <div class="w3-container skills">
              <hr>
          <p class="w3-large"><b><i class="fa fa-asterisk fa-fw w3-margin-right w3-text-ultra-violet"></i>Skills</b></p>
          <p>Autodesk Inventor</p>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-ultra-violet" style="width:90%">90%</div>
          </div>
          <p>Autodesk AutoCad</p>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-ultra-violet" style="width:80%">
              <div class="w3-center w3-text-white">80%</div>
            </div>
          </div>
          <router-link to="/webdev"><p>Web Design / developement</p></router-link>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-ultra-violet" style="width:75%">75%</div>
          </div>
          <p>Programming</p>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-ultra-violet" style="width:50%">50%</div>
          </div>
          <br>

          <p class="w3-large w3-text-theme"><b><i class="fa fa-globe fa-fw w3-margin-right w3-text-ultra-violet"></i>Languages</b></p>
          <p>Norwegian</p>
          <div class="w3-light-grey w3-round-xlarge">
            <div class="w3-round-xlarge w3-ultra-violet" style="height:24px;width:100%"></div>
          </div>
          <p>English</p>
          <div class="w3-light-grey w3-round-xlarge">
            <div class="w3-round-xlarge w3-ultra-violet" style="height:24px;width:80%"></div>
          </div>
          <p>Swedish</p>
          <div class="w3-light-grey w3-round-xlarge">
            <div class="w3-round-xlarge w3-ultra-violet" style="height:24px;width:55%"></div>
          </div>
          <br>
        </div>
      </div><br>
      </div>

    <!-- End Left Column -->
    </div>

</template>

<script>
export default {
  name: 'LeftColumn',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
