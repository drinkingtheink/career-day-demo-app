<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Here is a bunch of text so we can see changes.
    </p>
    <p>
      Vestibulum eu pharetra tortor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nam suscipit neque vitae commodo finibus. Phasellus at mollis purus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vivamus vel urna vel nunc malesuada volutpat. Proin at tortor gravida, cursus risus in, euismod enim. Phasellus vitae pharetra magna. In vehicula elementum arcu quis consectetur. Donec scelerisque sapien et fringilla efficitur. Proin tempus risus vel libero fringilla, in sagittis arcu molestie. Suspendisse dictum eros condimentum metus mollis, et aliquam nisl fermentum. Pellentesque lacus ligula, aliquam vitae vehicula vel, elementum vel felis. Vivamus hendrerit fringilla arcu, at imperdiet orci eleifend ut.
    </p>
    <p>
      Cras elementum urna tellus, semper lobortis purus placerat in. Aliquam scelerisque sem non mi blandit tristique. Donec molestie, arcu a ornare ultrices, quam elit tempor augue, a porttitor tortor mi varius dolor. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Phasellus faucibus consequat neque ac tempus. Donec ut ex ac ex mollis lobortis et ut leo. Duis in odio lobortis, rutrum justo ac, luctus dolor. Nam viverra, diam non venenatis eleifend, mauris purus lobortis mi, vel tempor lectus risus ut neque. Donec at rhoncus justo.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.hello {
  max-width: 800px;
  margin: 0 auto;
}
</style>
