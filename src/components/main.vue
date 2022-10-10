<template>
  <Gnb />
</template>

<script>


import Gnb from '@/components/menu/gnb'

//아래 컴포넌트에 선언된 항목많이 template에서 사용할 수 있음.
export default {
  name: 'Main',
  components: {
    Gnb
  }
}
</script>

<style scoped>
  * { background:black}
</style>