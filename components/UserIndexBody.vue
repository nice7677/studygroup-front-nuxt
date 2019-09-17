<template>
    <div class="body">
      <div class="container no-padding">
        <div class="d-flex justify-content-center align-middle">
          <div class="card" style="width: 450px; padding: 30px; margin-top: 6rem; margin-left: 1rem; margin-right: 1rem;">
            <div style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
              비밀번호 확인
            </div>
            <div class="form-group">
              <small>비밀번호</small>
              <input type="password" class="form-control" id="exampleInputPassword1" placeholder="">
            </div>
            <button type="submit" class="btn btn-info" style="margin-top: 1rem; margin-bottom: 1rem;">확인</button>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "UserIndexBody"
    }
</script>

<style scoped>
  .body {
    margin-top: 4rem;
    /*margin-bottom: 1rem;*/
  }
</style>
