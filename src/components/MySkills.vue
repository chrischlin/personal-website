<template>
  <div class="skill-set">
    <div class="title">My Skills.</div>
    <div class="skills">
      <div>
        <div class="subtitle">Web Development</div>
        <div class="skills-content">
          <div v-for="value in webs">
            {{ value }}
          </div>
        </div>
      </div>
      <div>
        <div class="subtitle">Others</div>
        <div class="skills-content">
          <div v-for="value in others">
            {{ value }}
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      webs: [
        "HTML 5",
        "JavaScript",
        "CSS 3",
        "React.js",
        "Vue 3",
        "Chakra UI",
        "Git",
        "NPM",
        "Yarn",
      ],
      others: [
        "Mangement",
        "Recruitment",
        "Negotiation",
        "Communication",
        "Planning",
        "Problem-solving",
      ],
    };
  },
};
</script>

<style scoped>
.skill-set {
  display: flex;
  justify-content: space-around;
  height: 400px;
  margin-top: 100px;
}

.skills {
  display: flex;
  justify-content: space-between;
  gap: 100px;
}

.skills-content {
  display: grid;
  grid-template-columns: auto auto;
  gap: 20px 30px;
  font-family: "Roboto Mono", sans-serif;
}

.title {
  font-size: 50px;
  font-weight: bold;
}

.subtitle {
  font-size: 25px;
  font-weight: bold;
  margin-bottom: 30px;
}
</style>
