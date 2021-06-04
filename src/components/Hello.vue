<template>
  <div class="hello">
    <div>
      <img alt="plc logo" src="../assets/img/plc.png">
      <div class="col-md-12">
      <img class="bg" alt="plc logo" src="../assets/img/background.jpg" height="90%" width="100%">
      <div class="text-pos center row col-md-12">
        <div class="col-md-6">
          <div class="container col-md-12">
            <div class="container paddingtl">
        <h1 class="text-white">THIS A GREAT SYSTEM DESIGN FOR YOU</h1>
        <div>
          <button type="button" class="btn btn-primary readmore">Read More</button>
        </div>
        </div>
        </div>
        </div>
        <div class="d-flex row col-md-6">
          <div class="card col-md-12 ind">
        <div class="containter col-md-12">
          <div class="flex row" align="center">
            <img alt="plc logo" src="../assets/img/plc.png">
          </div>
          <div class="col-md-12 logaccount" align="center">
            <p class="font-weight-regular">Login to your Account</p>
          </div>
          <div class="container">
          <form method="post">
            <div class="txt_field">
              <input type="text" required placeholder="Username">
            </div>
            <div class="txt_field">
              <input  type="password" required id="pass" placeholder="Password">
              <span>
              <i class="flex row fa fa-eye" id="eye"></i>
              </span>
            </div>
            <button type="button" class="btn btn-primary col-md-12 bgcolor">Login</button>
            <div class="flex row signup">
              <p > Not a member? <a href="#">Create Account</a></p>
            </div>
            <hr class="solid">
            <div class="flex row" align="center">
              <p>Privacy Policy <i class="fa fa-circle"></i> Terms of use</p>
            </div>
          </form>
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
  name: 'Home',
  props: {
    msg: String
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cons {
  transform: translate(50%, 50%);
}
.paddingtl {
  padding-left: 45%;
  padding-top: 20%;
}
.bg {
  position: absolute;
}
.text-pos {
  z-index: 2;
  position: absolute;
  top: 45%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.center {
  position: absolute;
  top: 50%;
  left: 50%;
  /* width: 400px; */
  transform: translate(-50%, -50%);
}
.text-white {
  color: white;
}
.readmore {
  background-color: #FF6347;
}
form .txt_field {
  position: relative;
  border-bottom: 2px solid #adadad;
  margin: 30px 0;
}
.txt_field input {
  width: 100%;
  padding: 0 5px;
  height: 40px;
  font-size: 16px;
  border: none;
  background: none;
  outline: none;
}
.txt_field label {
  position: absolute;
  top: 50%;
  left: 5px;
  color: #adadad;
  transform: translate(-50%);
  font-size: 16px;
  pointer-events: none;
}
.signup {
  padding-top: 20px;
  padding-bottom: 60px;
}
hr.solid {
  border-top: 3px solid #2E86C1;
}
.bgcolor {
  background-color:#2E86C1
}
p {
  color: #2E86C1
}
.logaccount {
  padding-top: 20px;
}
span {
  position: absolute;
  right: 15px;
  transform: translate(0, -25%);
  top: 50%;
  cursor: pointer;
}
.fa {
  font-size: 20px;
  color: #2E86C1;
}
.ind {
  width: 50%;
  margin-left: 10%;
}
</style>
