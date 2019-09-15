<template>
  <div id="app">
    <Style />
    <router-view/>
  </div>
</template>
<script>
import Style from './components/Style'
import 'bootstrap/dist/css/bootstrap.min.css';
export default {
  name: "app",
  components: {
    Style
  }
}
</script>