<template>
  <div>
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
        <a class="download-link" href="d/resume-en.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF</a>
        <div style="clear:both"></div>
      </div>
    </div>
    <div class="photo">
      <img src="img/resume-photo.png" alt="Photo of John" />
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2>Work experience</h2>

      <h3>Computer Operator<span class="company-name"> · Inside Media SRL</span></h3>
      <h4>Aug 2022 - Sep 2022</h4>

      <div>• Inserted and processed data into Word and Excel documents</div>
      <div>• Worked with printers, plotters, heat presses, and cutters</div>
      <div>• Assisted coworkers with operating customisation machinery for designing a multitude of items, such as shirts, bags, hats and more</div>

      <div class="tech-stack">Microsoft Office, Teamwork, Communication</div>

      <h2>Skills</h2>

      <div class="skill-set">
        <h3>Languages</h3>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div style="clear:both" />
      </div>

      <div class="skill-set">
        <h3>Game Dev</h3>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div style="clear:both" />
      </div>

      <div class="skill-set">
        <h3>Tools & Frameworks</h3>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div style="clear:both" />
      </div>

      <div class="skill-set">
        <h3>Other Software</h3>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div class="skill">SQL</div>
        <div style="clear:both" />
      </div>
      <div style="clear:both" />

      <h2>Education</h2>

      <h3>TU Eindhoven - Present</h3>
      <h4>BSc Computer Science and Engineering</h4>
      <div><b>Relevant courses:</b> Design for Games & Play I, II, and III, Data Structures, Algorithms, Algorithms Engineering, Heuristic Algorithms</div>

      <h3>TU/e Honors Academy - Present</h3>
      <h4>Competitive Programming and Problem Solving Track</h4>
      <div>• Selected for TU Eindhoven's Honors Academy (Top 10% of Bachelor students) and finished the 1st year with a "Good" result</div>
      <div>• Researched the topic of impartial game theory, presented my research in a seminar, and wrote a paper on its applications</div>

      <h2>Languages</h2>

      <h3>Romanian</h3>
      <div>Mother tongue</div>

      <h3>English</h3>
      <div>Fluent speaker (C2)</div>

      <h3>Dutch</h3>
      <div>In the process of learning and practicing... (A1)</div>

      <h3>French</h3>
      <div>Learned as part of middle and high school (~A2)</div>

      <h2>Besides...</h2>
      <div>
        <h3>I ❤️ Video Games</h3>
        <div>I find it really soothing to just shoot at bad guys</div>

        <h3>I 🧡 Board Games</h3>
        <div>I used to be thin but then I ingested 10 kilos of steroids and proteins a day while doing 1000 push-ups.</div>

        <h3>I 💛 Storytelling</h3>
        <div>I hope I can have a career here someday but I might have temper issues.</div>

        <h3>I 💚 Animals</h3>
        <div>Especially the big ones, with the trunk and leaves.</div>

      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "../components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    //SkillRate,
  },
});
</script>

<style scoped>
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

.company-name {
  opacity: 0.5;
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

.skill-set {
  float: left;
  padding-right: 30px;
  max-width: 230px !important;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.skill {
    float: left;
    border: 1px solid hsla(0,0%,86.3%,.44);
    padding: 2px 10px;
    margin: 5px
}

.photo img {
  height: 300px;
  width: 300px;
}

.tech-stack {
  font-style: italic;
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
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>