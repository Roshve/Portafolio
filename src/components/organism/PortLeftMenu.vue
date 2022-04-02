<template>
  <aside class="side-bar">
    <div class="profile">
      <img />
      <h4>Luis Cova</h4>
      <p>Front-End Developer</p>
      <ul>
        <li>
          <a href="facebook.com"><img /></a>
        </li>
        <li>
          <a href="linkedin.com"><img /></a>
        </li>
        <li>
          <a href="https://github.com/"><img /></a>
        </li>
      </ul>
    </div>
    <hr />
    <div class="about">
      <ul>
        <li>
          <p>Age:</p>
          <p>24</p>
        </li>
        <li>
          <p>Residence</p>
          <p>BD</p>
        </li>
        <li>
          <p>Freelance</p>
          <p>Avalible</p>
        </li>
        <li>
          <p>Address:</p>
          <p>Dhaka, Bangladesh</p>
        </li>
      </ul>
    </div>
    <hr />
    <div class="languages">
      <h4>Languages</h4>
      <ul>
        <li>Bangla</li>
        <li>English</li>
        <li>Spanish</li>
      </ul>
    </div>
    <hr />
    <div class="skills">
      <h4>Skills</h4>
      <ul>
        <li>Html</li>
        <li>CSS</li>
        <li>Js</li>
        <li>PHP</li>
        <li>WordPress</li>
      </ul>
    </div>
    <hr />
    <div class="extra-skills">
      <h4>Extra Skills</h4>
      <ul>
        <li>Bootstrap, Materialize</li>
        <li>Stylus, Sass, Less</li>
        <li>Gulp, Webpack, Grunt</li>
        <li>GIT Knowledge</li>
      </ul>
    </div>
    <hr>
    <port-button>DOWNLOAD CV</port-button>
  </aside>
</template>

<script>
import PortButton from "../atomic/PortButton.vue";
export default {
  name: "PortLeftMenu",
  components: { PortButton },
};
</script>

<style lang="scss" scoped>
.side-bar {
  background: #fff;
  width: 305px;
  padding: 25px 40px;
}
</style>>