<template>
  <div class="header">
    <div class="content">
      <h1 class="name">Christine Lin</h1>
      <p class="subtitle">
        A Frontend Developer, having passion for web design and love to create
        for it. Based in Taipei, Taiwan.
      </p>
    </div>
    <div>
      <img class="img" src="/images/christine.jpeg" alt="Christine Lin" />
    </div>
  </div>
</template>

<style scoped>
h1 {
  font-size: 60px;
  font-weight: bold;
}

p {
  font-family: "Roboto Mono", sans-serif;
}

.header {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 50px;
  background-color: #f9f9f9;
  color: black;
  height: 600px;
}

.content {
  width: 50%;
}

.img {
  object-fit: cover;
  width: 400px;
  height: 400px;
  border-radius: 50%;
  filter: grayscale(100%);
}
</style>
