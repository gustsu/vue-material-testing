<template>
  <div class="home">
    <div class="md-layout-container">
      <div class="md-layout md-gutter">
        <div class="md-layout-item md-medium-size-50 md-small-size-100">
          <md-card>
            <md-card-header>
              <div class="md-title">Card without hover effect</div>
            </md-card-header>

            <md-card-content>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio
              itaque ea, nostrum odio. Dolores, sed accusantium quasi non.
            </md-card-content>

            <md-card-actions>
              <md-button>Action</md-button>
              <md-button>Action</md-button>
            </md-card-actions>
          </md-card>
        </div>
        <div class="md-layout-item md-medium-size-50 md-small-size-100">
          <md-card>
            <md-card-header>
              <div class="md-title">Card without hover effect</div>
            </md-card-header>

            <md-card-content>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio
              itaque ea, nostrum odio. Dolores, sed accusantium quasi non.
            </md-card-content>

            <md-card-actions>
              <md-button>Action</md-button>
              <md-button>Action</md-button>
            </md-card-actions>
          </md-card>
        </div>
      </div>
    </div>

    <md-speed-dial md-direction="top">
      <md-speed-dial-target>
        <md-icon class="md-primary">add</md-icon>
      </md-speed-dial-target>

      <md-speed-dial-content>
        <md-button class="md-icon-button">
          <md-icon>attach_money</md-icon>
        </md-button>

        <md-button class="md-icon-button">
          <md-icon>cloud</md-icon>
        </md-button>
      </md-speed-dial-content>
    </md-speed-dial>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home"
};
</script>

<style lang="scss" scoped>
.md-speed-dial {
  position: absolute;
  bottom: 20px;
  right: 20px;
}
</style>
