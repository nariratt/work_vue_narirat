<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div
          class="pa-7 white rounded-circle d-inline-block"
        >
          <!-- <v-icon large color="#4B6587">
            mdi-cloud-upload
          </v-icon> -->
        </div>
      </v-col>
    </v-row>
    <h1 style="margin-top:3rem">
      Home Room
    </h1>
    <h3>MOBILE APP</h3>
    <v-form>
      <v-container>
        <v-row>
          <v-col
            style="margin-top:3rem;"
            cols="12"
            sm="6"
            md="4"
          >
            <v-menu transition="slide-y-transition">
              <template #activator="{ on, attrs }">
                <v-text-field
                  label="PLEASE ENTER YOUR PASSWORD"
                  placeholder="PASSWORD"
                  filled
                  rounded
                  dense
                  v-bind="attrs"
                  v-on="on"
                />
              </template>
              <div class="box">
                <v-col>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      1
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      2
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      3
                    </v-btn>
                  </v-col>
                </v-col>
                <v-col>
                  <v-col class="d-flex justify-center">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      4
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      5
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      6
                    </v-btn>
                  </v-col>
                </v-col>
                <v-col>
                  <v-col class="d-flex justify-center mb-6">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      7
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      8
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      9
                    </v-btn>
                  </v-col>
                  <v-col>
                    <v-col class="d-flex justify-center">
                      <v-btn
                        class="mx-2"
                        fab
                        dark
                        color="primary"
                      >
                        0
                      </v-btn>
                      <v-btn
                        class="mx-2"
                        fab
                        dark
                        color="warning"
                      >
                        <i class="fas fa-times" />
                      </v-btn>
                    </v-col>
                  </v-col>
                </v-col>
              </div>
            </v-menu>

            <v-btn
              class="btn1"
            >
              <span class="txt1">LOGIN</span>
            </v-btn>
            <p>Forgot password?</p>
            <p>New to Bank Apps? Sign Up</p>
          </v-col>
        </v-row>
      </v-container>
    </v-form>
  </div>
</template>

<style>
.pa-7{
  margin-top: 140px ;
}
h3 {
  margin-bottom: 80px;
}
.txt1{
  color: rgb(80, 67, 49);
}
.btn1{
  background: linear-gradient(#F0E5CF,#FFE1AF);
  margin-bottom: 50px;
}
.box{
  background-color: whitesmoke;
  padding: 5px;
  border-radius: 25px;
  font-size: 18px;
}
.d-flex{
  margin-top: -10px;
  padding: 1px;
}
</style>
