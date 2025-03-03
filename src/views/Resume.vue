<template>
  <div class="resume">
    <h1>Resume</h1>

    <div class="paragraph">
      I'm <strong>John Matrix</strong>, a former Delta Force operative with lots of experience, lots of training and huge muscles.
      <br />After graduating from kindergarten, I've been enrolled in the army for 25 years, where I learned to destroy things in an amazing number of ways.
      <br />I joined the Delta Force because I thought it was Greek lessons, but I quickly adapted to this unexpected environment and became a key element.
      <br />I love teamwork, but I can also go in solo depending on the mission requirements.
      <br />
      <br />Right now I'm trying to find inner peace after I've read some personal development books. I'm looking for a monk job so if you have any opportunity feel free to 
      <router-link to="/contact">contact me</router-link>.
      <br />
      <br />Besides war, I'm passionate about firearms, martial arts, explosions, push-ups and flowers.

      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/resume-en.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF 🇬🇧</a>
        <a class="download-link" href="d/cv-fr.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Télécharger en PDF 🇫🇷</a>
        <div style="clear:both"></div>
      </div>
    </div>

    <div class="photo">
      <img src="img/chrisProfile.jpeg" alt="Photo of Chris" />
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2>Work experience</h2>

      <h3>Primrows - Tursiops Studios</h3>
      <h4>2024-Present</h4>
      <div>Game about planting flowers</div>
      <div class="tech-stack">Unity, C#</div>

      <h3>Whisker Squadron - </h3>
      <h4>2021-2024</h4>
      <div>Game about cats flying spaceships</div>
      <div class="tech-stack">Unity, C#</div>

      <h3>Indie Pogo - LoweBros.Studios</h3>
      <h4>2016-2020</h4>
      <div>Game about indie clashing with pogo-abilities</div>

      <div class="tech-stack">Game Maker</div>

      <!--<h2>Skills</h2>

      <div class="skill-set">
        <h3>Lethal</h3>
        <SkillRate name="Handguns" :rate="5" />
        <SkillRate name="Rifles" :rate="5" />
        <SkillRate name="Shotguns" :rate="5" />
        <SkillRate name="Machineguns" :rate="5" />
        <SkillRate name="Missile launchers" :rate="5" />
        <SkillRate name="Knives" :rate="5" />
        <SkillRate name="Hand to hand combat" :rate="5" />
      </div>

      <div class="skill-set">
        <h3>Non-lethal</h3>
        <SkillRate name="Sneaking" :rate="1" />
        <SkillRate name="Negotiation" :rate="1" />
        <SkillRate name="Seduction" :rate="1" />
        <SkillRate name="Sense of humor" :rate="2" />
      </div>
      <div style="clear:both" />-->

      <h2>Education</h2>
      <h3>University of Michigan - 2013</h3>
      <h4>Bachelor's of Science</h4>
      <div>Computer Science</div>

    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
   // SkillRate,
  },
});
</script>


<style scoped>
.resume {
  width: 50%;
  margin: 0 auto;
  
}

h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo {
  height: 300px;
  width: 300px;
  border-radius: 50%;
  overflow: hidden;  /* Ensures any overflow is hidden */
}

.photo img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.tech-stack {
  font-style: italic;
}



@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>