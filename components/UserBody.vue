<template>
  <div class="body">
    <div class="container no-padding">
      <div>
        <div class="d-flex justify-content-center align-middle">
          <div class="card" style="width: 450px; padding: 30px; margin-top: 6rem; margin-left: 1rem; margin-right: 1rem;">
            <div style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
              정보 수정
            </div>
            <div class="form-group">
              <small>아이디</small>
              <input type="text" class="form-control" id="userId" readonly value="admin@naver.com">
              <!--            <small id="emailHelp" class="form-text text-muted">으하하하하하</small>-->
            </div>
            <div class="form-group">
              <small>새로운 비밀번호</small>
              <input type="password" class="form-control" id="password" placeholder="">
            </div>
            <div class="form-group">
              <small>새로운 비밀번호 확인</small>
              <input type="password" class="form-control" id="passwordCheck" placeholder="">
            </div>
            <div class="form-group">
              <small>닉네임</small>
              <input type="text" class="form-control" id="nick" placeholder="">
            </div>
            <button type="submit" class="btn btn-info" style="margin-top: 1rem; margin-bottom: 1rem;">저장</button>
            <button type="submit" class="btn btn-warning" style="">
              탈퇴
            </button>
            <a href="/regist">
              <button type="submit" class="btn btn-danger" style="width: 100%;margin-top: 1rem;">
                취소
              </button>
            </a>
          </div>
        </div>
      </div>
      <div>
        <div class="d-flex justify-content-center align-middle">
          <div class="card" style="width: 450px; padding: 30px; margin-top: 3rem; margin-left: 1rem; margin-right: 1rem;">
            <div style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
              사진 수정
            </div>
            <div class="form-group">
              <small>사진</small>
<!--              <input type="file" class="form-control" id="userId" readonly value="admin@naver.com">-->
              <!--            <small id="emailHelp" class="form-text text-muted">으하하하하하</small>-->
              <div class="input-group">
                <div class="custom-file">
                  <input type="file" class="custom-file-input" id="inputGroupFile04" aria-describedby="inputGroupFileAddon04">
                  <label class="custom-file-label" for="inputGroupFile04">파일 선택</label>
                </div>
                <div class="input-group-append">
                  <button class="btn btn-dark" type="button" id="inputGroupFileAddon04">업로드</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "UserBody"
    }
</script>

<style scoped>
  .body {
    margin-top: 1rem;
    /*margin-bottom: 1rem;*/
  }
</style>
