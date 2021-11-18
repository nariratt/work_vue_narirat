<template>
  <div>
    <v-row>
      <v-container>
        <v-form>
          <v-col
            style="margin-top:3rem;"
            cols="12"
            sm="6"
            md="4"
          />
          <!-- <v-card
            class="mx-auto"
            max-width="380"
            color="white"
          > -->
          <v-card-text>
            <div style="color : #324875;">
              <br><h3>Sign up bank account</h3><br>
            </div>
          </v-card-text>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-text-field
              label="Your Name"
              color="black"
              outlined
              dark
            />
            <v-text-field
              label="Bank Account"
              color="black"
              outlined
              dark
            />
            <v-text-field
              label="Mobile phone number"
              color="black"
              outlined
              dark
            />
            <v-text-field
              label="Email"
              color="black"
              outlined
              dark
            />
            <v-text-field
              label="Password"
              color="black"
              outlined
              dark
            />
          </v-col>
          <div class="use" style="color : black;">
            <p>Use 6 characters with a mix of numbers&nbsp;&nbsp;&nbsp;and letters</p>
          </div>
          </v-card>
        </v-form>
      </v-container>
    </v-row>
  </div>
</template>

<style>
.mx-auto {
  border-radius: 3rem;
}
.v-text-field--outlined fieldset{
  color: #27272c !important;
  width: 20rem;
  height: 3.5rem;
  margin-bottom: -20px;
}
.v-text-field--outlined label{
  color: #27272c !important;
}

</style>
