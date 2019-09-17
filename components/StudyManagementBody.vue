<template>
  <div class="body">
    <div class="container no-padding">
      <div>
        <div class="d-flex justify-content-center align-middle">
          <div class="card"
               style="width: 100%; padding: 30px; margin-top: 2rem; margin-left: 1rem; margin-right: 1rem;">
            <div
              style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
              관리하는 스터디
            </div>
            <div style="margin-top: 1rem;">
              <div class="card w-100 text-center">
                <div class="card-body">
                  <h5 class="card-title">막놀자 스터디</h5>
                  <p class="card-text">주제 : 막놀기</p>
                  <div class="d-none d-xl-block">
                    <a href="#" class="btn btn-info w-25">자세히 보기</a>
                  </div>
                  <div class="d-block d-sm-none">
                    <a href="#" class="btn btn-info w-100">자세히 보기</a>
                  </div>
                </div>
              </div>
            </div>
            <div style="margin-top: 1rem;">
              <div class="card w-100 text-center">
                <div class="card-body">
                  <h5 class="card-title">K8S 스터디</h5>
                  <p class="card-text">주제 : K8S 마스터</p>
                  <div class="d-none d-xl-block">
                    <a href="#" class="btn btn-info w-25">자세히 보기</a>
                  </div>
                  <div class="d-block d-sm-none">
                    <a href="#" class="btn btn-info w-100">자세히 보기</a>
                  </div>                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="d-flex justify-content-center align-middle">
          <div class="card"
               style="width: 100%; padding: 30px; margin-top: 2rem; margin-left: 1rem; margin-right: 1rem;">
            <div
              style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
              가입한 스터디
            </div>

            <div style="margin-top: 1rem;">
              <div class="card w-100 text-center">
                <div class="card-body">
                  <h5 class="card-title">Vue.js 스터디</h5>
                  <p class="card-text">주제 : Vue.js</p>
                  <div class="d-none d-xl-block">
                    <a href="#" class="btn btn-info w-25">자세히 보기</a>
                  </div>
                  <div class="d-block d-sm-none">
                    <a href="#" class="btn btn-info w-100">자세히 보기</a>
                  </div>                </div>
              </div>
            </div>
            <div style="margin-top: 1rem;">
              <div class="card w-100 text-center">
                <div class="card-body">
                  <h5 class="card-title">리액트 스터디</h5>
                  <p class="card-text">주제 : React</p>
                  <div class="d-none d-xl-block">
                    <a href="#" class="btn btn-info w-25">자세히 보기</a>
                  </div>
                  <div class="d-block d-sm-none">
                    <a href="#" class="btn btn-info w-100">자세히 보기</a>
                  </div>                </div>
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
    name: "StudyManagementBody"
  }
</script>

<style scoped>
  .body {
    margin-top: 4rem;
    /*margin-bottom: 1rem;*/
  }
</style>
