<template>
  <div class="loginBody">
    <div class="container no-padding">
      <div class="d-flex justify-content-center align-middle">
        <div class="card" style="width: 450px; padding: 30px; margin-top: 6rem; margin-left: 1rem; margin-right: 1rem;">
          <div style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
            회원가입
          </div>
          <div class="form-group">
            <small>아이디</small>
            <input type="email" class="form-control" id="email" aria-describedby="emailHelp" pattern="[a-zA-Z]{3,}@[a-zA-Z]{3,}[.]{1}[a-zA-Z]{2,}[.]{1}[a-zA-Z]{2,}[.]{1}[a-zA-Z]{2,}" required placeholder="Your Email">
            <!--            <small id="emailHelp" class="form-text text-muted">으하하하하하</small>-->
          </div>
          <div class="form-group">
            <small>비밀번호</small>
            <input type="password" class="form-control" id="password" placeholder="">
          </div>
          <div class="form-group">
            <small>닉네임</small>
            <input type="email" class="form-control" id="nick" aria-describedby="emailHelp" placeholder="">
            <!--            <small id="emailHelp" class="form-text text-muted">으하하하하하</small>-->
          </div>
          <button type="submit" class="btn btn-primary" style="margin-top: 1rem; margin-bottom: 1rem;">가입</button>
          <button type="submit" class="btn btn-warning">취소</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Register"
  }
</script>

<style scoped>
  .loginBody {
    margin-top: 1rem;
    /*margin-bottom: 1rem;*/
  }
</style>
