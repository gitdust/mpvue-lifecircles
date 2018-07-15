<template>
  <div>
    Page0
    <a
      href="/pages/Page1/main">navigate Page1</a>
     <a
      open-type="navigateBack"
      :delta="1"
      href="/pages/Page0/main">navigateBack delta 1</a>
    <a
      open-type="redirect"
      href="/pages/Page1/main">redirect Page1</a>
    <a
      open-type="reLaunch"
      href="/pages/Page1/main">reLaunch Page1</a>
    <a
      open-type="switchTab"
      href="/pages/TabBar0/main">navigate TabBar0</a>
    <a
      open-type="redirect"
      href="/pages/TabBar0/main">redirect TabBar0</a>
    <a
      open-type="reLaunch"
      href="/pages/TabBar0/main">reLaunch TabBar0</a>
  </div>
</template>

<script>
import { formatTime } from '@/utils/index'
import card from '@/components/card'

export default {
  components: {
    card
  },
  beforeCreate() {
    console.log('%cPage0 beforeCreate', 'color: #E01A4F');
  },
  created() {
    console.log('%cPage0 created', 'color: #E01A4F');
  },
  onLoad() {
    console.log('%cPage0 onLoad', 'color: #E01A4F');
  },
  onShow() {
    console.log('%cPage0 onShow', 'color: #E01A4F');
  },
  onReady() {
    console.log('%cPage0 onReady', 'color: #E01A4F');
  },
  onHide() {
    console.log('%cPage0 onHide', 'color: #E01A4F');
  },
  onUnload() {
    console.log('%cPage0 onUnload', 'color: #E01A4F');
  },
  beforeMount() {
    console.log('%cPage0 beforeMount', 'color: #E01A4F');
  },
  mounted() {
    console.log('%cPage0 mounted', 'color: #E01A4F');
  },
  beforeUpdate() {
    console.log('%cPage0 beforeUpdate', 'color: #E01A4F');
  },
  updated() {
    console.log('%cPage0 updated', 'color: #E01A4F');
  },
  beforeDestroy() {
    console.log('%cPage0 beforeDestroy', 'color: #E01A4F');
  },
  destroyed() {
    console.log('%cPage0 destroyed', 'color: #E01A4F');
  },
}
</script>

<style>
.log-list {
  display: flex;
  flex-direction: column;
  padding: 40rpx;
}

.log-item {
  margin: 10rpx;
}
</style>
