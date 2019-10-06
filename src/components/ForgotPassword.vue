<template>
  <section class="form-elegant">
    <mdb-row>
      <mdb-col md="5">
        <mdb-card>
          <dir id="bigdiv">
            <img
              src="https://images.alphacoders.com/124/thumb-1920-12453.jpg"
              width="2000"
              height="1500"
            />
          </dir>

          <div id="innerlogin">
            <h1>Forgot Password</h1>
            <p>Welcome back,please login to your account.</p>
          </div>
          <p id="email">email</p>
          <div id="inneremail">
            <i class="fas fa-user prefix"></i>
            <div id="inneremail2">
              <mdb-input type="email" />
            </div>
          </div>
          <dir id="Register1">
            <button type="register" class="btn btn-primary">
              <a
                href="https://mdbootstrap.com/docs/vue/layout/grid-usage/"
                class="blue-text ml-1"
              >confirm</a>
            
            
            </button>
          </dir>
        </mdb-card>
      </mdb-col>
    </mdb-row>
  </section>
</template>

<script>
import {
  mdbRow,
  mdbCol,
  mdbCard,
  mdbCardBody,
  mdbInput,
  mdbBtn,
  mdbIcon,
  mdbModal,
  mdbModalBody,
  mdbModalFooter
} from "mdbvue";

export default {
  name: "FormsPage",
  components: {
    mdbRow,
    mdbCol,
    mdbCard,
    mdbCardBody,
    mdbInput,
    mdbBtn,
    mdbIcon,
    mdbModal,
    mdbModalBody,
    mdbModalFooter
  },
  data() {
    return {
      showModal: false
    };
  }
};
</script>

<style>
.form-elegant .font-small {
  font-size: 0.8rem;
}

.form-elegant .z-depth-1a {
  -webkit-box-shadow: 0 2px 5px 0 rgba(55, 161, 255, 0.26),
    0 4px 12px 0 rgba(121, 155, 254, 0.25);
  box-shadow: 0 2px 5px 0 rgba(55, 161, 255, 0.26),
    0 4px 12px 0 rgba(121, 155, 254, 0.25);
}

.form-elegant .z-depth-1-half,
.form-elegant .btn:hover {
  -webkit-box-shadow: 0 5px 11px 0 rgba(85, 182, 255, 0.28),
    0 4px 15px 0 rgba(36, 133, 255, 0.15);
  box-shadow: 0 5px 11px 0 rgba(85, 182, 255, 0.28),
    0 4px 15px 0 rgba(36, 133, 255, 0.15);
}
#innerlogin {
  position: absolute;
  left: 1100px;
  top: 250px;
  margin-left: -100px;
}
#inneremail {
  position: absolute;
  left: 1000px;
  top: 400px;
  width: 20px;
  padding: 0.5px;
  border: 1px solid rgba(22, 22, 22, 0.24);
  background-color: rgb(255, 255, 255);
}
#inneremail2 {
  position: absolute;
  left: 118px;
  top: -0.75px;
  margin-left: -100px;
}
#email {
  position: absolute;
  left: 1100px;
  top: 358px;
  margin-left: -100px;
}
#innerpasswork {
  position: absolute;
  left: 1100px;
  top: 450px;
  margin-left: -100px;
  width: 20px;
  padding: 0.5px;
  border: 1px solid rgba(22, 22, 22, 0.24);
  background-color: rgb(255, 255, 255);
}
#innerpasswork2 {
  position: absolute;
  left: 118px;
  top: -0.75px;
  margin-left: -100px;
}
#passwork {
  position: absolute;
  left: 1100px;
  top: 408px;
  margin-left: -100px;
}
#RememberMe {
  position: absolute;
  left: 1100px;
  top: 480px;
  margin-left: -100px;
}
#ForgotPassword {
  position: absolute;
  left: 1302px;
  top: 460px;
  margin-left: -100px;
}
#orSignin {
  position: absolute;
  left: 1200px;
  top: 510px;
  margin-left: -100px;
}
#orSigninicon {
  position: absolute;
  left: 1200px;
  top: 550px;
  margin-left: -100px;
}
#Submit {
  position: absolute;
  left: 1325px;
  top: 600px;
  margin-left: -100px;
}
#Register1 {
  position: absolute;
  left: 1060px;
  top: 425px;
  margin-left: -100px;
}
#bigdiv {
  position: absolute;
  left: -50px;
  top: -50px;
}
</style>
