<template>
  <div align="center" class="all">
    <v-container style="position: relative; top: -38px">
      <v-row>
        <v-col>
          <a
            href="https://twitter.com/set_official"
            style="text-decoration: none"
          >
            <v-btn
              large
              elevation="1"
              color="#1DA1F2"
              height="3.2rem"
              class="buttonline"
              style="text-transform: none"
            >
              <div class="btntwitter iconsize">
                <v-icon dark size="42px">mdi-twitter</v-icon>
                Twitter
              </div>
            </v-btn>
          </a></v-col
        >
        <v-col>
          <a
            href="https://github.com/SystemEngineeringTeam"
            style="text-decoration: none"
          >
            <v-btn
              large
              elevation="1"
              color="white"
              height="3.2rem"
              class="buttonline"
              style="text-transform: none"
            >
              <div class="btngithub iconsize">
                <v-icon dark size="40px">mdi-github</v-icon>
                GitHub
              </div>
            </v-btn>
          </a></v-col
        >
        <v-col>
          <a
            href="https://set1.ie.aitech.ac.jp/blog"
            style="text-decoration: none"
          >
            <v-btn
              large
              elevation="1"
              color="black"
              height="3.2rem"
              class="buttonline"
              style="text-transform: none"
            >
              <div class="btnblog iconsize">
                <v-icon dark size="40px">mdi-book-open-blank-variant</v-icon>
                Blog
              </div>
            </v-btn>
          </a></v-col
        >
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      twitterURL: "https://github.com/hihumikan",
      githubURL: "https://github.com/hihumikan",
      blogURL: "https://github.com/hihumikan",
    };
  },
};
//@import url("https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@500&family=Roboto:ital@1&display=swap");
</script>

<style>
.btntwitter {
  color: white;
}

.btngithub {
  color: black;
}

.btnblog {
  color: white;
}

.iconsize {
  font-size: 22px;
}

.all {
  font-family: Montserrat;
}

@media screen and (min-width: 830px) {
  .buttonline {
    width: 16em;
  }
}

@media only screen and (min-width: 689px) and (max-width: 829px) {
  .buttonline {
    width: 13em;
  }
}
@media only screen and (min-width: 545px) and (max-width: 688px) {
  .buttonline {
    width: 10em;
  }
}
@media only screen and (min-width: 417px) and (max-width: 544px) {
  .buttonline {
    top: 49px;
    width: 22rem;
  }
}
@media only screen and (min-width: 309px) and (max-width: 416px) {
  .buttonline {
    top: 49px;
    width: 16rem;
  }
}
@media only screen and (min-width: 20px) and (max-width: 309px) {
  .buttonline {
    top: 49px;
    width: 12rem;
  }
}
@media only screen and (min-width: 20px) and (max-width: 241px) {
  .buttonline {
    top: 49px;
    width: 10rem;
  }
}
</style>
