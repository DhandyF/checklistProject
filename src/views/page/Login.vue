<template>
  <div>
    <div id="container">
      <vs-row vs-justify="center" vs-align="center" vs-w="12">
        <vs-col vs-xs="12" vs-sm="5" vs-lg="5">
          <vs-card>
            <vs-row vs-w="12">
              <vs-col class="mb-2" vs-xs="12" vs-sm="12" vs-lg="12">
                <h2>Login</h2>
              </vs-col>
            </vs-row>
            <vs-row>
              <vs-col class="d-flex flex-column" vs-xs="12" vs-sm="12" vs-lg="12">
                <vs-input class="mb-1 mx-auto w-50" icon="mail" label-placeholder="Email"></vs-input>
                <vs-input class="mb-1 mx-auto w-50" icon="lock" label-placeholder="Password" type="password"></vs-input>
                <vs-divider />
                <div>
                  <vs-button class="w-50 mb-2" color="primary" type="filled">Login</vs-button>
                  <p class="mb-1 register">Register</p>
                </div>
              </vs-col>
            </vs-row>
          </vs-card>
        </vs-col>
      </vs-row>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
        
    }
  },
}
</script>

<style lang="scss" scoped>
  #container {
    display: flex;
    margin: 0;
    padding: 0;
    height: 657px;
    // align-items: center;
  }
  .form-login{
    flex-direction: column;
  }
  .register{
    cursor: pointer;
    color: lightgray;
  }
  .register:hover{
    text-decoration: underline;
    color: gray;
  }
</style>