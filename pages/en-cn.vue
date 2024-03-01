<template>
  <div>
    <v-container class="mb-6 mt-3">
      <v-row>
        <v-col cols="12" sm="6" md="3" class="item-col">
          <!-- Image for the first item -->
          <v-img
            src="../public/images/13.png"
            width="100%"
            class="item-img"
          ></v-img>
          <!-- Button for the item type -->
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">News</v-btn>
          </div>
          <!-- Title for the first item -->
          <div class="text-white">
            <h4>Five Ways to Squeeze the Most Value out of Your ERP System</h4>
          </div>
          <!-- Description for the first item -->
          <div>
            <p class="text-white mt-1 mb-2 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>

        <!-- Second item column (similar structure) -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <v-img
            src="../public/images/14.jpeg"
            width="100%"
            class="item-img"
          ></v-img>
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">Blog</v-btn>
          </div>
          <div class="text-white">
            <h4>
              Getting the Most Out of Your Business Intelligence Dashboard
            </h4>
          </div>
          <div>
            <p class="text-white mt-1 mb-2 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>

        <!-- Third item column (similar structure) -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <v-img
            src="../public/images/15.jpg"
            width="100%"
            class="item-img"
          ></v-img>
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">News</v-btn>
          </div>
          <div class="text-white">
            <h4>Client Delivery at PDG: Interview with Navarre Miles</h4>
          </div>
          <div>
            <p class="text-white mt-1 mb-2 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>

        <!-- Fourth item column (similar structure) -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <v-img
            src="../public/images/16.png"
            width="100%"
            class="item-img"
          ></v-img>
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">Blog</v-btn>
          </div>
          <div class="text-white">
            <h4>Top Digital Transformation Trends for Media</h4>
          </div>
          <div>
            <p class="text-white mt-1 mb-2 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<style>
/* Styling for item columns */
.item-col {
  padding: 0 15px;
}
/* Styling for item images */
.item-img {
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}
/* Hover effect for item images */
.item-img:hover {
  transform: scale(1.05); /* Scale up on hover */
}
</style>
