<template>
  <div class="container">
      <div class="row">
        <div class="col-xs-12">
          <announcement></announcement>
          <app-article></app-article>
          <br>
      <app-contact>
      <p>Some content</p>
      <p slot="top"> Contact us and one of our members will contact you</p>
      <p slot="bottom">Please do not write sensitive information</p>

      </app-contact>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    
}
</script>