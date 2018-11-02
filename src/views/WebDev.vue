<template>
  <!-- The Grid -->
  <div class="w3-row-padding">
    <LeftColumn/>
    <!-- Right Column -->
      <div class="w3-twothird">
        <div id="front" class="w3-container w3-card w3-white w3-margin-bottom">
          <h2 class="w3-text-grey w3-padding-16"><i class="fa fa-suitcase fa-fw w3-margin-right w3-xxlarge w3-text-ultra-violet"></i>Web Developement / design</h2>
          <div class="w3-container">
            <hr>
          </div>
        </div>

      <!-- End Right Column -->
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
import LeftColumn from '@/components/LeftColumn.vue'

export default {
  name: 'webdev',
  components: {
    LeftColumn
  }
}
</script>
