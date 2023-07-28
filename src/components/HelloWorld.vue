<script setup lang="ts">
</script>

<template>
  <div class="card">
    <div class="head">
      <div class="app-name">
        <img class="logo" src="/logo.png"/>
        <span class="voice">玩兔语音</span>
      </div>
      <div class="button">
        <!-- <button class="download">下载APP</button>  -->
        <img src="../assets/download.png" class="download"/>
      </div>
    </div>
    <img src="../assets/banner.png" class="banner"/>
    <img src="../assets/phone.png" class="phone"/>
    <img src="../assets/downloadBtn.png" class="downloadBtn"/>
  </div>

</template>

<style scoped>
*{
  padding: 0;
  margin: 0;
}
.card{
  width: 100%;
  height: 100%;
  position: absolute;
    left: 0;
    bottom: 0;
  background: linear-gradient(#E0D5FB, #FADAE9);
}
.head{
  /* width:100%; */
  height: 10%;
  background-color: aliceblue;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  display: flex;
  align-items:center;
  justify-content: space-between;
  margin-bottom: 40px;
}
.app-name{
  display: flex;
  align-items: center;
  margin-left: 20px;
  
}

.logo{
  widows: 40px;
  height: 40px;
}

.voice{
  margin-left: 10px;
  font-size: 20px;
  font-weight: bolder;
  letter-spacing: 2px;
}
.button{
  margin-right: 20px;
}
.download{
  width: 120px;
  height: 40px;
  /* background-color: #8C7EFF;
  border-radius:20px;
  padding: 5px 15px;
  color: aliceblue;
  font-weight: bold;
  letter-spacing: 1px; */
}

.banner{
  max-width:80%;
  max-height: 100px;
  margin-bottom: 50px;
}
.phone{
  max-width: 100%;
  max-height: 100%;
  margin-bottom: 10px;
}

.downloadBtn{
  max-width: 80%;
  max-height: 100%;
}
</style>
