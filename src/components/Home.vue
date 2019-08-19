<template>
      <b-container fluid>
          <b-row>
                <b-col cols="3">
                    <div class="logo-container">
                        <h1 class="logo">rogério<span class="logo-symbol">{</span>leal<span class="logo-symbol">}</span></h1>
                        <small>Desenvolvedor Web</small>
                    </div>
                </b-col>
          </b-row>
          <b-row>
              <b-col>
                  <div class="code-container">
                      <div class="code-buttons-container">
                          <div class="rounded-circle code-button button-red"></div>
                          <div class="rounded-circle code-button button-orange ml-10"></div>
                          <div class="rounded-circle code-button button-green ml-10"></div>
                      </div>
                  </div>
              </b-col>
          </b-row>
      </b-container>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
