<template>
  <div class="row middle">
    <div class="col-xl-12 d-none d-sm-block">
      <div class="col-xl-12 common">
        스터디 그램은 누구나 사용 할 수 있습니다
      </div>
      <div class="col-xl-12 common" style="color: #b2b2b2; font-weight: bolder;">
        스터디 시작하기
      </div>
      <div class="col-xl-12 common" style="color:#6c3ad3; font-weight: bolder;">
        스터디 관리하기
      </div>
      <div class="col-xl-12 common"
           style="font-weight: bold; color: #b2b2b2; font-size: 0.85rem;letter-spacing: -1px; margin-top: 1rem;">
        스터디그램을 사용해 나만의 스터디를 만들어 보세요.
      </div>
      <div class="col-xl-12 common">
        <a href="/">
          <b-button class="study-start-btn" size="lg" variant="primary"
                    style="width: 17rem; height: 3.7rem; margin-top: 3.5rem; font-weight: bolder;">스터디 시작하기
          </b-button>
        </a>
      </div>
    </div>
    <div class="col-12 d-block d-sm-none" style="padding: 0px;">
      <div class="col-xl-12 common mobile">
        스터디 그램은 누구나 사용 할 수 있습니다
      </div>
      <div class="col-xl-12 common mobile" style="color: #b2b2b2; font-weight: bolder;">
        스터디 시작하기
      </div>
      <div class="col-xl-12 common mobile" style="color:#6c3ad3; font-weight: bolder;">
        스터디 관리하기
      </div>
      <div class="col-xl-12 common mobile"
           style="font-weight: bold; color: #b2b2b2; font-size: 0.75rem;letter-spacing: -1px; margin-top: 1rem;">
        스터디그램을 사용해 나만의 스터디를 만들어 보세요.
      </div>
      <div class="col-xl-12 common">
        <a href="/">
          <b-button class="study-start-btn" size="lg" variant="primary"
                    style="width: 17rem; height: 3.7rem; margin-top: 2.5rem; font-weight: bolder;">스터디 시작하기
          </b-button>
        </a>
      </div>
    </div>

  </div>
</template>

<script>

  export default {
    name: "Middle"
  }
</script>

<style scoped>
  @import url('https://cdn.rawgit.com/moonspam/NanumSquare/master/nanumsquare.css');
  @import "../../assets/css/common.css";

  .middle {
    font-size: 2.5rem;
    padding-top: 3.5rem;
    /*font-weight: bold;*/
    font-weight: lighter;
    font-family: 'NanumSquare', sans-serif !important;
    letter-spacing: -0.2rem;
  }

  .mobile {
    font-size: 1.31rem;
    /*padding-top: 3.5rem;*/
    /*font-weight: bold;*/
    font-weight: lighter;
    font-family: 'NanumSquare', sans-serif !important;
    letter-spacing: -0.2rem;
  }

  .common {
    text-align: center;
  }

  .study-start-btn {
    background-color: #6c3ad3;
  }

  button.study-start-btn:hover,
  button.study-start-btn:active,
  button.study-start-btn:focus {
    background-color: #845ef7 !important;
  }
</style>
