<template>
  <div class="block latestPostBlock">
    <v-container>
      <h2 class="text-center">Guide</h2>

      <v-hover v-slot:default="{ hover }">
        <div>
        <v-card
          class="rounded-xl text-center"
          style="background-image: linear-gradient(90deg, #1DCCE0, #4247DD);"
          dark
          max-width="100%"
          max-height="320"
          :elevation="hover ? 12 : 4"
          :class="{ 'on-hover': hover }"
          >
            <div class="d-flex justify-space-between">
              <div>
                <h1 class="font-bold my-16 pl-9" style="font-size: 3.2vw;">
                  - What is the Book4Book -
                </h1>
              </div>
              <div>
                <iframe
                  class="rounded-xl text-right"
                  width="560"
                  height="320"
                  src="https://www.youtube.com/embed/crrZ4scWh0s"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                ></iframe>
              </div>
            </div>
        </v-card>
        </div>
      </v-hover>
      <br />
      <v-divider class="pt-9"></v-divider>
      <br />
      <v-hover v-slot:default="{ hover }">
        <v-card
          class="text-center rounded-xl"
          style="background-image: linear-gradient(90deg,#4247DD,#1DCCE0);"
          dark
          max-width="100%"
          max-height="320"
          :elevation="hover ? 12 : 4"
          :class="{ 'on-hover': hover }"
        >
          <div class="d-flex justify-space-between">
            <div>
              <iframe
                class="rounded-xl text-left"
                width="560"
                height="320"
                src="https://www.youtube.com/embed/8KCJoSzAF6k"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </div>
            <div>
              <h1 class="font-bold py-16" style="font-size: 2.6vw;">
                - Watch here how to register as a member of Book4Book -
              </h1>
            </div>
          </div></v-card
        >
      </v-hover>
      <br />
      <v-divider class="pt-9"></v-divider>
      <br />
      <v-hover v-slot:default="{ hover }">
        <v-card
          class="text-center rounded-xl"
          style="background-image: linear-gradient(90deg, #1DCCE0, #4247DD);"
          dark
          max-width="100%"
          max-height="320"
          :elevation="hover ? 12 : 4"
          :class="{ 'on-hover': hover }"
        >
          <div class="d-flex justify-space-between">
            <div>
              <h1 class="font-bold px-10 my-16" style="font-size: 2.6vw;">
                - Watch here how to post a book request in Book4Book -
              </h1>
            </div>
            <div>
              <iframe
                class="rounded-xl text-right"
                width="560"
                height="320"
                src="https://www.youtube.com/embed/Sc6QBBu03VY"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </div>
          </div>
        </v-card>
      </v-hover>
      <br />
      <v-divider class="pt-9"></v-divider>
      <br />
      <v-hover v-slot:default="{ hover }">
        <v-card
          class="text-center rounded-xl"
          style="background-image: linear-gradient(90deg,#4247DD,#1DCCE0);"
          dark
          max-width="100%"
          max-height="320"
          :elevation="hover ? 12 : 4"
          :class="{ 'on-hover': hover }"
        >
          <div class="d-flex justify-space-between">
            <div>
              <iframe
                class="rounded-xl text-left"
                width="560"
                height="320"
                src="https://www.youtube.com/embed/luhlMZ3Djp0"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </div>
            <div>
              <h1 class="font-bold pa-10" style="font-size:  2.6vw;">
                - Watch here how to donate a book in Book4Book -
              </h1>
            </div>
          </div>
        </v-card>
      </v-hover>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "UtubeVid",

  data: () => ({
    items: [
      {
        src: require("../assets/images/nish.jpg"),
      },
    ],
  }),
};
</script>