<template>
  <div class="loginBody">
    <div class="container no-padding">
      <div class="d-flex justify-content-center align-middle">
        <div class="card" style="width: 450px; padding: 30px; margin-top: 6rem; margin-left: 1rem; margin-right: 1rem;">
          <div
            style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
            로그인
          </div>
          <div class="form-group">
            <small>아이디</small>
            <input v-model="id" type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
                   pattern="[a-zA-Z]{3,}@[a-zA-Z]{3,}[.]{1}[a-zA-Z]{2,}[.]{1}[a-zA-Z]{2,}[.]{1}[a-zA-Z]{2,}" required
                   placeholder="Your Email">
            <!--            <small id="emailHelp" class="form-text text-muted">으하하하하하</small>-->
          </div>
          <div class="form-group">
            <small>비밀번호</small>
            <input v-model="pw" type="password" class="form-control" id="exampleInputPassword1" placeholder="">
          </div>
          <button  v-on:click="login" type="submit" class="btn btn-primary" style="margin-top: 1rem; margin-bottom: 1rem;">로그인</button>
          <a href="/regist">
            <button type="submit" class="btn btn-success" style="width: 100%">
              회원가입
            </button>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import axios from 'axios'

  export default {
    name: "LoginBody",
    data: function () {
      return {
        id: '',
        pw: '',
      }
    },
    methods: {
      login: function (event) {
        axios.post('https://studygram.co.kr/api/login',
          {
            id: this.id,
            pw: this.pw,
          }
        ).then((res) => {
          // alert("이메일에서 인증을 해주세요.")
          // console.log(res)
          localStorage.setItem('token', res.data.token)
          location.href = "/"

        })
          .catch((err) => {
            alert(err.response.data.msg)
          })
      }
    }
  }
</script>

<style scoped>
  .loginBody {
    margin-top: 1rem;
    /*margin-bottom: 1rem;*/
  }
</style>
