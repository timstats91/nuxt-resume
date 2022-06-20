<template>
<header class="container">
  <nav class="nav">
    <img src="../static/img/TimStatler.png" alt="" class="logo">
    <ul class="nav-list">
        <li class="nav-item">About Me</li>
        <li class="nav-item">Education</li>
        <li class="nav-item">Experience</li>
        <li class="nav-item">Technologies</li>
        <li class="nav-item">Projects</li>
    </ul>
  </nav>
</header>
</template>

<script>
export default {

}
</script>

<style scoped>
.container {
    background-color: #399322;
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.nav {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}
.nav img {
    height: 100px;
}
.nav-list {
    display: flex;
    flex-direction: row;
}
.nav-item {
    text-decoration: none;
    list-style: none;
    padding: 1em;
}
</style>