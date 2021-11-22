<template>
  <div>
    <div class="d-none d-lg-block">
      <header class="header-menu">
        <b-container fluid>
          <b-row>
            <b-col lg="5" class="text-left">
              <div class="pl-3">
                <b-img src="~/../src/assets/images/logo.png" fluid></b-img>
              </div>
            </b-col>
            <b-col lg="7" class="text-right">
              <ul class="menu-items">
                <li>Show All Tyres</li>
                <li>Find a Dealer</li>
                <li>Guides & Videos</li>
                <li>Go with</li>
                <li>Service & Help</li>
              </ul>
            </b-col>
          </b-row>
        </b-container>
      </header>
    </div>
    <div class="d-block d-lg-none">
      <header class="mobile-header-menu">
        <b-container fluid>
          <b-row>
            <b-col cols="7">
              <b-img src="~/../src/assets/images/logo.png" fluid></b-img>
            </b-col>
            <b-col cols="5" class="text-right">
              <b-icon
                v-b-toggle.sidebar-1
                icon="list"
                font-scale="2"
                style="vertical-align: middle"
              ></b-icon>
            </b-col>
          </b-row>
        </b-container>
      </header>
    </div>
    <b-sidebar
      id="sidebar-1"
      title="Sidebar"
      size="large"
      no-header
      shadow
      width="100%"
      sidebar-class="mobile-menu-sidebar"
    >
      <b-list-group>
        <b-list-group-item>
          <b-row>
            <b-col cols="9" class="text-left"> Show All Tyres </b-col>
            <b-col cols="3" class="text-right">
              <b-icon
                icon="chevron-right"
                font-scale="1.5"
                style="vertical-align: middle"
              ></b-icon>
            </b-col>
          </b-row>
        </b-list-group-item>
        <b-list-group-item>
          <b-row>
            <b-col cols="9" class="text-left"> SERVICE & HELP </b-col>
            <b-col cols="3" class="text-right">
              <b-icon
                icon="chevron-right"
                font-scale="1.5"
                style="vertical-align: middle"
              ></b-icon>
            </b-col>
          </b-row>
        </b-list-group-item>
        <b-list-group-item>
          <b-row>
            <b-col cols="9" class="text-left"> FIND A DEALER </b-col>
            <b-col cols="3" class="text-right">
              <b-icon
                icon="chevron-right"
                font-scale="1.5"
                style="vertical-align: middle"
              ></b-icon>
            </b-col>
          </b-row>
        </b-list-group-item>
        <b-list-group-item>
          <b-row>
            <b-col cols="9" class="text-left">GUIDES & VIDEOS </b-col>
            <b-col cols="3" class="text-right">
              <b-icon
                icon="chevron-right"
                font-scale="1.5"
                style="vertical-align: middle"
              ></b-icon>
            </b-col>
          </b-row>
        </b-list-group-item>
        <b-list-group-item>
          <b-row>
            <b-col cols="9" class="text-left"> GO WITH  </b-col>
            <b-col cols="3" class="text-right">
              <b-icon
                icon="chevron-right"
                font-scale="1.5"
                style="vertical-align: middle"
              ></b-icon>
            </b-col>
          </b-row>
        </b-list-group-item>
      </b-list-group>
    </b-sidebar>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
