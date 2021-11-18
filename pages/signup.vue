<template>
  <div>
    <v-row>
      <v-container>
        <v-form>
          <v-col
            style="margin-top:-1rem;"
            cols="12"
            sm="6"
            md="4"
          />
          <v-card
            style="border-radius : 2rem;"
            class="mx-auto"
            max-width="380"
            color="white"
          >
            <v-card-text>
              <div style="color : #324875; margin-bottom:-2rem;">
                <br><h3>Sign up bank account</h3><br><br>
                <v-col
                  cols="12"
                  sm="6"
                  md="4"
                >
                  <div class="ss">
                    <v-text-field
                      label="Your Name"
                      color="black"
                      outlined
                      dark
                    />
                  </div>
                  <div class="ss">
                    <v-text-field
                      label="Bank Account"
                      color="black"
                      outlined
                      dark
                    />
                  </div>
                  <div class="ss">
                    <v-text-field
                      label="Mobile phone number"
                      color="black"
                      outlined
                      dark
                    />
                  </div>
                  <div class="ss">
                    <v-text-field
                      label="Email"
                      color="black"
                      outlined
                      dark
                    />
                  </div>
                  <div class="ss">
                    <v-text-field
                      label="Password"
                      color="black"
                      outlined
                      dark
                      append-icon="mdi-eye"
                    />
                  </div>
                </v-col>
              </div>

              <div
                class="
                      use"
                style="color : black;"
              >
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Use 6 characters with a mix of numbers<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; and letters</p>
              </div>
              <div class="check">
                <v-checkbox
                  style="border-color:black;"
                  label="black"
                  color="black"
                />
              </div>
              <div class="check2">
                <p>By signin up,you agree to<br>Bank's Term of Use & Privacy Policy.</p>
              </div>
              <div class="btn">
                <v-btn class="btn1">
                  <p> SIGN IN</p>
                </v-btn>
                <div class="or">
                  <p>OR</p>
                </div>
                <v-btn class="btn2" color="white">
                  <p> CANCEL</p>
                </v-btn>
              </div>
              <div class="al" style="color : black;">
                <p>Already signed up ? <a href="#">Log in</a></p>
              </div>
            </v-card-text>
          </v-card>
        </v-form>
      </v-container>
    </v-row>
    <br>
  </div>
</template>

<style>
.mx-auto {
  border-radius: 3rem;
}
.ss{
  margin-top: -20px;
}
.v-text-field--outlined fieldset{
  color: #27272c !important;
  width: 20rem;
  height: 3.2rem;
}
.v-text-field--outlined label{
  color: #27272c !important;
  font-size: 13px;
  margin-top: -3px;
}
.use p{
  color: rgb(104, 104, 177);
  margin-top: -1rem;
  text-align: left;
}
.check {
  padding-left: 2rem;
  width: 4rem;
}
.check2{
  margin-top: -3rem;
}
.check2 p{
  color: #000000;
  text-align: left;
  margin-left: 5rem;
}
.btn{
  margin-left: 4rem;
}
.btn1{
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-top: 20px;
  margin-left: -15rem;
}
.btn1 p{
  color: black;
  margin-bottom: -4px;

}
.btn2{
  margin-top: -70px;
  margin-left: 7rem;
}
.btn2 p{
  margin-top: 20px;
}
.btn p{
  color: #000000;
}
.or {
  margin-left: -4rem;
  margin-top: -2rem;
}

</style>
