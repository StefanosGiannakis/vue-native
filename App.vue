<template>
  <view class="container">
  <Statusbar/>
  
  <Header title='My New App'/>

    <!-- <scroll-view :content-container-style="{width:'100%'}"> -->
    <HeaderImage/>
    <PurpleButton/>
    <!-- </scroll-view> -->
  </view>
</template>

<script>

import Statusbar from './components/Statusbar';
import Header from './components/Header';
import HeaderImage from './components/HeaderImage';
import PurpleButton from './components/PurpleButton';
import ScrollView from './components/ScrollView';

export default {
  components: { 
    Statusbar,
    Header,
    HeaderImage,
    PurpleButton,
    ScrollView
  }
}
</script>

<style>
.container {
  /* background-color: white; */
  /* align-items: center; */
  /* justify-content: center; */
  /* flex: 1; */
}
.text-color-primary {
  color: blue;
}
</style>

