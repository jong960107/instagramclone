<template lang="">
    <div id="mainWrapper">
      <div id="sectionImg">
        <div id="images">
          <img src="image1" alt="">
          <img src="image2" alt="">
          <img src="image3" alt="">
        </div>
    </div>
        <div id="section">
        <div id="signInWrapper">
          <h1>Instagram</h1>
          <input type="text" @model="username" placeholder="전화번호,사용자이름,이메일">
          <input type="text" @model="password" placeholder="비밀번호">
          <button type="submit">로그인</button>
          <div id="facebookLogin"></div>
        </div>
        </div>
        </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>