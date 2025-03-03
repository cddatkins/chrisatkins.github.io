<template>
  <div class="contact">
    <h1>Let's get in touch</h1>
    <ul>
      <li>
        <i class="fa fa-envelope-o fa-lg fa-fw"></i>
        <a href="mailto:cddatkins@gmail.com" target="_blank">cddatkins@email.com</a>
      </li>
      <li>
        <i class="fa fa-linkedin fa-lg fa-fw" style="vertical-align: -5%;"></i>
        <a href="https://www.linkedin.com/in/cddatkins/" target="_blank">linkedin.com/in/cddatkins/</a>
      </li>
      <li>
        <i class="fa fa-github fa-lg fa-fw"></i>
        <a href="https://github.com/cddatkins" target="_blank">github.com/cddatkins</a>
      </li>
      <!--<li>
        <i class="fa fa-gamepad fa-lg fa-fw"></i>
        <a href="https://myself.itch.io" target="_blank">myself.itch.io</a>
      </li>
      <li>
        <i class="fa fa-steam fa-lg fa-fw"></i>
        <a href="https://steamcommunity.com/id/me" target="_blank">steam.com/me</a>
      </li>-->
    </ul>
  
    <!--<div style="margin-bottom:40px;">I'm looking for a job !<br/>Feel free to contact me about any opportunity, or just to chat about cooking, kittens or anything else.</div>-->

    

  </div>
</template>

<style scoped>
.contact {
  width: 50%;
  margin: 0 auto;
  
}

ul {
  list-style: none;
  padding-inline-start: 0px;
}

li {
    line-height: 1.8em;
    font-size: 1.2em;
  }

@media only screen and (min-width: 620px){
  ul {
    padding-inline-start: 40px;
  }

  li {
    line-height: 2em;
    font-size: 1.4em;
  }
}

i {
  margin-right: 20px;
}
</style>
