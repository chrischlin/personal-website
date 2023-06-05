<template>
  <div class="footer">
    <div class="title">Let's Work Together!</div>
    <div class="content">Get a chance to learn more about each other!</div>
    <div class="icon-area">
      <a href="https://www.linkedin.com/in/chrislin0/" class="icon">
        <font-awesome-icon icon="fa-brands fa-linkedin" size="2x" />
      </a>
      <a href="https://github.com/chrischlin" class="icon">
        <font-awesome-icon icon="fa-brands fa-github" size="2x" />
      </a>
    </div>
    <div class="copyright">© Christine Lin 2023</div>
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import { library } from "@fortawesome/fontawesome-svg-core";
import { faLinkedin, faGithub } from "@fortawesome/free-brands-svg-icons";

library.add(faLinkedin, faGithub);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>

<style scoped>
.footer {
  background-color: #191919;
  color: white;
  text-align: center;
  display: flex;
  flex-direction: column;
}

.title {
  font-size: 50px;
  font-weight: bold;
  margin-top: 100px;
  margin-bottom: 100px;
}

.content {
  font-family: "Roboto Mono", sans-serif;
}

.icon-area {
  margin: 50px;
}

.icon {
  color: inherit;
  margin: 10px;
}

.copyright {
  margin-top: 100px;
  margin-bottom: 50px;
}
</style>
