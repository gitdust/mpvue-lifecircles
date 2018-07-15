<template>
  <div>
    Page1
    <a
      href="/pages/Page0/main">navigate Page0</a>
     <a
      href="/pages/Page2/main">navigate Page2</a>
    <a
      open-type="navigateBack"
      :delta="1"
      href="/pages/Page0/main">navigateBack delta 1</a>
    <a
      open-type="navigateBack"
      :delta="2"
      href="/pages/Page0/main">navigateBack delta 2</a>
    <a
      open-type="navigateBack"
      :delta="30"
      href="/pages/Page0/main">navigateBack delta 30</a>
    <a
      open-type="reLaunch"
      href="/pages/Page0/main">reLaunch Page0</a>
        <a
      open-type="reLaunch"
      href="/pages/Page1/main">reLaunch self</a>
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  beforeCreate() {
    console.log('%cPage1 beforeCreate', 'color: #94FBAB');
  },
  created() {
    console.log('%cPage1 created', 'color: #94FBAB');
  },
  onLoad() {
    console.log('%cPage1 onLoad', 'color: #94FBAB');
  },
  onShow() {
    console.log('%cPage1 onShow', 'color: #94FBAB');
  },
  onReady() {
    console.log('%cPage1 onReady', 'color: #94FBAB');
  },
  onHide() {
    console.log('%cPage1 onHide', 'color: #94FBAB');
  },
  onUnload() {
    console.log('%cPage1 onUnload', 'color: #94FBAB');
  },
  beforeMount() {
    console.log('%cPage1 beforeMount', 'color: #94FBAB');
  },
  mounted() {
    console.log('%cPage1 mounted', 'color: #94FBAB');
  },
  beforeUpdate() {
    console.log('%cPage1 beforeUpdate', 'color: #94FBAB');
  },
  updated() {
    console.log('%cPage1 updated', 'color: #94FBAB');
  },
  beforeDestroy() {
    console.log('%cPage1 beforeDestroy', 'color: #94FBAB');
  },
  destroyed() {
    console.log('%cPage1 destroyed', 'color: #94FBAB');
  },
}
</script>

<style scoped>
.userinfo {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.userinfo-avatar {
  width: 128rpx;
  height: 128rpx;
  margin: 20rpx;
  border-radius: 50%;
}

.userinfo-nickname {
  color: #aaa;
}

.usermotto {
  margin-top: 150px;
}

.form-control {
  display: block;
  padding: 0 12px;
  margin-bottom: 5px;
  border: 1px solid #ccc;
}

</style>
