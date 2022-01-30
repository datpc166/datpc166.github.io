---
layout: post
title:  "What I’ve Learnt Working On Jagex’s Unannounced MMORPG."
type: "Personal Blog"
color: "background-color: firebrick"
summary: "One morning, I woke up to an email titled 'Welcome to Jagex Games Studio' - I could barely believe it!"
author: dylan
date: '2021-07-17'
category: ['personal', 'jagex', 'reflection', 'development', 'improvement']
thumbnail: /assets/img/posts/JGXUnannouncedMmorpg/cover.png
keywords: personal, jagex, reflection, development, improvement
permalink: /blog/what-ive-learnt-working-on-jagexs-unannounced-mmorpg/
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

<img src="/assets/img/posts/JGXUnannouncedMmorpg/cover.png" style="object-fit: cover; height: 500px; width: 100%; object-position: 0 50%">
<div class="WordSection1">
<p>One April morning, I woke up to a great surprise, I had gotten an email titled: &lsquo;<em>Welcome to Jagex Games Studio</em>&rsquo;, I was quite tired at the time so I had to read the email a few times to realise it was real.</p>
<p>This email offered me a once-in-a-lifetime <strong>Game Engineering Internship</strong> at <strong>Jagex Games Studio</strong>, I immediately accepted the offer and went to tell everyone!</p>
<p>Before this Internship, I had not played RuneScape, so between the time of accepting my offer and starting my first day at Jagex, I was fighting Goblins, sheering sheep, and completing a handful of quests! I&rsquo;m not really an MMORPG type of person, but I must admit, I found myself spending hours exploring the colossal medieval fantasy world of Gielinor and making friends!</p>
<p>I started my first day in the middle of May, a new face in the games industry, I had <em>never</em> worked a job like this before, I was excited to see what it was like to work in a tech industry, and to see what work was ahead of me! And it was <em>so</em> much different from the retail job I was used to working!</p>
<p>Jagex hired <strong>4</strong> new interns, <strong>2 Game Engineers</strong> (including me) and <strong>2 Artists</strong>, we all quickly became good friends. All of us were split up within the many teams in Jagex to work in different areas.</p>
<p>I was put on the unannounced MMORPG (For the sake of ease, I&rsquo;ll be calling this &lsquo;The MMORPG&rsquo; throughout the blog) project for <strong>2 months</strong>, this game is currently in <strong>pre-production</strong>, and the <strong>remaining month</strong> of my internship would be spent working on <strong>Old School RuneScape</strong>, which, as I&rsquo;m sure you&rsquo;re aware is a <strong>live</strong> game. I like this structure as it <strong>allows me to experience game development at different stages</strong>.</p>
<p>In this blog post I will be talking about the 2 months I spent working on the MMORPG, and as you are probably aware, the game I&rsquo;m working on is Unannounced; so, I can&rsquo;t say too much about the title or talk about specifics, therefore a lot of this blog would be <em>anonymised</em>, mostly talking about <strong>tools I&rsquo;ve learnt</strong> to use and <strong>programming skills</strong> I&rsquo;ve picked up along the way.</p>
<p>Jagex were amazing at helping me settle in, they prepared plenty of introductory calls with many different people from different teams to help me with IT, learning about the company amongst a few other things, as well as calls with a handful of people from the MMORPG team, introducing me to the ideas behind the game, and the codebase. Within the team, we also had a few social evenings, where we played games like Golf With Your Friends, these social evenings were great fun!</p>
<p>I decided to contact other people in many different roles and teams to talk to them about what their role is to help me learn more about the games industry. I&rsquo;ve also talked to many different programmers and asked them about their journey into the games industry and any tips so I can learn from them and make some friends!</p>
<p>&nbsp;</p>
<hr>
<img src="/assets/img/posts/JGXUnannouncedMmorpg/tools.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">What I've learnt</h3>
<p>At Jagex, I was using a number of tools which I had never used before, these tools were used for <strong>source control</strong>, <strong>general game development</strong>, <strong>documentation</strong>, and <strong>task organization</strong>.</p>
<p>The game itself is being made in <strong>Unreal Engine</strong>, and I was working on the game during the time it was developed using <strong>UE4</strong>.</p>
<p>I&rsquo;ve personally always been hesitant on using Unreal Engine as I&rsquo;ve been pretty comfortable using Unity, having to use a different engine was a <em>challenge</em> at first, but a <em>welcome</em> one, it taught me that <strong>the best way to adapt and use new tools is to just use them</strong>, engines change all the time in the games industry, so I&rsquo;m happy that I now have the <strong>confidence</strong> to approach whatever comes my way.</p>
<p>Using C++ with Unreal Engine was another hurdle, I had tried using it beforehand and found the macros confusing, which in turn made me run into many problems, so this internship taught me how to use these to develop many <strong>game mechanics</strong> which involved the use of <strong>networking</strong> and <strong>replication</strong>, that was another thing I was new to as well, a handful of the other skills which I&rsquo;ve learnt were how to use <strong>delegates</strong> and <strong>interfaces</strong>.</p>
</div>
<div class="WordSection2">
<p>Some of the highlight contributions of mine within the MMORPG include but aren&rsquo;t limited to:</p>
<ul>
<li><strong>Player Name Mechanic </strong>&ndash; The player can put in their own username and it appears above their head for themselves and everyone else playing to see.</li>
<li><strong>Player Respawning </strong>&ndash; The player respawns a few seconds after they die.</li>
<li><strong>Enemy Respawning </strong>&ndash; Enemies respawn a few seconds after being killed.</li>
<li><strong>XP &amp; Levelling </strong>&ndash; Players can gain experience points after battling enemies, once they get a certain amount of experience points, they can level up.</li>
<li><strong>Debug Commands </strong>&ndash; I&rsquo;ve implemented a handful of debug commands to help with playtesting.</li>
</ul>
<p><strong>Source control</strong> is another important tool, I&rsquo;ve used Git beforehand, but for this project <strong>Perforce</strong> was used with <strong>Swarm for code reviews</strong> alongside <strong>Unreal Game Sync</strong> to keep all the project files up to date.</p>
<p>Perforce was easy enough to learn as it is similar to Git, and through using Perforce and having team members to ask questions, <strong>I&rsquo;ve learned how to fix conflicts</strong> &ndash; before this was something I was worried to approach in case I messed it up.</p>
<p>Code Reviews is something new to me, beforehand, my teams would just push the code into the main branch or their own branch without any code review process, but I found doing code reviews quite fun! It&rsquo;s really interesting to see other peoples process to making a mechanic, and code reviews allowed me to ask questions about their code and other people to give me feedback, which in turn helped me learn more about the codebase, and how to improve my code.</p>
<p><strong>Documentation</strong> and <strong>task organization</strong> is very important in ensuring everyone is staying as productive as possible, one of the main productivity tools the team used was an online task manager called <strong>BaseCamp</strong>, which is now a tool I&rsquo;m using in my personal time as well.</p>
<p>Basecamp is like a collection of tools which can be used to open up discussions, to-do lists and automatic check-ins. To-do lists were used and they helped me organise the work which I was going to do throughout the week and ensured I was on track to finish on time.</p>
<p>During the development of the game, there is sometimes things which need to be documented, whether that be help guides on how to do something, or design decisions, on this MMORPG team, we gathered our documentation using a tool called <strong>Confluence</strong>.</p>
<p>I quite enjoyed documenting my findings, some of the stuff I&rsquo;ve documented were a <strong>how to play document</strong>, which got used quite a lot as the MMORPG didn&rsquo;t have a tutorial in it yet, and <strong>a few programming cheat-sheets</strong>, to help me learn and help others learn as well.</p>
<p>Documentation is something which I will definitely be doing in the future for my own projects.</p>
<p>&nbsp;</p>
<hr>
<img src="/assets/img/posts/JGXUnannouncedMmorpg/extracurricular.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 30%">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Extracurricular Activities & Work</h3>
<p>Whilst working at Jagex, I&rsquo;ve participated in many activities outside of my role, and learnt lots through them.</p>
<p>One of the first activities I attended was the <strong>Diversity Champion Training</strong>, which was a group workshop where we chatted about <strong>diversity in the games industry</strong>. During this we talked about how we could make the games industry more diverse, and how to be there for anyone to talk to about any issues they may be having.</p>
<p>We also talked about the painting <a href="https://en.wikipedia.org/wiki/Room_in_New_York" target="_blank" style="padding:0px !important">&lsquo;A Room In New York&rsquo;</a> by Edward Hopper, through open discussion about what was happening in the photo we concluded that we can&rsquo;t judge things by how we see it, as there could be many sides to every story. I learnt that <em>I should be the change that I want to see!</em></p>
<p>Another activity I participated in was the <strong>Into Games Virtual Work Experience</strong>&nbsp;&ndash; I volunteered through Jagex to help <strong>mentor college students</strong>, and they had to work as a team to produce a game design document and game prototype in accordance to a brief, this was the first time I&rsquo;ve ever done mentoring, and although these students were only a few years younger than me, and I was an intern, so I was new to the games industry, I decided to bite the bullet and try my hand at mentoring.</p>
<p>I realised through this that I really enjoy it! I prepared a handful of slides for each session with the students, and they were able to produce some great work by the end of the week! I talk more about my experience with this mentoring in this blog post <a href="/blog/guiding-students-through-designing-prototying-a-game/" target="_blank" style="padding:0px !important">here</a></p>
</div>
<p>I was also able to go to Cambridge to check out the Jagex studio too! An <strong>Intern Social Day</strong> was arranged for all of the interns to meet up, have a tour around the studio, meet some people from Jagex and look around Cambridge!</p>
<p>I&rsquo;ve never been to Cambridge, seen a game studio, or been in my own hotel room before, so this was a whole load of new experiences!</p>
<p>The studio was amazing, it had artwork and foam sword props everywhere, there was loads of plants, and kitchens on every floor with Jagex branded mugs and glasses, the desks were separated into their different teams, and there was even a cafeteria and pub!</p>
<p>After we saw the studio, we had a nice picnic outside for lunch, and then went into Cambridge town to do champagne punting, and have an evening meal. I had great time getting to know everyone!</p>
<p>The next time I went to Cambridge was for the MMORPG offsite.</p>
<p>The offsite was to discuss the goals of the MMORPG and plans for the future, and we had these meetings in a beautiful fancy conference room in a hotel we stayed in. During the talks, we had tea, and small snacks.</p>
<p>We also had lunch at the hotel and went into the Cambridge town for a big group dinner. It was great fun getting to meet the MMORPG team in person!</p>
<p>&nbsp;</p>
<hr>
<img src="/assets/img/posts/JGXUnannouncedMmorpg/tea.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 60%">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Conclusion</h3>
<p>Overall, I&rsquo;ve learnt many things working on Jagex&rsquo;s unannounced MMORPG team for 2 months during my internship. It may not seem like a long time, but within those two months I&rsquo;ve learnt many programming skills, different tools, and the different types of roles in the games industry. I&rsquo;ve also noticed a boost in my confidence, speaking skills and capability to learn and adapt to new things.</p>
<p>This internship has made me realise what my goal is for the future: I hope to one day grow my skills in <strong>programming</strong> and <strong>leadership</strong> so I can become a <strong>Lead Programmer</strong>!</p>
<hr>
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Next - The Final Month Of My Internship.</h3>

<div class="row" style="padding: 20px">
  <div class="card blog-post" style="border-radius: 50px; width: 100% !important">
    <a href="/blog/my-time-working-on-runecape" style="padding: 0px" target="_blank">
      <div class="card-body center">
              <h4 class="card-title">My Time Working On Old School RuneScape's Engine Team</h4>
          <hr>
          <h6 class="card-subtitle mb-2 text-muted">Aug 17, 2021</h6>
          <p class="card-text">I was given the opportunity to work on engine programming for Old School RuneScape’s C++ Client, this helped me learn lots about how game engines work.</p>
      </div>
    </a>
  </div>
</div>
<br/>