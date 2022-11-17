---
layout: cover
theme: bricks
title: A brief story of Vue
---

# A brief story of Vue
A rebelious front end framework

<img class="max-h-100 float-right" src="/public/images/vue_logo.png">

<!--
VueJS is an mvvm Javascript framework para escribir
-->

---

# Some context of the times

<div  class="flex flex-row">
  
  <div v-click class="p-6 max-w-sm mx-auto bg-green rounded-xl shadow-lg flex flex-column items-center spacex-4">
    <div class="shrink-0 text-center max-w-sm">
      <img src="/images/nodejs_logo.png" />
      <span>2009</span>
      <p class="text-sm"><strong>NodeJS</strong> is released and opens several new capabilities and posibilities in JS development</p>
    </div>    
  </div>
  <div v-click class="p-6 max-w-sm mx-auto bg-green rounded-xl shadow-lg flex flex-column items-center spacex-4">
    <div class="shrink-0 text-center max-w-sm">
      <img src="/images/angularjs_logo.png" />
      <span>2010</span>
      <p class="text-sm"><strong>Angular JS</strong> is released introducing the concept of two way data binding and stateful components in the web</p>
    </div>        
  </div>

  <div v-click class="p-6 max-w-sm mx-auto bg-green rounded-xl shadow-lg flex flex-column items-center spacex-4">
    <div class="shrink-0 text-center max-w-sm">
      <img src="/images/react_logo.png" />
      <span>2013</span>
      <p class="text-sm"><strong>ReactJS</strong> is released and introduces composition and a user first, component driven context for building applications</p>
    </div>        
  </div>
  <div v-click class="p-6 max-w-sm mx-auto bg-green rounded-xl shadow-lg flex flex-column items-center spacex-4">
    <div class="shrink-0 text-center max-w-sm">
      <img src="/images/vue_logo.png" />
      <span>2014</span>
      <p class="text-sm"><strong>VueJS</strong> gets it's first commits and attempts to bring the same user and developer focused mindset closer to HTML as a progressively adoptable framework</p>
    </div>        
  </div>
  <div v-click class="p-6 max-w-sm mx-auto bg-green rounded-xl shadow-lg flex flex-column items-center spacex-4">
    <div class="shrink-0 text-center max-w-sm">
      <img src="/images/angular_logo.png" />
      <span>2016</span>
      <p class="text-sm"><strong>Angular</strong> breaks into the scene with a more OOP and Typescript powered framework.</p>
    </div>        
  </div>
</div>

<!-- a reminder that this style is always scoped -->
<style>
.slidev-vclick-target {
  transition: all 2000ms ease 10ms
}

.slidev-vclick-hidden {
  transform: scale(0);
}
</style>

<!-- 2004 Maven for Java -->
<!-- 2006 John Resig releases JQuery -->
<!-- 2010 backbone -->
<!-- 2013 Jordan Walke releases React -->
<!-- 2013 also saw the birth of Gulp by Erick Schoffstail -->
<!-- 2015 Chrome adds turbofan, growing the capabilities of the browser-->
<!-- Hasta 2021 angular js perdio support -->

---
title: it all started with this dude
layout: center
background: '/images/evan_you_conference.png'
---

<img v-click src="/images/evan_you_conference.png" />

# The story starts with You
<v-after>

## Evan You

<style>
.slidev-vclick-target {
  transition: all 1000ms ease 10ms
}

.slidev-vclick-hidden {
  transform: scale(0);
}
</style>

</v-after>
---

# Evan You can do it

- He had a major in history of art and took a bootcamp of tech in arts, learned JS
- Built a web native version of a highly interactive app and got Google's attention
- Worked for MeteorJS as a dev until VueJS patreon was financially viable
- Focused on the user and developer experiences as his principles of design
- Great community building and direction skills, he is the BDFL for VueJS

<img src="/images/evan_you_conference_long.jpeg" />

<!-- Other BDFLs: Guido Van Rossum Python, Linus Torvalds

He shifted to fully working on Vue when his Patreon checks got to 4K USD a month, today he is aroun d the 40KUSD a Month-->

---
layout: center
---

# Vue then

- Vue started as Element, then Seed, and was initially thought of as a lighter version of Angular
- A small community up until Vue2, where things got crazy for Evan and crew
- Laravel choose it for Laravel Spark, boosting Vue while leveraging on PHP's comeback

<img v-click class="h-32" src="/public/images/taylor_otwell_tweet_on_vue.png" />

<v-click>

- Backing was and is community based

</v-click>


