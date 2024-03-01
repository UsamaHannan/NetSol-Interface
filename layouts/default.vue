<template>
  <div>
    <v-app>
      <div class="background">
        <!-- Container for layout -->
        <v-container>
          <v-row>
            <v-col>
              <!-- NetSol logo -->
              <img
                class="mt-3"
                src="../public/images/logo.png"
                width="120px"
                alt=""
              />
            </v-col>
            <!-- Column for the Regions button -->
            <v-col cols="12" md="2" sm="8">
              <div>
                <!-- Dropdown menu for Regions -->
                <v-menu>
                  <template v-slot:activator="{ props }">
                    <!-- Regions button -->
                    <v-btn
                      color="gradient"
                      class="text-white"
                      :style="{
                        backgroundImage:
                          'linear-gradient(to bottom, #0c8aee, #0442da)',
                      }"
                      v-bind="props"
                      rounded
                      size="large"
                      width="100%"
                      style="text-transform: none"
                    >
                      Regions
                    </v-btn>
                  </template>
                  <!-- List of regions in the dropdown -->
                  <v-list style="background-color: #092530; color: white">
                    <!-- USA -->
                    <v-list-item to="/en-us" class="dropdown-item">
                      <v-list-item-title>USA</v-list-item-title>
                      <v-divider
                        color="white"
                        class="border-opacity-25"
                      ></v-divider>
                    </v-list-item>
                    <!-- UK -->
                    <v-list-item to="/en-uk" class="dropdown-item">
                      <v-list-item-title>UK</v-list-item-title>
                      <v-divider
                        color="white"
                        class="border-opacity-25"
                      ></v-divider>
                    </v-list-item>
                    <!-- China -->
                    <v-list-item to="/en-cn" class="dropdown-item">
                      <v-list-item-title>China</v-list-item-title>
                      <v-divider
                        color="white"
                        class="border-opacity-25"
                      ></v-divider>
                    </v-list-item>
                    <!-- Pakistan -->
                    <v-list-item to="/en-pk" class="dropdown-item">
                      <v-list-item-title>Pakistan</v-list-item-title>
                      <v-divider
                        color="white"
                        class="border-opacity-25"
                      ></v-divider>
                    </v-list-item>
                  </v-list>
                </v-menu>
              </div>
            </v-col>
          </v-row>
        </v-container>
        <!-- Divider after the logo and Regions button -->
        <v-divider color="white"></v-divider>
        <!-- News and Insights section -->
        <div>
          <v-row class="d-flex justify-center mt-8">
            <v-chip color="#03071c" variant="flat"
              ><h2 class="text-gradient">News and Insights</h2>
            </v-chip></v-row
          >
        </div>
        <!-- Title for Latest Insights section -->
        <div class="d-flex justify-center">
          <h1
            style="font-size: 36px"
            class="d-flex justify-center text-gradient ml-4 mt-6"
          >
            Latest Insights from Leading Voices
          </h1>
        </div>
        <!-- Description of NetSol's impact -->
        <div class="d-flex justify-center">
          <h4 class="font-weight-thin pa-2 text-blue-grey-lighten-3">
            Solving the world’s problems through technology wouldn’t be possible
            without our most important <br />
            <span class="d-flex justify-center"
              >invention: the NetSol. Have a look at our talented teams.</span
            >
          </h4>
        </div>
        <!-- "View All News" button -->
        <div class="d-flex justify-center">
          <a href="#" class="text-white pa-2 mb-12">View All News</a>
        </div>
        <!-- Slot for additional content -->
        <div>
          <slot />
        </div>
      </div>
    </v-app>
  </div>
</template>

<style>
/* Global styles */
html,
body {
  margin: 0;
  padding: 0;
}
/* Background styling */
.background {
  background-size: cover;
  background-position: center;
  background-image: url("@/images/background.png");
}
/* Hover effect for dropdown items */
.dropdown-item:hover {
  color: #00eaff; /* Change to the desired hover background color */
}
/* Text gradient effect */
.text-gradient {
  background-image: linear-gradient(to bottom, #ffffff, #d0d0d0);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
