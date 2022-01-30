---
layout: post
title:  "My Time Working On Old School RuneScape's Engine Team."
type: "Personal Blog"
color: "background-color: firebrick"
summary: "I was given the opportunity to work on engine programming for Old School RuneScape’s C++ Client, this helped me learn lots about how game engines work."
author: amyelliott
date: '2021-08-17'
category: ['personal', 'jagex', 'reflection', 'development', 'improvement']
thumbnail: /assets/img/posts/JGXRunescape/cover.jpg
keywords: personal, jagex, reflection, development, improvement
permalink: /blog/my-time-working-on-runecape/
usemathjax: true
---
<!---Keep this here-->
<!---Part of the collapsible group items // Ref: https://codepen.io/nhembram/pen/XKEJJp -->
<script>
     $('.panel-collapse').on('show.bs.collapse', function () {
        $(this).siblings('.panel-heading').addClass('active');
      });

      $('.panel-collapse').on('hide.bs.collapse', function () {
        $(this).siblings('.panel-heading').removeClass('active');
      });
</script>

<img src="/assets/img/posts/JGXRunescape/1.jpg" style="object-fit: cover; height: 500px; width: 100%; object-position: 0 50%">
<p>This blog is a continuation of my previous blog when I talked about my first two months at Jagex on the Unannounced MMORPG team.<br /><strong>I would recommend that you read that one before this!</strong></p>

<div class="row" style="padding: 20px">
  <div class="card blog-post" style="border-radius: 50px; width: 100% !important">
    <a href="/blog/what-ive-learnt-working-on-jagexs-unannounced-mmorpg" style="padding: 0px" target="_blank">
      <div class="card-body center">
              <h4 class="card-title">What I've Learnt Working On Jagex's Unannounced MMORPG</h4>
          <hr>
          <h6 class="card-subtitle mb-2 text-muted">Jul 17, 2021</h6>
          <p class="card-text">One morning, I woke up to an email titled 'Welcome to Jagex Games Studio' - I could barely believe it!</p>
      </div>
    </a>
  </div>
</div>

<p>During the final month of my internship at Jagex, I worked on <strong>Old School RuneScape</strong> on their <strong>Engine team</strong> where my job was to work on the <strong>enhancement of the RuneScape engine</strong> and associated systems.<br />My last month went by very fast but despite that, I managed to learn loads and do loads of new things!</p>
<p>As I had already been at Jagex for two months the onboarding wasn't as long, I had a few introductory calls with the Engine team to meet everyone and learn about what they work on.</p>
<hr>
<img src="/assets/img/posts/JGXRunescape/2.jpg" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">What I've learnt</h3>
<p>I've learned tons working on the Old School RuneScape engine team.<br />An example of this is the <strong>many different tools that are used in a live game</strong> like how content and engine are separated with Perforce for content and Git for the engine!<br />Intellij was used for Java and server code, Visual Studio (which is my default IDE!) for the C++ client code, some Python scripts to build solutions, and GitBash to run Git commands!</p>
<p>Through working on the engine team at Old School RuneScape I've learned a bit about <strong>how engine development compares to gameplay programming</strong>.<br />There's a lot of comparisons which I could make about their commonalities and differences, the main difference being that engine development isn&rsquo;t always player-facing (which is an obvious one) &ndash; I find both types of development great fun anyway!</p>
<p>Working on a live game is another key learning point for me, I've learned about how (in general) they&rsquo;re different in comparison to a game in pre-production.<br />With a live game, there are loads that I had to set up before I dove into the code, and there are many different branches! It usually takes longer to see your changes in the live game in comparison to a game in pre-production as the live game has to go through many different stages like code reviews and QA! This may be different for every game though! I&rsquo;ve also learned that, as well as a live game having many people working on it, there are also loads of different roles and teams which work on different aspects of the live game.<br />Tools like <strong>Jira</strong> are used to manage everyone&rsquo;s work, and <strong>sprints</strong> are more common to ensure everyone is on track with their work!</p>
<p><strong>Git Bash</strong> and using Git commands was one of the big things which I've learned out of all the tools I've used. I've not really used Git with commands before, but I did use Git with UI, I liked using TurtoiseGit and GitHub Desktop previously. Now I know how Git works with some commands!</p>
<p>I used <strong>C++</strong> when working on the <strong>Steam engine</strong>, and through doing a client-side ticket I've learned lots about <strong>logic, rendering, being efficient with my code, and how code efficiency compares between a live game and a game in pre-production.</strong><br />I also learned about the process of what the RuneScape content developers do through adding some <strong>RuneScript code</strong> which printed something in the game chatbox, and during another call with some content developers, I learned about how to add an NPC into the game with decision dialogue which either ended up with the player battling the NPC or starting a quest for the NPC.<br />This helped when it came to adding in sprites and packaging them as adding sprites was part of one of the tasks I was working on, and it is something content developers usually work with.</p>
<hr>

