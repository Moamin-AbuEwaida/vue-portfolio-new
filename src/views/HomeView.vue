<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <NavBar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.jpeg" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="red--text text-darken-4 top">Hello I'm Agatha</h5>
          <h1 class="white--text">Modern Artist</h1>
          <p class="grey--text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.<br />
            Placeat quam doloribus ipsam aperiam impedit quo qui assumenda
            maxime, <br />
            animi corporis commodi omnis?
          </p>
          <v-btn tile color="#a7121d" dark> about me</v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#a7121d" x-large class="ml-3">
                    fa-masks-theater
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">Theater</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem ipsum dolor sit amet consectetur<br />
                    adipisicing elit.
                  </p>
                  <v-btn color="#a7121d" dark text
                    >Know More <v-icon right>mdi-arrow-right</v-icon></v-btn
                  >
                </div>
                <div class="child bgColor2">
                  <v-icon x-large class="ml-3" dark>fa-film</v-icon>
                  <h3 class="white--text ml-3 mt-4">Cinema</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem ipsum dolor sit amet consectetur.
                    <br />Neque reiciendis sapiente,
                  </p>
                  <v-btn dark text
                    >Know More <v-icon right>mdi-arrow-right</v-icon></v-btn
                  >
                </div>
                <div class="child bgColor1">
                  <v-icon color="#a7121d" x-large class="ml-3" dark
                    >fa-people-robbery</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Dance</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem ipsum dolor sit amet consectetur.
                    <br />Neque reiciendis sapiente,
                  </p>
                  <v-btn color="#a7121d" dark text
                    >Know More <v-icon right>mdi-arrow-right</v-icon></v-btn
                  >
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="red--text text-darken-4 mt-4 number">12</h1>
                  <h3 class="white--text mt-4">Years Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mBotton padding bgColor1">
                        <h1 class="red--text text-darken-4">24+</h1>
                        <p class="grey--text">projects</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol mt-2">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text-darken-4">214+</h1>
                        <p class="grey--text">Hours of act</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mBotton padding bgColor1">
                        <h1 class="red--text text-darken-4">30</h1>
                        <p class="grey--text">Shows</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol mt-2">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text-darken-4">11</h1>
                        <p class="grey--text">Different Cities</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="white--text text-uppercase">Featured Shows</h4>
          <p class="grey--text">Lorem ipsum dolor sit.</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#a7121d" dark>View All</v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1e1e1e"
          >
            <v-img src="2.jpeg" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1e1e1e"
          >
            <v-img src="3.jpeg" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> The Vintage </v-btn>
          <br />
          <v-btn color="#a7121d" dark text class="ml-n4"
            >Know more <v-icon right>mdi-arrow-right</v-icon></v-btn
          >
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> The Fisherman </v-btn>
          <br />
          <v-btn color="#a7121d" dark text class="ml-n4"
            >Know more <v-icon right>mdi-arrow-right</v-icon></v-btn
          >
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1e1e1e"
          >
            <v-img src="4.jpeg" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1e1e1e"
          >
            <v-img src="5.jpeg" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Fly Away </v-btn>
          <br />
          <v-btn color="#a7121d" dark text class="ml-n4"
            >Know more <v-icon right>mdi-arrow-right</v-icon></v-btn
          >
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> The Tree </v-btn>
          <br />
          <v-btn color="#a7121d" dark text class="ml-n4"
            >Know more <v-icon right>mdi-arrow-right</v-icon></v-btn
          >
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    let's work together on<br />your next project
                  </h1>
                  <p class="grey--text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Ab!<br />consectetur adipisicing elit. Ab!
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn tile color="#a7121d" dark class="mt-16">contact</v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text @click="scroll('home')">Home</v-btn>
              <v-btn text @click="scroll('project')">Project</v-btn>
              <v-btn text @click="scroll('about')">About</v-btn>
              <v-btn text @click="scroll('contact')">Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar";

export default {
  name: "HomePage",
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },

  components: {
    NavBar,
  },
};
</script>

<style>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #ce1d2a;
}
.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mBottom {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0px;
}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>
