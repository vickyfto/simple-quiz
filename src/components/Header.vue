<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled><b>Fancy Quiz App</b></b-nav-item>
      <b-nav-item disabled>Counter: <b> correct {{ numCorrect }} </b> / <b> incorrect {{ numTotal }} </b> </b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: [
    'numCorrect',
    'numTotal'
  ]
}
</script>