<div class="flex w-full flex-row justify-center">

  <div class="shrink w-50">
    <img v-click class="object-contain w-28" src="/public/images/google_logo.png">
    <img v-after class="object-contain w-28" src="/public/images/angular_logo.png">
  </div>

  <div class="w-50">
    <img v-after class="object-contain w-28" src="/public/images/facebook_logo.webp">
    <img v-after class="object-contain w-28" src="/public/images/react_logo.png">
  </div>

  <div class="w-50">
    <img v-after class="object-contain w-28" src="/public/images/evan_face.png">
    <img v-after class="object-contain w-28" src="/public/images/vue_logo.png">
  </div>
</div>

<style>
.slidev-vclick-target {
  transition: all 1000ms ease 10ms
}

.slidev-vclick-hidden {
  transform: scale(0);
}
</style>

---

# Vue now

<div class="flex flex-wrap justify-center">
  <img class="m-5 max-h-140px" src="/public/images/git_angular.png" />
  <img class="m-5 max-h-140px" src="/public/images/git_vue.png" />
  <img class="m-5 max-h-140px" src="/public/images/git_react.png" />
</div>

---

# Vue now
- Widely adoped in Europe and Asia (where Evan is a hero)

<v-click>

- Ecosystem has produced tooling like <strong>Vite</strong> and <strong>Pinia</strong>, which are starting to set prescedents in terms of buildtools and state management.

<div class="flex justify-center">
  <img src="/public/images/vite_logo.svg" />
  <img src="/public/images/pinia_logo.svg" />
</div>

</v-click>

<style>
.slidev-vclick-target {
  transition: all 1000ms ease 10ms
}

.slidev-vclick-hidden {
  transform: scale(0);
}
</style>

---

# Vue now


<v-click>

- Nasa, SpaceX and other major adpopters use it for dashboards and UI stuff

<div class="bg-white flex flex-wrap justify-start">
  <img class="max-h-90px " src="/public/images/nitendo_logo.png"/>
  <img class="max-h-90px " src="/public/images/nasa_logo.jpeg"/>
  <img class="max-h-90px " src="/public/images/elon_logos.jpeg"/>
  <img class="max-h-90px " src="/public/images/behance_logo.webp"/>
  <img class="max-h-90px " src="/public/images/chesscom_logo.png"/>
  <img class="max-h-90px " src="/public/images/gitlab_logo.png"/>
</div>

</v-click>

<v-click>

- Also, fun fact, Vue versions are anime titles

</v-click>

<div class="flex flex-wrap justify-center">
  <img v-after class="max-h-110px " src="/public/images/versions/3.2.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/3.0.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.7.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.6.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.5.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.4.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.3.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.2.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.1.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/2.0.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/1.0.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/0.12.jpeg"/>
  <img v-after class="max-h-110px " src="/public/images/versions/0.11.jpeg"/>
</div>

<style>
.slidev-vclick-target {
  transition: all 1000ms ease 10ms
}

.slidev-vclick-hidden {
  transform: scale(0);
}
</style>

<!-- 
3.2 August 5, 2021 Quintessential Quintuplets
3.1 June 7, 2021 Pluto
3.0 September 18, 2020 One Piece
2.7 July 1, 2022 Naruto
2.6 February 4, 2019 Macross
2.5 October 13, 2017 Level E
2.4 July 13, 2017 Kill la Kill
2.3 April 27, 2017 JoJo's Bizarre Adventure
2.2 February 26, 2017 Initial D
2.1 November 22, 2016 Hunter X Hunter
2.0 September 30, 2016 Ghost in the Shell
1.0 October 27, 2015 Evangelion 
0.12 June 12, 2015 Dragon Ball
0.11 November 7, 2014 Cowboy Bebop
0.10 March 23, 2014 Blade Runner
0.9 February 25, 2014 Animatrix
0.8 January 27, 2014
0.7 December 24, 2013
0.6 December 8, 2013

 -->


---

# Community and events
- Started as a few developers Evan You contacted directly after contributing to the project for a while
- Contributing patterns and guidelines were developed around Vue 1, community events led by Evan, Anthony Fu and eventually other members of the industry like Sarah Drasner
- Evan You as an active community developer, created chapters for US and China and eventually the whole world
- Pieces of the ecosystem, such as Pinia and Vite have become their own community beacons

<div class="flex justify-center">
  <img class="max-h-80" src="/public/images/vueamsterdam_one.png" />
  <img class="max-h-80" src="/public/images/vueamsterdam_2.jpeg" />
</div>

<!-- Links -->
---
src: ./links.md
---

---



<div class="h-full w-full flex justify-center place-content-center">
  <span>Q&A</span>
  <h1 class="text-2xl">And Thank You!</h1>
</div>

<logos-vue class="3x1 animate-ping" />
