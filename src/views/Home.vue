<template>
  <div class="home">
    <Header />
    <Content />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '../components/Header'
import Content from '../components/Content'

export default {
  name: 'Home',
  components: {
    Header,
    Content
  }
}
</script>
