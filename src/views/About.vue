<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello! :)</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Raul Șerban</strong>, an avid game developer and designer.<br/>
        I'm currently a student at TU Eindhoven in the Netherlands, enrolled in the <strong>Computer Science and Engineering</strong> Bachelor program.
      </div>

      <div style="margin-top: 20px;">I've worked on a few <router-link to="/game-projects">game-related projects</router-link> and on <router-link to="/other-projects">other projects</router-link>. You can also check out my <router-link to="/resume">resume</router-link> for further details.</div>

      <div style="margin-top: 40px;">I'm currently <strong>accepting work and any opportunities</strong> in the gaming industry. You can reach me at <a href="raulserban05@gmail.com">raulserban05@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of John" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>