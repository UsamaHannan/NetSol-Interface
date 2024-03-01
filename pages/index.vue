<template>
  <div>
    <v-container class="mb-6 mt-3">
      <v-row>
        <!-- First item column -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <!-- Image for the first item -->
          <v-img
            src="../public/images/1.png"
            width="100%"
            class="item-img"
          ></v-img>
          <!-- Button for the item type -->
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">News</v-btn>
          </div>
          <!-- Title for the first item -->
          <div class="text-white">
            <h4>Leasing Life Conference & Awards</h4>
          </div>
          <!-- Description for the first item -->
          <div>
            <p class="text-white mt-1 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>

        <!-- Second item column (similar structure) -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <v-img
            src="../public/images/2.png"
            width="100%"
            class="item-img"
          ></v-img>
          <!-- Button for the item type -->
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">Blog</v-btn>
          </div>
          <!-- Title for the second item -->
          <div class="text-white">
            <h4>Auto Finance Summit 2023</h4>
          </div>
          <!-- Description for the second item -->
          <div>
            <p class="text-white mt-1 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>

        <!-- Third item column (similar structure) -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <v-img
            src="../public/images/3.png"
            width="100%"
            class="item-img"
          ></v-img>
          <!-- Button for the item type -->
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">News</v-btn>
          </div>
          <!-- Title for the third item -->
          <div class="text-white">
            <h4>Careers at Netsol</h4>
          </div>
          <!-- Description for the third item -->
          <div>
            <p class="text-white mt-1 text-body-2">
              Solving the world’s problems through technology wouldn’t be
              possible without our most important invention.
            </p>
          </div>
        </v-col>

        <!-- Fourth item column (similar structure) -->
        <v-col cols="12" sm="6" md="3" class="item-col">
          <v-img
            src="../public/images/4.png"
            width="100%"
            class="item-img"
          ></v-img>
          <!-- Button for the item type -->
          <div class="mt-3 mb-3">
            <v-btn variant="tonal" color="#18EBFE" size="x-small">Blog</v-btn>
          </div>
          <!-- Title for the fourth item -->
          <div class="text-white">
            <h4>Leasing Life Conference & Awards</h4>
          </div>
          <!-- Description for the fourth item -->
          <div>
            <p class="text-white mt-1 text-body-2">
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
  transform: scale(1.05);
}
</style>
