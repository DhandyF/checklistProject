<template>
  <div>
    <div id="container">
      <vs-row vs-justify="center" vs-align="center" vs-w="12">
        <vs-col type="flex" vs-justify="center" vs-align="center" vs-xs="12" vs-sm="8" vs-lg="8">
          <vs-card>
            <vs-row vs-w="12">
              <vs-col vs-xs="hidden" vs-sm="hidden" vs-lg="6" vs-align="center">
                <img src="@/assets/images/login.png" alt="login">
              </vs-col>
            </vs-row>
            <!-- <div slot="header">
              <h3>
                Hello world !
              </h3>
            </div>
            <div>
              <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</span>
            </div>
            <div slot="footer">
              <vs-row vs-justify="flex-end">
                <vs-button type="gradient" color="danger" icon="favorite"></vs-button>
                <vs-button color="primary" icon="turned_in_not"></vs-button>
                <vs-button color="rgb(230,230,230)" color-text="rgb(50,50,50)" icon="settings"></vs-button>
              </vs-row>
            </div> -->
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
</style>