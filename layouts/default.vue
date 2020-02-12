<template>
 <div class="app-layout">
   <div class="sidebar">
     <p>チャンネル一覧</p>
     <p>#random</p>
     <p>#general</p>
     <p>#i-sys</p>
   </div>
   <div class="main-content">
     <nuxt />
   </div>
 </div>
</template>

<style>
.app-layout {
 display: flex;
}

.sidebar {
 width: 300px;

 /* ここを変更 */
 background: #4A4141;

 height: 100vh;
 padding: 20px;
}

.sidebar p {
  color: #DDDDDD;
  padding-top: 4px;
}

.main-content {
 width: 100%;

 /* ここを変更 */
 background: #F1F1F1;

 height: 100vh;
}
</style>