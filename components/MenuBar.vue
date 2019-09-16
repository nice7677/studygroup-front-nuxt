<template>
  <div class="no-margin fixed-top">
    <div class="header no-margin">
      <div class="container no-padding">
        <div class="row no-margin">
          <div class="col-5 col-xl-2 col-lg-2">
            <a href="/"
               style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold;">Studygram</a>
          </div>
          <div class="col-xl-4 col-lg-4 d-none d-sm-block left no-padding">
            <a href="/study/join" style="color: #8a8a8a; letter-spacing: -0.5px;">스터디찾기</a>
            <a href="/study/manager" style="color: #8a8a8a; letter-spacing: -0.5px;margin-left: 1.2rem;">스터디관리</a>
          </div>
          <div class="col-xl-6 col-lg-6 d-none d-sm-block right no-padding">
            <a href="/howtouse" style="color: #8a8a8a; letter-spacing: -2px;margin-left: 1rem;">이용안내</a>
            <a href="/notice" style="color: #8a8a8a; letter-spacing: -2px;margin-left: 1rem;">공지사항</a>
            <a href="/login" style="color: #8a8a8a; letter-spacing: -2px;margin-left: 1rem;">
              <button type="button" class="btn btn-secondary"
                      style="font-size: 0.85rem;letter-spacing: -2px; width: 75px">로그인
              </button>
            </a>
            <a href="/login" style="color: #8a8a8a; letter-spacing: -2px;margin-left: 1rem;">
              <button type="button" class="btn btn-outline-secondary"
                      style="font-size: 0.85rem;letter-spacing: -2px; width: 75px">회원가입
              </button>
            </a>
          </div>
          <div class="col-7 d-block d-sm-none" style="text-align: right; padding-left: 0px;">
<!--            <a href="/study/join" style="font-weight: bold;font-size: 0.8rem;color: #8a8a8a; letter-spacing: -0.5px;">스터디찾기</a>-->
<!--            <a href="/study/manager"-->
<!--               style="font-weight: bold;font-size: 0.8rem;color: #8a8a8a; letter-spacing: -0.5px;margin-left: 1.2rem;">스터디관리</a>-->
            <div style="font-weight: bold; padding: 0px;" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
              <i class="fas fa-bars"></i>
<!--              <span class="navbar-toggler-icon"></span>-->
            </div>
          </div>
        </div>
        <div class="collapse" id="navbarToggleExternalContent">
          <div class="p-4" style="color: white; font-family: 'NanumSquare', sans-serif !important;font-size: 0.9rem;text-align: center;align-items: center;justify-content: center; font-weight: bold; background-color: #6c3ad3;">
            <div style="margin-bottom: 0.7rem;">스터디찾기</div>
            <div style="margin-bottom: 0.7rem;">스터디관리</div>
            <div style="margin-bottom: 0.7rem;">로그인</div>
            <div style="margin-bottom: 0.7rem;">회원가입</div>
            <div style="margin-bottom: 0.7rem;">이용안내</div>
            <div style="margin-bottom: 0.7rem;">공지사항</div>
            <div style="">스터디그램 이란?</div>
          </div>
        </div>
      </div>
    </div>
    <!--    <b-row>-->
    <!--      <b-col xs="12" lg="6">dddddd</b-col>-->
    <!--      <b-col xs="12" lg="6">dddddd</b-col>-->
    <!--    </b-row>-->
  </div>

</template>

<script>

  export default {
    name: "MenuBar",
    components: {
    },

  }
</script>

<style scoped>
  @import "../assets/css/common.css";
  @import url('https://fonts.googleapis.com/css?family=Gothic+A1&display=swap');
  @import url('https://fonts.googleapis.com/css?family=Encode+Sans+Expanded|Encode+Sans+Semi+Expanded|Lato|Quicksand|Righteous|Source+Sans+Pro&display=swap');
  @import url('https://cdn.rawgit.com/moonspam/NanumSquare/master/nanumsquare.css');


  .row {
    height: 4rem;
    align-items: center;
  }

  a {
    /*margin-left: 0.8rem;*/
    /*margin-right: 1.6rem;*/
    text-decoration: none;
    text-decoration: none !important;
    color: white;
    font-family: 'Gothic A1', sans-serif;
  }

  a:visited {
    text-decoration: none;
  }

  a:active {
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
    color: white;
  }

  .left {
    font-size: 0.90rem;
    font-weight: 777;
  }

  .right {
    font-size: 0.85rem;
    font-weight: 700;
    text-align: right;
  }

  .header {
    border-bottom: 1px solid #dbdbdb;
    /*z-index: 10;*/
    background: white;
  }
</style>
