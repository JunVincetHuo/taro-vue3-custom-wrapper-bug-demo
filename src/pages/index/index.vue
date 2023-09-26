<template>
  <custom-wrapper class="index">
    <view>
      <text>{{ msg }}</text>
    </view>
  </custom-wrapper>
</template>

<script>
import { ref } from 'vue'
import './index.less'

export default {
  setup () {
    const msg = ref('Hello world')
    return {
      msg
    }
  }
}
</script>
