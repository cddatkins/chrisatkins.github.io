<template>
  <div class="about">
    <h1>Hello World!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Chris Atkins</strong>, a Game Programmer.<br/>
        I've mostly worked with <strong>Unity</strong> and <strong>C#</strong> but I'm always looking to learn new things.<br/>
        I'm currently working on a few projects, some of which you can see on the <router-link to="/game-projects">Game Projects</router-link> page.<br/>
      </div>

      

      <!--<div style="margin-top: 40px;">I'm <strong>currently looking for work</strong> as a Game Programmer. You can reach me at <a href="mailto:cddatkins@gamil.com">cddatkins@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>-->
    </div>

    <div class="photo">
      <img src="img/chrisProfile.jpeg" alt="Avatar of Chris" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>

.about {
  width: 50%;
  margin: 0 auto;
  
}

.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  width: 300px;      /* Set the desired width */
  height: 300px;     /* Set the same height to create a square */
  border-radius: 50%;
  overflow: hidden;  /* Ensures any overflow is hidden */
}

.photo img {
  width: 100%;
  height: 100%;
  object-fit: cover; /* Ensures the image covers the container without distortion */
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
  }
}

</style>