<img class="image-heading" src="/assets/img/posts/JGXRunescape/mention.PNG" style="height: 200px !important">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">What I've done</h3>
<p>One of the main things I've worked on when working on Old School RuneScape's engine team has been officially released on the Steam client! The <a href="https://secure.runescape.com/m=news/group-ironman?oldschool=1" target="_blank" style="padding:0px !important">newspost here</a> mentions this too!</p>
<p>It's a volume slider for the title screen! </p>
<p>This had to be coded from complete scratch, and I had to figure out the most efficient way to render in the volume bar sprites for changing the volume! <br />Doing this in the codebase meant I needed to learn about all the different systems to do with inserting sprites and saving data for the next time the player opens the client!</p>
<div class="video-container" style="padding-top: 0px !important">
    <iframe src="https://drive.google.com/file/d/1foSvjsgSucx8CZFhu_vlCnjHB73p9Fcg/preview" width="100%" frameborder="0"></iframe>
</div>
<hr>
<img src="/assets/img/posts/JGXRunescape/3.jpg" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Extracurricular Activities & Work</h3>
<p>There are lots of things that I&rsquo;ve done outside of my role which was fun to do with Jagex.<br />For example, a Tech Social, where lots of people got together from the tech teams and played games. We played a drawing game and a few online card games! This really helped me with meeting new people from other teams which I might have not met otherwise!</p>
<p>I also decided to travel up to Cambridge on my own accord <strong>to see what it's like to work in the studio</strong> for a week despite it being empty due to renovations and many people working from home.<br />I quite liked working in the studio, it was a different environment from working at home. At home, I'm surrounded by all of my consoles, posters, and gaming bits, and I&rsquo;ve grown comfortable working in that environment, but in the studio, I'm in an open office space where I can talk to the few people who are there and grab a coffee in one of the kitchens! I feel as if I can be a lot more social in an office!<br />After work in the studio, I went to many places with different groups of people from Jagex! On one of the evenings, I went to a pub, called The Golden Hind, and on another evening, I went to a lovely Japanese restaurant to eat some noodles and dumplings, and another evening I had some pizza, and on the final Friday evening, I went to the Milton Country Park&rsquo;s Food Court! It&rsquo;s an understatement to say I was full! I had a really great time though!</p>
<p>Another activity that I was able to do was go on the <strong>company live stream</strong> to talk to <strong>hundreds</strong> of people at Jagex about how my internship went!<br />This was great fun to do!<br />Similar to this I came into the studio again nearer the end of my internship to record a <strong>promotional video</strong>!</p>
<p>I also asked to be a <strong>panelist</strong> in one of the <strong>Old School RuneScape Q&amp;A Twitch live streams</strong> where I answered questions about my internship. This was a little more challenging as there were <strong>thousands</strong> of people watching live who know much more about RuneScape than I do! But nevertheless, it was great fun to do!</p>
<div class="video-container" style="padding-top: 0">
    <iframe src="https://www.youtube.com/embed/8eg0Re1GqjM" width="100%" frameborder="0"></iframe>
</div>
<p>I decided to do some <strong>content dev</strong> after work nearer the end of my internship to see what working on content was like. So, I talked to some of the content developers and <strong>tried to make some of my own quests for Old School RuneScape!</strong><br />This was great fun as I learned about the process which a Content Developer goes through from start to end!<br />I didn&rsquo;t really have too much time to do this though because of how late into my internship I asked to do it, but I managed to work on some <strong>detailed quest briefs</strong> and look through some RuneScript code to see how other quests work!</p>
<hr>
<img src="/assets/img/posts/JGXRunescape/4.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Conclusion</h3>
<p>I've learned that as I&rsquo;ve only spent a month on Old School RuneScape, it was hard to do much because the codebase was so large (And some of it was super old!) - It took a while to get used to it! But either way, <strong>I was able to implement something which I was very proud of!</strong> There are loads of differences between working with a custom engine and working with an engine like Unreal Engine, and there are many differences between working on gameplay programming and engine programming. But overall, this has taught me that <strong>it&rsquo;s not too hard to get used to a new engine, and I shouldn&rsquo;t be scared of approaching new tools!</strong></p>
<p>In conclusion, I've really enjoyed being an engine developer and I've really liked working on a live game! It&rsquo;s taught me how game engines work under the hood and the <strong>many different paths which programmers can take in the games industry alone!</strong></p>
<p>I'm thankful to have been given the opportunity to do this internship!</p>