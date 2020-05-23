<template>
<div>
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
</div>
 
</template>

<script>
import NavHeader from "../components/NavHeader"
import NavHeader from "../components/NavFooter"

export default {
  name: 'home',
  components:{
      NavHeader,
     NavHeader
  }
}
</script>