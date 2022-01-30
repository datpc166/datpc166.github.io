---
layout: post
title:  "A Year Of Technical Games Development"
type: "Personal Blog"
color: "background-color: firebrick"
summary: "In this blog, I discuss my Technical Games Development module, And how it helped me learn to develop my core team working skills for use in games development."
author: amyelliott
date: '2021-06-22'
category: ['personal', 'reflection', 'development', 'improvement']
thumbnail: /assets/img/posts/YearTDEMO/cover.png
keywords: university, gamejam, unity
permalink: /blog/a-year-of-technical-games-development/
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

<img src="/assets/img/posts/YearTDEMO/cover2.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 35%">


<!-- -------------------------------------------------------------------- -->
<!-- This is for the main description of the game, this is very important -->
<!-- -------------------------------------------------------------------- -->
<p style="word-wrap: normal">One of my favourite modules in University has to be my Technical Games Development module (TDEMO), this module helped me learn to develop my core team working skills for use in games development, as well as this, it helped me develop my awareness of group dynamics, and gave me the opportunity to test out any potential career paths and the problems usually faced in those. <br /><br /> For this module, I made <b>5 games</b>, and in this blog I will be discussing and comparing a handful of mechanics & problems from each of them, I would also be reflecting on those games and what I've learnt from them, and how the materials learnt in other modules have impacted my approach to certain games and mechanics made in this module.</p>

<hr>

<!-- -------------- -->
<!-- Rewriting page -->
<!-- -------------- -->
<h2 style="text-align:left; margin-top: 20px; margin-bottom: 20px">Blocky Road</h2>
<img src="/assets/img/posts/YearTDEMO/blockyroad.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 35%">
<p>Blocky Road is a <b>puzzle game</b>, designed to fit around the well-known <b>'Hypercasual' genre.</b>  I had to do some research into this genre before starting to make sure I was completely clear on what type of game I could make so I can begin thinking of ideas, this definition on Wikipedia summarised the genre very well: <a href = "https://en.wikipedia.org/wiki/Hyper-casual_game" target="_blank" style="padding: 2px"> “A hyper-casual game is a mobile video game which is easy-to-play and usually free-to-play; they also feature very minimalistic user interfaces.” </a> (‘Hyper-Casual Game’, 2021) <br /> My goal for this game jam project was to make a game which can do all of that, I had a week to make this game, but I couldn’t just work on this game as there was other university work to do as well within that week, so one of my main challenges was to be able to make an enjoyable Hyper casual game <b>within 9 hours.</b> </p>
<div class="video-container">
    <iframe src="https://drive.google.com/file/d/1xUnJNABDKprSjj6J-bpHVCQsT5F683Ps/preview" width="100%" frameborder="0"></iframe>
</div>
<div class="panel-heading active" role="tab" id="headingOne">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseDevDiary" aria-expanded="true" aria-controls="collapseDevDiary" style="font-size: 18px; padding: 0px !important">
        Development Diary - What Is It, Why Am I Doing It & How Can I Keep Up With It?
    </a>
    </h2>                                
</div>
<div id="collapseDevDiary" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne">
    <div class="panel-body">
        <img src="/assets/img/posts/YearTDEMO/developmentlogs.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 35%; margin-top: 20px; margin-bottom: 20px">
        <p>Development Diaries are simply what the name suggests, <i><b>a write up of the development of something in a diary structure</b></i>, I had <a href = "https://amyelliottuop.wordpress.com/technical-game-development-tdemo/game-2-23-10-20/" target="_blank" style="padding: 2px">written one myself</a> throughout the development for Blocky road to document my process. Initially, however, I found that it had been <b>difficult to keep up with this on a day-to-day basis</b>, as I had a lot to write about in little time. I thought about how I can write development logs <i>differently</i>, so I don’t have to write them each day. <br /> One reason I like writing Development Diaries is because it gives me <b>something to look back, and reflect on when I grow my skills, and it can look really good on my portfolio!</b> Another reason is, on a blog post I read, Sokolovski (2020) stated that <a href = "https://www.thegamer.com/dev-diaries-direct-updates-habit-game-studios/" target="_blank" style="padding: 2px">“Transparency and engagement with fans can positively contribute to the player-base's impression of the studio and, in turn, make them want to play the game even more, therefore attracting even more potential players.”</a> This really motivated me to keep up with my own diaries. <br /> To make sure I’m able to write <i>good</i> development diaries without forgetting important details, I figured the best way to approach this for this game in particular was to <b>build up a list of tasks</b> which I’ve done on Trello, and at the end of development, update my development diary, for other projects with a longer production time, I would update my development diary every-other-day. <br /> <b>It’s useful to be able to use Trello to note down what I was able to do, as otherwise I may have forgotten about them!</b> <br /> When I was doing this, <b>I was relying on my memory to remember what I have done on each task</b>, as I only noted down what the task was and not what I done to complete it! I think to improve, <b>I could’ve left comments or a short sentence explaining what I did for the task with some images to support that.</b></p>                                        
    </div>
</div>
<div class="panel-heading active" role="tab" id="headingTwo">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseChargeUI" aria-expanded="true" aria-controls="collapseChargeUI" style="font-size: 18px; padding: 0px !important">
        Charge Movement User Interface
    </a>
    </h2>                                
</div>
<div id="collapseChargeUI" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
    <div class="panel-body">
        <img src="/assets/img/posts/YearTDEMO/chargemovement.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 35%; margin-top: 20px; margin-bottom: 20px">
        <p>For my game, I needed some way of telling the player how much they can charge up their movement before they move, so I came up with a circle charge UI design, Quintans (2013) gave an example of Good UI by mentioning <a href = "https://gamedevelopment.tutsplus.com/tutorials/game-ui-by-example-a-crash-course-in-the-good-and-the-bad--gamedev-3943" target="_blank" style="padding: 2px">“the role of a good UI is to provide relevant information clearly and quickly, and to get out of the way once it has done its job.”</a> – So, I took that into consideration when implementing the charge movement which follows the players mouse. <br /> The reason why I had to implement this way of movement is because I couldn’t use the WASD keys to move the player character, instead, I had to think of how to <b>move the player with a single key</b>, so the entire game can be played with one key. This makes the game <b>easy-to-play for anyone.</b> <br /> For the visual side of the charge movement, I made 2 transparent rings in Photoshop, and applied the code of the charging to the fill of one of the rings inside of Unity. <br /> I got this working pretty quickly, as I already had all the code I needed in place, but there was a bug which I had, which I couldn’t fix in the time I had. <br /> For me, this was one of the most <b>significant bugs</b> in the game, and in more detail, the bug was that the bar would fill up, and go up to being full, but then I would want it to go back to 1, instead, the bar never got to 4, and then skipped right to 1, so in the end, I made the bar so it stayed full once you’ve already charged it to 4. <br /> <b>At the time I felt this was fine</b>, but looking back onto this broken UI now, <b><i>it doesn’t make any sense to a new player</i></b>, and may confuse them when they’re playing. <br /> This understanding will be essential to me going forward, <b>if I ever want to further develop this game, I know what to work on and fix first.</b></p>
    </div>
</div>
<h3 style="margin-top: 20px">Reflection on Blocky Road</h3>                                
<p>Overall, making Blocky Road was a <b>creative, and technical challenge</b> for me, but a challenge I was happy to take on! It allowed me to <b>push my creativity, whilst also trying to stick to the genre</b> – Which is one I’ve never explored before! <br /> Having experienced developing one of my own hyper casual games I now know I really enjoy making them, and <b>it’s something I can look into for any future games!</b> Something I’m interested in doing with this game in the future, is <b>putting it on the Google Playstore</b>, as this game was <b>designed from the ground up with mobile gaming in mind.</b> <br /> My <b>TOGA</b> (Tools for Games & Animation) module helped me out with making this game as well, as during that module, we were tasked to <b>design simple systems to use in simple text-based games</b>, and though this game isn’t text based, it is simple, so I was able to design my game systems <b>with those good practices in mind.</b></p>                  
<h3 style="margin-top: 20px">Ranking & Player Feedback</h3>  
<p>This game ranked <b>#1</b> Overall, which I was really happy with! <br /> There was some positive feedback which I got when I first uploaded the game to the game jam! I uploaded the game early so I could get any feedback on bugs and do a version 2 of the game before the end of the game jam! <br /> Some of the main bugs or quality fixes which I had gotten in the feedback was minor, and only required quick fixes which I would be able to do with the time I had left on the game jam, and once these were fixed, a version 2 of the game was released!</p>
<iframe frameborder="0" src="https://itch.io/embed/801093?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://amy-elliott.itch.io/blockyroads">Blocky Road by Amy Elliott</a></iframe>                              

<hr>
<h2 style="text-align:left; margin-top: 20px; margin-bottom: 20px">Pet Pal</h2>
<img src="/assets/img/posts/YearTDEMO/petpal.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 35%">
<p>Pet Pal is a <b>clicker game</b>, designed to fit around the <b>‘Incremental’ genre.</b> I knew this genre pretty well from the famous mobile and browser game Cookie Clicker where <a href="https://en.wikipedia.org/wiki/Cookie_Clicker" target="_blank" style="padding: 2px">“The user initially clicks on a big cookie on the screen, earning a single cookie per click. They can then spend their earned cookies upon purchasing assets that automatically produce cookies.”</a> (<i>‘Cookie Clicker’</i>, 2021). <br /> My teams' goal for this game jam was to make a simple 2D incremental game, it was the first group game jam in this module, and I was in a team of 5, including mysef, so we had to learn how to work together. Our group had <b>a week to make this game</b>, but as we were a group there was less stress as each of us were working on a specialism.</p>
<div class="panel-heading active" role="tab" id="headingThree">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGroupLeadPP" aria-expanded="true" aria-controls="collapseGroupLeadPP" style="font-size: 18px; padding: 0px !important">
        Being A Group Lead For The First Time - What I Did, Why I Did It, & How I Made Sure Everything Turned Out Okay
    </a>
    </h2>                                
</div>
<div id="collapseGroupLeadPP" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
    <div class="panel-body">
        <img src="/assets/img/posts/YearTDEMO/pp1.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 35%; margin-top: 20px; margin-bottom: 20px">
        <p>One thing I have always wanted to do was be a <b>group lead for a game jam</b>, and this is because <b>I wanted to know what the workflow was like, and if I would be a good lead.</b> <br /> At first, I thought that being a group lead meant that I deal with some project management and have <i>plenty</i> of time to work on other things for the game, in my case, the programming, but <b>I quickly learnt that this wasn’t the case.</b> <br /> <br /> As I was new to leading, I had to learn a bit more about it. Kantilaftis (2014) wrote an excellent blog post called <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">‘How To Form A Solid Indie Game Development Team’</a> – This blog post gave me an insight on the many different roles that could be taken on in Games Development excluding the handful which I already knew about. <b>Kantilaftis’s description of a Project Manager helped me realise what my role was</b>, as quoted by her; <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">“(their) responsibility is to make sure the team works fast and efficiently.” </a> She followed this by answering our burning question of <i><b>why</b></i> it should be done; <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">“(they) will be the one that sets milestones for the team and sees to it that they are achieved in a reasonable time frame”</a> and <i><b>how</b></i> to do so; <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">“This involves motivating team members that fall behind and making sure everyone is performing their tasks.”</a> <br /> To make sure members are <b>performing their tasks, staying motivated and not falling behind</b>, I made a <b>working schedule</b> for the group, as it was only a weeklong game jam, we <b>each</b> put in around <b>7 to 9 hours</b> into this game. <br /> For me, the most <b>useful</b> way I knew to stay on track was to <b>not cram work in</b> at once, but to instead <b>work in chunks of 3 hours</b>, this ensures we can <b>stay focused</b>, we aren’t putting in <b>too many hours</b> and we are working to the <b>best of our abilities</b>. At the time, <i><b>I didn’t think about how everyone may have different schedules</b></i>, alternatively, keeping the team on a work schedule <i>can be good</i>, as it’s not long term, and it ensures everyone is working at the same time. <br /> <br /> On my <a href="https://amyelliottuop.wordpress.com/technical-game-development-tdemo/game-3-30-10-20/" target="_blank" style="padding: 2px">development diary</a>, I wrote about how some members <b>weren’t available during the sessions</b>, so I trusted them to work on their own accord to reach the same amount of work hours as everyone else in the group, <b>I had no way of checking the working hours</b>, so it was <b>entirely possible</b> that group members who aren’t available during the scheduled hours may <b>overwork or underwork</b> themselves, <b><i>in the future</i>, if I were to lead another project, this is something which I could do further research into, and improve on</b>. To check our members were performing their tasks, for each working session, we joined a group call, and during this group call, <b>I checked where everyone is</b> and their <b>plan of action</b> for the session, I would also work on <b>assigning tasks</b> by sharing my screen and <b>going through our groups Trello task list.</b> We would remain on the call whilst we worked just to <b>simulate a work environment.</b></p>
    </div>
</div>
<div class="panel-heading active" role="tab" id="headingFour">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseSourceControl" aria-expanded="true" aria-controls="collapseSourceControl" style="font-size: 18px; padding: 0px !important">
        Teaching Source Control
    </a>
    </h2>                                
</div>
<div id="collapseSourceControl" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingFour">
    <div class="panel-body">
        <img src="/assets/img/posts/YearTDEMO/pp2.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 10%; margin-top: 20px; margin-bottom: 20px">
        <p>Teaching and explaining source control is <b>very important</b>, especially for a group project like this, since we are all working on the same Unity Project, but I thought to make things easier and to get less conflicts, I would <i>only set up, and teach git to the programmers of the group</i>, so that means Layla and Fabio, it would be extra unneeded work to set up git for the artists for a game which we are only going to work on shortly. <br /> I <b>explained source control</b>  and <b>how it worked</b> to <b>everyone</b> on a discord call, and then guided Layla and Fabio through <b>how</b> to install Github Desktop and <b>use it</b> with the games repository, which I had set up with an empty Unity Project. <br /> I <b>explained why it is important</b> to have <b>useful, descriptive comments on each commit</b> and how they should try not to <b>work on the same stuff</b> at the same time to <b>avoid coming across conflicts</b> (We never even got one!) We avoided working on multiple branches and just <b>pushed all of our commits to the master branch</b>, since the game is only a small game. They both picked up how it worked <b>very quickly</b>, so in the end working on this game with source control made it so much easier then working on separate unity projects!</p>                                     
    </div>
</div>   
<h3 style="margin-top: 20px">Reflection on Pet Pal</h3>
<p>Overall, making Pet Pal was a great opportunity for me to <b>lead and teach</b>, which I’ve discovered is something I’m quite interested in, so now I know <b>leadership is something I can consider for any future careers.</b> For me, one of the most <b>significant experiences</b> arose from <b>teaching source control to the team</b>, as later on in the module, I found myself teaching source control multiple times for each game jam group. <br /> I personally didn’t like Pet Pal, so I don’t see it going much further than it has. I see clicker games like this quite boring, and the game itself isn’t unique, although given an opportunity to expand this game, I feel it would have to be <i>remade from the beginning again</i>, including all assets, with a more creative twist to the game to make it more unique. <br /> My <b>Image Creation</b> module helped me, and most likely my teammates out with making assets for this game, as <b>Photoshop was used to produce art assets for the game</b>, another module which I find helped the programmers was <b>TOGA (Tools for Games & Animation)</b> as at this point, the <b>programming fundamentals</b> were being taught, and these fundamentals were used in the game.</p>
<h3 style="margin-top: 20px">Ranking & Player Feedback</h3>
<p>This game ranked <b>#15</b> Overall, which is quite a low ranking, but I wasn’t too surprised given the simplistic gameplay, now I feel<b>we could’ve scored higher if we had been a little more creative</b> with the idea and having discussed our opinions on the game with the rest of the group a few months after we finished the game, <b>the other team members felt much the same.</b> <br /> I asked for feedback on my leadership from the rest of the group to see how I did and how I can improve. The responses which I have gotten were <b>all positive, which is great! </b> Key words which I have picked out from this feedback was that when leading the game, I showed that I was <b>“Organised”</b>, <b>“[Kept things] within scope”</b>, <b>“Ensured [the group] stayed on task”</b> and <b>“Made sure [the group] finished early so we could improve the game based on feedback”</b> – And for me, the most useful positive feedback which I got was the last point of finishing the game early to get feedback, as <b>for future games, I tried my best to enforce this idea.</b></p> 
<details> 
    <summary>Personal Feedback</summary> 
    <table>
        <tr>
            <th>Name</th>
            <th>Feedback</th>
        </tr>
        <tr>
            <td>Jacob</td>
            <td>Amy was our lead and a good one at that, she kept things organised and within scope as well as also doing some of our coding.  Very good team mate on top of being a lead.</td>
        </tr>
        <tr>
            <td>Layla</td>
            <td>Amy was an active team leader who ensured we stayed on task and made a good decision with ensuring we finished early so we could improve the game based on feedback.</td>
        </tr>
        <tr>
            <td>Lewis</td>
            <td>Amy was the lead for the group and I believe did code also, In terms of leading she did very well with keeping things organized and getting everyone to work. Overall was a good and useful leader.</td>
        </tr>
        <tr>
            <td>Fabio</td>
            <td>Amy was the leader, kept us on track, good programmer </td>
        </tr>
    </table>                        
</details>     
<details> 
    <summary>Teams Opinion On The Game</summary> 
    <table>
        <tr>
            <th>Name</th>
            <th>Game Rating</th>
            <th>Opinion</th>
        </tr>
        <tr>
            <td>Jacob</td>
            <td style="background-color: #a52a2a5e">3/10</td>
            <td>Clicker games are my one of my least favourite genre's within the entire market, but dispite this. I did enjoy working with everyone in this group and felt like we made a solid incremental clicker based game.</td>
        </tr>
        <tr>
            <td>Layla</td>
            <td style="background-color: #ff9a264d">4/10</td>
            <td>Although we did a good job at the game that we set out to create, we could've been more ambitious with our goals while remaining within the gamejam limits to create something more engaging to players.</td>
        </tr>
        <tr>
            <td>Lewis</td>
            <td style="background-color: #ff9a264d">5/10</td>
            <td>The game was well made and good though the theme wasnt all that interesting limiting what was capable.</td>
        </tr>
        <tr>
            <td>Fabio</td>
            <td style="background-color: #a52a2a5e">3/10</td>
            <td>The theme 'clicker game' wasn't interesting and i think we might have missed the mark on what makes a clicker gamer a clicker game but it did have comedic value bcuase of the sheep evalution </td>
        </tr>
    </table>                       
</details>      
<iframe frameborder="0" src="https://itch.io/embed/809572?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://laylamccahon.itch.io/pet-pals">Team ; : Pet Pal by LaylaMcCahon, xXbollerXx, Amy Elliott, Lewis Roberts, Jacob Kelly</a></iframe>             

<hr>
<h2 style="text-align:left; margin-top: 20px; margin-bottom: 20px">Poppin' Hoppin' Unlockin'</h2>
<img src="/assets/img/posts/YearTDEMO/pophop.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 35%">
<p>Poppin’ Hoppin’ Unlockin’ is a <b>puzzle game</b>, designed to fit around the <b>‘Platformer’ genre.</b> This genre is popular and most influenced from games such as Super Mario Bros because <a href="https://en.wikipedia.org/wiki/Platform_game" target="_blank" style = "padding: 2px"> “Its success as a pack-in led many companies to see platform games as vital to their success and contributed greatly to popularizing the genre during the 8-bit console generation.”</a> (‘Platform Game’, 2021). <br /> My teams’ goal for this game jam project was to make a stylish 3D platformer with a back story, we were all a bit more confident approaching this game jam as we had practice from the previous. Our group had <b>2 weeks to make this game</b>, but again, as we were a group there was less stress as each of us were working on a specialism. </p>
<div class="video-container">
    <iframe src="https://drive.google.com/file/d/1deLSTMYxZiBX5j6h-fKWi9XlJmI5nTYA/preview" width="100%" frameborder="0"></iframe>
</div>
<div class="panel-heading active" role="tab" id="headingFive">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGroupLeadPop" aria-expanded="true" aria-controls="collapseGroupLeadPop" style="font-size: 18px; padding: 0px !important">
        Being A Group Lead Again - What I Did Differently, Why I Did It, & How I Made Sure Everything Turned Out Okay.                                    
    </a>
    </h2>                                
</div>
<div id="collapseGroupLeadPop" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingFive">
    <div class="panel-body">
        <img src="/assets/img/posts/YearTDEMO/ph2.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 30%; margin-top: 20px; margin-bottom: 20px">
        <p>I decided to take the Group Lead role on again and this was to <b>improve</b> on anything I may have not done as well last time; and although my peer feedback on my leadership was all positive, <b>I knew there had to be other areas which I could improve in.</b> <br />Previously, I stated that <i>for Pet Pal I didn’t have time to do much programming</i> for the game, as all of my time was mostly spent on project management, <b>this time I wanted to make sure I can contribute to programming as well.</b> <br /> For me, I would've initially thought the most <b>significant difference</b> between leading this project and leading the previous is the <b>team size</b>, for this project we had a team of 8; and because of the team size difference, you would think there was more which I had to manage as the group leader, but having experienced this, I now realise that <b>leading a team of 8 is not much different from leading a team of 5!</b> Furthermore, I have learnt that this is most likely because of having team members which are happy to pull their own weight in the team, so there <b>wasn’t any conflicts</b> which I had to deal with in either of these games. <br /> Another relevant and useful experience this time leading the project has to be <b>reflecting</b> on what I’ve learnt previously. <br /> For this game, I decided to get <b>more input, in multiple areas from every member of the team</b>, as previously I felt like I didn’t do that. At the time I thought this would be a bad idea, and the team wouldn’t contribute, but I was <b>pleasantly surprised at how much input this team gave me!</b> <br /> An example of one of the inputs I asked for at the beginning of the game jam, was <b>I asked every team member what role they wanted to take on</b> for the development of the game, they could pick <b>whatever</b> they liked, if they wanted to try something new, or if they wanted to stick to something they were more comfortable with, I really enjoyed this as I felt like for the other gamejams which I’ve participated in, most people stick to a role which they know they can do well, or a role they were assigned, but <b>I personally feel like experimenting in different areas is one of the most valuable experiences you can get out of these gamejams</b>, and this is certainly something which I will be doing for any future gamejams which I lead. <br /> In addition to that, another input which I have taken from the team is about <b>opinions on the game’s development thus far</b>, one question in particular was about a main aspect of the game which we didn’t have time to implement. <br /> <b>I think the ability to give creative input, even in an area which you don’t specialise in is important</b>, a lack of creative input is commonly found in triple-a studios, and it’s called ‘Triple-a Fatigue’, many opinions on <a href="https://www.mcvuk.com/development-news/are-devs-suffering-from-triple-a-fatigue/" target="_blank" style="padding: 2px"> this article </a> state that with a lack of creative input, they don’t feel part of the games development, so I wanted to know the opinion of other game developers’ on this subject, and to do this <a href="https://docs.google.com/spreadsheets/d/111GM5brCa-JbQkPFiuStK_NycC4K4L20tEJ29bF5slM/edit?usp=sharing" target="_blank" style="padding: 2px"> I made a survey</a>, and some of the answers I got were very interesting and informative! The results which I have gotten from this indicate that there are <b>many pros and cons to creative freedom</b>, and it will certainly be something which I will be looking further into in the future.</p>                                    
    </div>
</div> 
<div class="panel-heading active" role="tab" id="headingSix">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseLvlMech" aria-expanded="true" aria-controls="collapseLvlMech" style="font-size: 18px; padding: 0px !important">
        Making The Basic Level Mechanics                                    
    </a>
    </h2>                                
</div>
<div id="collapseLvlMech" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingSix">
    <div class="panel-body">  
        <img src="/assets/img/posts/YearTDEMO/phu.gif" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">       
        <p>Specific tasks were shared out amongst the programmers of the team, and the majority of those tasks were to do with mechanics involving the player, so <b>I decided to take on level mechanics</b> myself, this involves things like visual cues to fade the screen between levels, to checking if the player has the key to complete the level by the time they reach the door. <br />Doing this as early as possible was <b>essential</b>, as I needed to build a <b>level template which can be worked with</b> when it comes to designing and implementing levels, and <b>levels isn’t something we want to work on last minute!</b> - This is because, like Weesner, (2011) states <a href="https://www.gamasutra.com/view/news/126332/Opinion_Classic_Problems_With_Level_Design.php" target="_blank" style = "padding: 2px"> “Level design is incredibly time consuming. It’s one of the few aspects of design that spans the entire development process from early prototyping to closing out final bugs!”</a> and <b>in my own experience</b> with making levels in gamejams starting the level design as soon as possible is <b>always</b> good, as if you were to start level design closer to the deadline like I did for <a href="https://horsehead.itch.io/in-too-deep" target="_blank" style = "padding: 2px"> ‘In Too Deep’</a>, <a href="https://horsehead.itch.io/gamejam-2019" target="_blank" style = "padding: 2px"> ‘Welcome To Yelapa’</a> and <a href="https://horsehead.itch.io/airport-lost-found-division" target="_blank" style = "padding: 2px"> ‘Airport – Lost & Found Division’</a> the levels tend to be <b>lower quality</b>, and <b>less entertaining</b> to play, in comparison, the gamejams where levels were focused on sooner like <a href="https://horsehead.itch.io/team-swap-heroes" target="_blank" style = "padding: 2px"> ‘Team Swap Heroes’</a>, <a href="https://horsehead.itch.io/driven-round-the-loop" target="_blank" style = "padding: 2px"> ‘Driven Round The Loop’</a> and <a href="https://horsehead.itch.io/gmtk-gamejam-2019" target="_blank" style = "padding: 2px"> ‘Only One Recruit’</a> have much more <b>entertaining and fun to play levels</b>, which in turn <b>makes the player want to play for longer</b>, I noticed this pattern during the development which is why I tried to get the team to work on the level design as soon as possible. <br /> One of the mechanics I worked on for the levels was <b>checking to see if they key to open the door has been collected.</b> <br /> To make this work, I made a <b>levelProperties script</b>, which would be on <b>every level</b> and contain a <b>boolean which indicates whether the player has collected the key for the level or not</b>, and if they have, it runs the win function. <br /> At the time, I thought this was the best way of approaching this, as it worked, but having learnt many new practices since then, I now realise that <b>I should’ve used ScriptableObjects to contain level data, and keep things tidy</b>, as <a href="https://bluebubblebee.medium.com/the-beauty-of-scriptable-objects-in-unity3d-c92b3a3783d3" target="_blank" style = "padding: 2px"> “they are great for organizing assets” </a> BlueBubbleBee, (2020). As a next step, if I were to work on this game again, I would be doing a lot of tidying to make sure the game is as <b>optimized</b> as possible, <b>so adding levels to it would be easy for anyone to do!</b> <br /> To go a step further, I could <b>integrate level creation with a program like Tiled</b> to build out levels from JSON text files, so artists would be able to use the easy to learn Tiled program to paint out levels!</p>                                    
    </div>
</div> 
<h3 style="margin-top: 20px">Reflection on Poppin' Hoppin' Unlockin'</h3>
<p>Overall, making Poppin’ Hoppin’ Unlockin’ (PHU) was a great opportunity to <b>further improve my leadership skills</b>, it allowed me to <b>experiment</b> in a more <b>creative approach to leading.</b> <br /> For me, one of my most significant experiences arose from <b>learning about different ways to lead a team</b>, my reflection on my leadership lead me to doing more research into creative input in the games industry, which is now a subject I’m interested in studying further. <br /> I personally really liked PHU as it was <b>great fun to make, and play!</b> The theme this time <b>allowed for more creativity</b>, which was not the case with the previous game. To improve, I feel like <b>player mechanics need a bit more refining to make it easier to play.</b> <br /> My <b>Define Games module</b> helped me out with rules within our game, for the first theme of Define Games, Jerrett, (2020) discussed how games are structured and he defines what rules are within games “Rules <b>restrict how to achieve a goal(s). Rules are operational</b> (Distinct) <b>Constitutive</b> (Mathematical) and <b>Implicit</b> (Unwritten).” – An example of this is the <b>lava and spikes being an implicit rule.</b></p>
<h3 style="margin-top: 20px">Ranking & Player Feedback</h3>                
<p>Poppin’ Hoppin’ Unlockin’ ranked <b>#15</b> Overall, which is a low ranking which surprised me a bit, <b>I thought the game was quite fun but that may be my biased opinion</b>, the feedback suggests that the reason we had gotten such a low score was because of the <b>player dash mechanic being difficult to use</b>, ultimately resulting in <b>frustration from the player.</b> <br /> I asked for feedback on my leadership from the rest of the group, and I was really happy with what I got, it made me realise that my leadership skills aren’t so bad!</p>
<details> 
    <summary>Personal Feedback</summary> 
    <table>
        <tr>
        <th>Name</th>
        <th>Feedback</th>
        </tr>
        <tr>
        <td>Luke</td>
        <td>I mean its Amy. Every quality you would want from a leader is here - good sense of timing, how hard tasks are, reading her peers skill levels, a knowledge base wide enough to support all members of the team should they need it but despite this pushed others to try themselves in order to let them learn and do things there own way which i think takes a lot of self awareness and self control. A sense of humour too which allowed us all to feel at ease with her and be ourselves and enjoy our time together. I dont want to cry on about it forever but honestly just fanastic leadership! </td>
        </tr>
        <tr>
        <td>Ben</td>
        <td>Great team lead that was able to keep the team all working together on time while still teaching and helping out.</td>
        </tr>
        <tr>
        <td>Gabe</td>
        <td>Highly driven and a great programmer. Did a good job of leading the team given the short time frame, particularly cutting down scope.</td>
        </tr>
        <tr>
        <td>Bryce</td>
        <td>As far as I remember, Amy was an amazing lead and encouraged everyone to work and do their best. She also worked on a lot of the moment mechanics. </td>
        </tr>
        <tr>
        <td>Cameron</td>
        <td>Was a really great lead.</td>
        </tr>
    </table>                        
</details>     
<details> 
    <summary>Teams Opinion On The Game</summary> 
    <table>
        <tr>
        <th>Name</th>
        <th>Game Rating</th>
        <th>Opinion</th>
        </tr>
        <tr>
        <td>Luke</td>
        <td style="background-color: #74ff2630">8/10</td>
        <td>While it was a shame the bombs couldnt work because of that dam character controller I believe the stunning visuals and the dam near mystical sound effects and music made it a experience despite it. The team that made it all had their voices heard and opinions shown in the final product which shows how loving and passioniate the team was. Loved every call with the team and i think the project reflects those times very well.</td>
        </tr>
        <tr>
        <td>Ben</td>
        <td style="background-color: #74ff2630">9/10</td>
        <td>So far the best Tdemo group I have worked with. The team worked together well and thanks to the amount of planning we were able to make a really good game super fast.</td>
        </tr>
        <tr>
        <td>Gabe</td>
        <td style="background-color: #74ff2630">10/10</td>
        <td>I mean we made it so I'm fully biased but honestly yeah the only thing that could be better would be to have had the mechanics a little more polished.</td>
        </tr>
        <tr>
        <td>Bryce</td>
        <td style="background-color: #74ff2630">7/10</td>
        <td>This was an amazing team to work with and game to work on. I enjoyed every moment even thought I didnt produce as much good quality work as I would have liked. </td>
        </tr>
        <tr>
        <td>Cameron</td>
        <td style="background-color: #74ff2630">8/10</td>
        <td>An amazing group of people who worked really hard and it was really well organised. </td>
        </tr>
    </table>                       
</details>    
<iframe frameborder="0" src="https://itch.io/embed/817536?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://amy-elliott.itch.io/poppin-hoppin-unlockin">Poppin' Hoppin' Unlockin' by Amy Elliott, Gabe, UP2014114, Mohamed.Elfayoumy, Ben Webb, Bryce Reading, Rob Cole, UP2023255</a></iframe>
               
<hr>
<h2 style="text-align:left; margin-top: 20px; margin-bottom: 20px">Aqua Adventure</h2>
<img src="/assets/img/posts/YearTDEMO/aqua.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 35%">
<p>Aqua Adventure is an <b>on-rails shooter game</b>, designed to fit around the <b>‘StarFox’ theme.</b> This theme is based off of, well, you guessed it; Nintendo’s beloved StarFox series! Mainly the 1993 title. <a href="https://en.wikipedia.org/wiki/Star_Fox" target="_blank" style="padding: 2px"> “StarFox is a spaceship shooter and third person action-adventure video game”</a> (<i>‘Star Fox’</i>, 2021) – This Wikipedia article is where we got the idea of what genres to base our game off of. <br /> My teams’ goal for this game jam was to make an underwater on-rails shooter, <b>we had 2 weeks.</b> This group mostly consisted of artists and 3D modellers, so I happily proposed to take on the entirety of the programming myself as a personal challenge. </p>
<div class="video-container">
    <iframe src="https://drive.google.com/file/d/1Lsjp-sLquA0sjiQp2OGtJFtKbMXT4TwD/preview" width="100%" height="500" frameborder="0"></iframe>
</div>                    
<div class="panel-heading active" role="tab" id="headingSeven">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseProgSelf" aria-expanded="true" aria-controls="collapseProgSelf" style="font-size: 18px; padding: 0px !important">
        Taking On The Programming Myself                                  
    </a>
    </h2>                                
</div>
<div id="collapseProgSelf" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingSeven">
    <div class="panel-body">  
        <img src="/assets/img/posts/YearTDEMO/aa.gif" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">       
        <p>Being a solo-programmer on this game meant that <b>I had to handle a lot of work - And I was prepared for this!</b> Some things which I had to work on during this project involve source control, and implementing all my teams' models, and game mechanics inside of Unity (Our game engine). <br /> As I mentioned, I asked the team if I can take on the entirety of the programming myself as a <b>personal challenge</b>, and I'm very happy they let me do that, as it allowed me to challenge myself, and although I got stressed near the end of the game jam, <b>it helped me learn what I can accomplish and what my limits are when working by myself on programming.</b><br /> A blog post titled <a href="https://www.edutopia.org/blog/can-stress-help-students-renee-jain" target="_blank" style="padding: 2px"> 'Can Stress Help Students?' </a> I read by Jain, (2015) talks about the <b>benefits of stress</b>, we usually see stress as a negative thing, but <a href="https://www.edutopia.org/blog/can-stress-help-students-renee-jain" target="_blank" style="padding: 2px"> "Thinking about stress as 'good' or performance-enhancing can work to your advantage" </a> as studies showed <a href="https://www.edutopia.org/blog/can-stress-help-students-renee-jain" target="_blank" style="padding: 2px"> "[people] primed with the mindset that stress was good for them - felt more productive and energetic."</a><br /> I didn't do this research during the game jam, but I know <b>for the future that I should try and see stress as a positive</b>, to <b>help me with productivity</b>, I would do this by thinking about the end product as I'm working toward it.<br /></p>
    </div>
</div> 
<h3> Reflection on Aqua Adventure </h3>
<p>Overall, Aqua Adventure was a great opportunity to <b>challenge myself and test my limits.</b><br />For me, testing my limits was the most useful aspect of making this game, as <b>my reflection work allowed me to learn about how to handle stress in a better way</b>, which is something I'm hoping to apply in the future for whenever I feel myself getting overwhelmed.<br />I really liked how Aqua Adventure turned out as it's fun to play, and has wonderful assets which made the game look really nice! Because of the role I took on for this game jam, it was also down to me to make an environment level out of the assets given, which gave me some creative freedom! <br /> To improve the game, I think <b>more mechanics</b> need to be put in, like <b>enemy AI</b> so they can attack the player, which means a health system would need to be put in, along with this I think we needed something in the game to use the <b>somersault and barrelroll</b> mechanic with, as that was implemented but never used!<br />My <b>Image Creation module</b> helped me out the most with this game, as I had to work on <b>environmental colours</b>, which was a topic that was covered within those lectures.<br /></p>                    
<h3> Ranking, Group & Player Feedback </h3>              
<p>Aqua Adventure ranked <b>#4</b> Overall, which isn&rsquo;t too bad!<br /> A summary of the feedback which we had gotten on the game was mostly about <b>how the barrel rolling and somersaulting mechanics didn&rsquo;t do anything for the game</b>, along with this, players also mentioned the <b>lack of communication between the game and player</b>, so the player didn&rsquo;t know how to win, this is due to <b>time constraints</b>, so given the opportunity to work on this game again, those are amongst the <b>first things which would be worked on.</b><br /><br />I asked for feedback from the rest of the group on how I performed during the game jam, and Tessa&rsquo;s feedback really <b>helped me realize that I need to step down a little bit.</b> <br />As I was only a programmer for this game, <i>I shouldn&rsquo;t be doing any leading</i>, upon talking to Tessa, she helpfully explained her feedback in more detail, Tessa told me that: &ldquo;Your eagerness in some parts of the project felt like you were trying to be a team lead yourself.&rdquo; I didn&rsquo;t mean to do this, so her being honest with me about this made me realize that in the future I should step back a bit and <b>re-evaluate how I'm altering the team dynamic.</b> Another point Tessa raised was that &ldquo;[my] timetabling felt a little controlling.&rdquo; &ndash; In a way, I think that was because <b>I always schedule out my entire day</b>, every day as it&rsquo;s a good habit of mine, and it <b>personally helps me get work done</b>, but <b>I need to learn that everyone works differently!</b> To improve so I don&rsquo;t come off as controlling, I should instead <b>trust a little more and work my schedule around everyone else&rsquo;s.</b><br /> </p>
<details> 
    <summary>Personal Feedback</summary> 
    <table>
        <tr>
        <th>Name</th>
        <th>Feedback</th>
        </tr>
        <tr>
        <td>Denisa</td>
        <td>She did all of the programming, per her own wish, and she did an amazing job at it. The game runs smoothly and she did catch any major bugs before it got to our QA phase.</td>
        </tr>
        <tr>
        <td>Hayley</td>
        <td>Amy, I love the job you did on the programming and I love how it turned out, the effort you put in was alot and you definitely demonstrated effective communication. It was a pleasure to work with you.</td>
        </tr>
        <tr>
        <td>Hannah</td>
        <td>Amy put her blood sweat and tears into the project managing to pull the team through the coding aspect of the group as well as implementing our teams assets and compiling the game. She was keen to get the work done and helped the rest of her teammates where possible.</td>
        </tr>
        <tr>
        <td>Abby</td>
        <td>Worked super hard to get all of our assets into the game, especially happy with her work as she was the only programmer and she managed to implement so much.</td>
        </tr>
        <tr>
        <td>Scarlett</td>
        <td>amy did really good work as she did all the programming and put the whole thing together! amy worked very hard to make our game what it was and I/ our group appreciated it a lot.</td>
        </tr>
        <tr>
        <td>Tess</td>
        <td>Although Amy at times seemed quite controlling, I cannot fault the amount of work she has done – building the game by herself is no easy feat! I appreciate the extra time she put in to make sure everyone’s assets were included as well. I am also thankful for the Trello board organising she did after we set her the task (as she seemed very excited by it). Nice work, Amy!.</td>
        </tr>
    </table>                        
</details> 
<details> 
    <summary>Teams Opinion On The Game</summary> 
    <table>
        <tr>
        <th>Name</th>
        <th>Game Rating</th>
        <th>Opinion</th>
        </tr>
        <tr>
        <td>Denisa</td>
        <td style="background-color: #74ff2630">7/10</td>
        <td>I enjoyed working with this team. Co-leading with Tessa was a great experience in project management, especially time management and task delegation. Everyone did their part, which allowed me to focus on my own tasks. Great team to work with, would happily do so again.</td>
        </tr>
        <tr>
        <td>Hayley</td>
        <td style="background-color: #ff9a264d">6/10</td>
        <td>Working with everyone was a challenge, the modelling helped cement my basic 3D modelling skills and the video (whilst i'm still a little embarrased about it) came out fairly well and I'm low key proud of it.</td>
        </tr>
        <tr>
        <td>Tess</td>
        <td style="background-color: #74ff2630">8/10</td>
        <td>Learning how to make music and sounds without the software I learnt from College was difficult but fun. I enjoyed working with the team, leadership and management was good experience (especially with Denisa's helping hand), and I would happily work with the team again.</td>
        </tr>
        <tr>
        <td>Scarlett</td>
        <td style="background-color: #74ff2630">8/10</td>
        <td>This team was really nice to work with. This helped me improve my 3dsmax skills. I'm proud of the game we made, everyone contributed something really cool so it was nice to see it all together and it was nice to read our good feedback on it.</td>
        </tr>                          
        <tr>
        <td>Abby</td>
        <td style="background-color: #74ff2630">7/10</td>
        <td>using 3DS max was a challenge, I wasn't comfortable using 3DS max at the time but after i got the hang of it, it was fairly simple and fun, I enjoyed working with the team and I am very proud of our game we made, I would to do something like this again.</td>
        </tr>                          
    </table>                       
</details>                       
<iframe frameborder="0" src="https://itch.io/embed/838435?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://amy-elliott.itch.io/aqua-adventure">Aqua Adventure by Amy Elliott, scarlettyeats0, up2015448TessaSmith, Hannahwaard, UP2022388 Hayley L, Denisa Maximova-2032161, Abbymcgreavey1</a></iframe>                

<hr>
<h2 style="text-align:left; margin-top: 20px; margin-bottom: 20px">Submarine Simulator</h2>
<img src="/assets/img/posts/YearTDEMO/sub.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 35%">
<p>Submarine Simulator is a <b>Planesman trainer</b>, designed and made for <b>The Royal Navy’s Recruitment Events.</b> Our target audience for this game are young teenagers ranging from 12-16, as they would be the ones attending these events. <br /> My teams’ goal for this game jam project was to make a fun and engaging, but short gameplay loop of around 90-120 seconds where the player gets to control both the planesman and the periscope view, and it also had to impress our clients! <br /> I gathered the group from other students who I’ve enjoyed working with in the past game jams or have seen good work from. Our group had around <b>5 months to make this simulator</b>, at the beginning, there was less stress as we were a 7-person group (including myself) so each of us worked on our own specialism, but nearer the end, it got a bit more stressful, as we all took on multiple specialisms to get the simulator finished on time. </p>
<div class="video-container">
    <iframe src="https://drive.google.com/file/d/1WWCWUeE9DKs-CWJIH61bWjN6uZjfC-c3/preview" width="100%" height="500" frameborder="0"></iframe>
</div>                  
<div class="panel-heading active" role="tab" id="headingEight">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGroupResearch" aria-expanded="true" aria-controls="collapseGroupResearch" style="font-size: 18px; padding: 0px !important">
        Group Research                                
    </a>
    </h2>                                
</div>
<div id="collapseGroupResearch" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingEight">
    <div class="panel-body">  
        <img src="/assets/img/posts/YearTDEMO/ss1.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">       
        <p>As a group, and as divided specialisms, we all began doing research into things we may need to know, and we shared these things. <br /> We also had our own group Zotero. Zotero is a <a href="https://en.wikipedia.org/wiki/Zotero" target="_blank" style="padding: 2px"> "reference management software to manage bibliographic data and related research materials" </a> (‘Zotero’, 2021) We used the Zotero to put useful videos and guides to help everyone out on.<br />
        We also put together <b>group discussions calls</b>, where we <b>proposed new ideas to grow our understanding</b> of what we will end up making by the end of this.<br />
        As of January, when we were doing these calls and collecting research, we had researched into all areas of things.<br />
        For our general research, we done a lot of research into <a href="https://science.howstuffworks.com/transport/engines-equipment/submarine.htm" target="_blank" style="padding: 2px"> How Submarines Work </a> (How Submarines Work, 2000), into <a href="https://youtu.be/BTis6GioP2g" target="_blank" style="padding: 2px"> How Submarines Dive and Surface </a> (Science Channel, 2016), and into <a href="https://youtu.be/3CMvMaUtd0Q" target="_blank" style="padding: 2px"> what it’s like on a submarine. </a> (Navy Lookout, 2020; Royal Navy Personnel in the Control Room on HMS Vigilant, Submarine..., n.d.; Ship Control Station, n.d.) <br />
        For our art research, the modellers looked into <a href="https://www.substance3d.com/products/substance-designer/" target="_blank" style="padding: 2px"> substance designer </a>, the documentation tells us that <a href="https://docs.substance3d.com/sddoc/substance-designer-overview-129368161.html" target="_blank" style="padding: 2px"> "Substance Designer is an application intended for creating 2D textures, materials and effects in a node-based interface, with a heavy focus on procedural generation, parametrisation and non-destructive workflows"</a>, the modellers used a <a href="https://youtu.be/BrIEYW59ld4" target="_blank" style="padding: 2px"> guide to learning substance </a> (The DiNusty Empire, 2016) and <a href="https://youtu.be/BbZ7ip-eCcI" target="_blank" style="padding: 2px"> research into how to unwrap </a> (ChamferZone, 2017).<br />
        For the programming research, we had a look into a few things regarding <a href="https://locomotionvault.github.io/?fbclid=IwAR1WLkyIrrfxQmfGaKOJj7xT4YT2kNRs3PfFxU6WTKR5FWJwVm1HjrEXKhc" target="_blank" style="padding: 2px"> VR </a> and <a href="https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization" target="_blank" style="padding: 2px"> Networking </a>, (Latency Compensating Methods in Client/Server In-Game Protocol Design and Optimization - Valve Developer Community, n.d.; Locomotion Vault, n.d.) I didn’t personally do this research as this was something Aurora and George were looking into. <br />
        The research I helped out with was a lot of the <b>general stuff</b> in the early stages, as I wasn’t thinking much about the programming side of things yet, as we haven’t delved into even a prototype at this point yet.</p>                                                                               
    </div>
</div>
<div class="panel-heading active" role="tab" id="headingNine">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseIndividualResearch" aria-expanded="true" aria-controls="collapseIndividualResearch" style="font-size: 18px; padding: 0px !important">
        Individual Research                                
    </a>
    </h2>                                
</div>
<div id="collapseIndividualResearch" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingNine">
    <div class="panel-body">  
        <img src="/assets/img/posts/YearTDEMO/ss2.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">       
        <p>At this point I was only told to <i>study Unreal Engine and C++ over the Christmas break</i>, to get comfortable with using Unreal with a combination of Blueprints and C++. Previously, I had done my own research and study into Unreal and C++, but I hadn’t ever applied it to a final game before.<br />
        I began my study of Unreal by going through the <a href="https://docs.unrealengine.com/en-US/index.html" target="_blank" style="padding: 2px"> Unreal Engine Documentation </a> and taking notes on important things, which I can use as a reference when I’m stuck. In addition to using it as a reference, <b>writing out notes this way helps me remember and study them much better.</b><br />
        I studied lots of basics, like the <b>most important workflows</b> when working in Unreal, <b>Player Movement, Input Checking</b> and <b>Interacting</b> with things, and <b>User Interface</b>. I personally found the <a href="https://docs.unrealengine.com/en-US/Basics/UnrealEngineForUnityDevs/index.html" target="_blank" style="padding: 2px"> Unity to Unreal documentation </a> (Unreal Engine 4 For Unity Developers, n.d.) very helpful to pick up things a lot quicker, as it used terms that I’m familiar with.<br />
        Another source that I used to study was the book Understanding the Basics of Blueprints (Ferro, n.d.). I didn’t study the whole book, but I read the entirety of chapter 2. I have also done some research into the Planesman using a <a href="https://americanhistory.si.edu/subs/operating/attackcenter/controlstation/index.html" target="_blank" style="padding: 2px"> web page </a> (Ship Control Station, n.d.) which talked about submarine movement in much more detail, I also looked into some terms, like Yaw and Rudder, and found a <a href="https://www.researchgate.net/figure/The-six-degree-of-freedom-model-of-submarine_fig1_274622739" target="_blank" style="padding: 2px"> picture that showcases the six-degree-of-freedom model of a submarine </a> (Figure 1. The Six Degree-of-Freedom Model of Submarine, n.d.), this helped me understand these terms.</p>                                        
    </div>
</div>
<div class="panel-heading active" role="tab" id="headingTen">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseIndividualPrototypes" aria-expanded="true" aria-controls="collapseIndividualPrototypes" style="font-size: 18px; padding: 0px !important">
        Individual Prototypes                                
    </a>
    </h2>                                
</div>
<div id="collapseIndividualPrototypes" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTen">
    <div class="panel-body">  
        <img src="/assets/img/posts/YearTDEMO/ss.gif" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">       
        <p>In the first few months of development, nothing much was done to make the game at all, so I decided if nothing was going to be done, I would have to individually get started with <i>some sort of prototype.</i><br />
        <b>We were still using Unreal Engine at this point, and I was not confident with using that at the time</b>, so I decided for the <b>purposes of prototyping and idea generation I would use Unity</b>, and another thing I would avoid is the whole ‘VR’ stuff as I haven’t got my own VR which is compatible, I would <b>aim to make this prototype work with mouse controls</b>, and maybe some keyboard presses. <b>This means our whole team could use and play it.</b></p>
        <p>I didn’t spend too long on this prototype, there <b>isn’t any functionality in it besides camera movement</b>, but <i>even doing something like this</i> sparked ideas!<br />
        I used Liam’s basic block out to get an idea of the scale of the place and how I could work with it, at this point, the team was still confused on the brief, we hadn’t been in a submarine, we had no idea what it looked like and we only had a basic idea of what a planesman and periscope operator actually do.<br />
        With this barebones blockout-with-camera-controls-prototype I whacked together quickly, I had these ideas for our future development:</p>
        <ul>
            <li><b>The game doesn’t necessarily need to be built from the ground-up with VR implemented</b>, most of our group, except one person had a VR headset to test on, so it would be <b>easier for testing purposes to have mouse controls</b> so everyone could work on the game if they wanted to.</li>                                             
            <li>We could <b>plan and develop the game in singleplayer</b> first, and then switch over to the multiplayer once we got all the basics down for the game.</li>
            <li>We could <b>switch between the planesman and periscope operator</b> with a UI button.</li>
            <li>It made me realise that <b>we were focusing on stuff we shouldn’t be focusing on first</b>, as we were <b><i>worrying too much</i> about the multiplayer and VR functionality rather than the actual game</b>, even though they’re important, the actual game needs to work first, and the mechanics can be thrown together in a <b>gamejam</b></li>
        </ul>
        <p>After I completed the prototype and we were in a group voice call, I proposed my ideas, and how <b>we should switch over to Unity because the majority of us knew how to use Unity and we only had limited time, which wouldn't be long enough for all of us to learn Unreal.</b><br />
        <b>I proposed the singleplayer idea</b> and <b>how we should focus on the game instead of the multiplayer and the VR for now</b>, and then from this call, we discussed running a gamejam over the weekend to get as much of the <b>basic game done and implemented</b>, as our team was being a bit slow in general and this was because we all didn’t know exactly what to do.</p>                                       
    </div>
</div>
<div class="panel-heading active" role="tab" id="headingEleven">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGroupPrototypes" aria-expanded="true" aria-controls="collapseGroupPrototypes" style="font-size: 18px; padding: 0px !important">
        Group Prototypes                                
    </a>
    </h2>                                
</div>
<div id="collapseGroupPrototypes" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingEleven">
    <div class="panel-body">  
        <img src="/assets/img/posts/YearTDEMO/gjss1.gif" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">       
            <p>This is one of the <b>smarter moves for the group</b>, as we all knew we weren’t getting anywhere as of now, we knew we needed to do something, and that is why we arranged the gamejam.<br />
            <b>I hoped that everyone in the group would attend</b>, but unfortunately, they didn’t so there was a lot of work to do, which meant that we done what we planned but not to the <b>quality</b> that we wanted.<br />
            We made a trello board just for the gamejam which we worked our way though, and at this point, our 3D modellers Rob and Liam had already finished their submarine models.</p>
        <h4>First Day of Gamejam (12/02: 6pm start)</h4>
        <img src="/assets/img/posts/YearTDEMO/gjss2.jpg" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">
            <p>Our plan looked into <b>the gameplay loop, the time frame, and the different controls, and any challenges we can add in to add difficulty to the game.</b><br />
            We planned the Periscope and Planesman mode out separately, but starting with the Periscope mode, we split it into 2, an ‘IN the periscope’ mode and a ‘Human Mode’ and from here we began going into detail about what each of those jobs done, and as we were describing this we decided to reference our brief which we had previously put together. Having it in a graph like this makes it seem like much less work is needed to be done.<br />
            With the Human Mode, we just had to take notes on <b>how they would input their findings.</b><br />
            For the Planesman notes, we wrote about <b>what they would do</b>, and that wasn’t very much. <br />
            The rest of the Miro board had the <b>gameplay description</b>, which was a written summary on how we imagine it would flow, which had some ideas around it.<br />
            When we moved onto Unity, Aurora was adding the planesman room and the periscope room with their textures, and I was working on adding <b>packages and working on the camera splines</b> for the Periscope room.<br />
            For the periscope room, I decided to use splines for the cinematic transitions between using the periscope and going over to the input panel, at this point they were just simple cameras moving along splines, there was no transitions between the two.</p>                                        
        <h4>Second Day of Gamejam (12/02)</h4>
        <img src="/assets/img/posts/YearTDEMO/gjss6.gif" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">
            <p>On this day I worked on a <b>whole bunch of things</b>, our planning on the Miro board was done, but we kept using the Trello.<br />
            I began working on the <b>script to switch between the periscope and using the control panel for the periscope room.</b><br />
            After that I worked on the <b>package management</b>, importing <a href="https://assetstore.unity.com/packages/tools/particles-effects/aura-2-volumetric-lighting-fog-137148" target="_blank" style="padding: 2px">Aura 2</a> and <a href="http://dotween.demigiant.com/getstarted.php" target="_blank" style="padding: 2px">DOTween.</a><br />
            I imported Aura 2 for Rob to play around with the lighting, and to make the scenes look nicer.<br />
            From here I worked on the <b>Planesman camera controls</b>, and much like my individual prototype, I used <a href="https://unity.com/unity/features/editor/art-and-design/cinemachine" target="_blank" style="padding: 2px">Cinemachine</a> to make a <b>‘first person’ feeling camera</b> which you can move around with your mouse, it also has restrictions so you can’t go past certain angles looking up and down, and the camera slowly recentres to the control panel if you have it in one place for too long.<br />
            From here I worked more on the periscope room and the planesman room, getting them to <b>crossfade</b> between each other, as snapping to the next camera feels unnatural.<br />
            I made the crossfade with an image UI component, and I simply got it to fade in or out depending on the bool parameter which I enabled and disabled within the code when you press on the interactive buttons in the rooms. I also made the Fade UI a prefab so it can be used in any scene.<br />
            From here I then worked on <b>outputting stuff to the screen</b> as the planesman operator, this wasn’t too hard to do, and it also looked really cool! This was the basics of it though, so the clearing functions and minus functions on the keypad were not working at this point.<br />
            Another thing I worked on during this day was the friend which will be sitting next to you when you’re in the planesman room.<br />
            Usually there would be 2 planesman in a submarine sitting side by side, and for this, we voted on a character in a poll which we have taken from Mixamo, for now this character is a placeholder, and I picked to use Mixamo as it’s all free and has many many realistic animations which you can apply to models which either you have made or they’re pre made on the website.<br />
            We ended up picking the gas mask character, as it means we wouldn’t have to worry about lip syncing when they give the instructions on how to play the game.<br />
            He was also inserted into the game, and it made the planesman area feel so much more alive!</p>
        <h4>Last Day of Gamejam (13/02)</h4>
        <img src="/assets/img/posts/YearTDEMO/gjss10.gif" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 50%; margin-top: 20px; margin-bottom: 20px">
            <p>On the last day of the gamejam it was <strong>hard</strong> to get the rest of the programming stuff done, but that was just down to me arranging the gamejam date to be on a day where <strong>most people in our team were busy</strong>! I didn’t think I could get the rest of the programming stuff done on time.</p>
            <p>On things non-programming related, I worked on <strong>reinserting the lighting for the periscope room</strong>, as something happened in Rob’s lighting on the room which made things error, putting the lighting in was fun as I was able to work with fog and different colours, and it really <strong>gave more personality to the room</strong>. I also worked on <strong>optimizing the camera controls</strong> for the periscope room as I was working on the lighting another thing I worked on was <strong>putting some more props into all of the scenes to make them look more alive!</strong> These props came from Liam and Rob, and I really like how they clutter up the place more.</p>
            <p>I then began working on <strong>making the input screen more detailed</strong>, to display what we need it to and getting the minus button and clear button working, now you can switch between putting the yaw and pitch inputs in, but I doubt this format would be used for the final game as we need to plan a bit more about how this would all work in general.</p>
            <p>After this I began working on the actual periscope, as of now there is no ‘sea’ in the game, but <strong>I’ve made targets which are any object tagged with target</strong>, and the periscope operator turns their camera according to some buttons, but this is all prototyping! this WILL be changed in the future!</p>
            <p>This was also added in as a button within the periscope room, so you can go in and out from using the periscope and being in the periscope room!</p>
            <p>Gabe also found some cool sound FX which we used on the buttons in the game to make using the control panel more fun to use!</p>
            <p>And that was pretty much what I had done for the gamejam, it was a lot of hard work, and it paid off! <br />And because this one went so well, we decided to do another one at some point which we are going to try and get the whole team to attend!</p>                                              
    </div>
</div>
<h3> Reflection on Submarine Simulator </h3>
<p>Overall, Submarine Simulator was a great experience as we had a chance to <strong>work with a client on a given brief</strong>.<br />For me, the most important experience making the game is working with a group of people who I now consider great friends and would love to work with in the future, working with this group has greatly helped me with my <strong>social and team working skills</strong>.<br />This project also taught me about the <strong>importance of communicating with our client</strong>, an example demonstrating this was the <strong>trouble we had with implementing the VR and Networking</strong> which was wanted on the brief, and we couldn't implement them due to covid and time restrictions, so, as a team, we proposed an <strong>alternative, feasible approach of the game</strong> to our client which didn't require those features, and they were happy with the idea, which in turn allowed us to produce a higher quality experience to the player.</p>
<p>I really like how Submarine Simulator has turned out as it’s fun to play, and it looks really nice due to the great models made by our modelers. And due to the size of the team, we <strong>all</strong> got a sprinkle of creative freedom no matter what role we took on!</p>
<p>To improve the Submarine Simulator, we would add compatibility with <strong>Virtual Reality</strong>, to allow the user to experience the game from the actual first-person experience they were meant to, along with this, we would add a <strong>multiplayer challenge</strong>, so the game fits the originally given brief.</p>
<p>My EPortfolio module helped me out the most with developing this game, as during our meetings with our client, we needed to <strong>present ourselves the best way possible</strong>, as we wanted them to see us as <strong>professionals</strong> and not students, and one of our Eportfolio lessons was on exactly this! It was very useful to know the best way to do this.</p>
<details> 
    <summary>Personal Feedback</summary> 
    <table>
        <tr>
        <th>Name</th>
        <th>Feedback</th>
        </tr>
        <tr>
        <td>Liam</td>
        <td>Working with Amy she showed fantastic knowledge of programming, C# and the Unity engine. She worked hard and was more than happy to help anyone who needed it. She was incredibly professional throughout and a great source of motivation. I look forward to working with her again.</td>
        </tr>
        <tr>
        <td>Ethan</td>
        <td>I worked along side Amy on our Submarine simulator. She worked on various aspects of the core gameplay elements and fixed many of the large bugs within the game. She has worked tirelessly on every aspect of the game, pushing herself to her limits, whilst helping all of us out with our own tasks. I see her willingness and motivation as an inspiration for our team.</td>
        </tr>                          
    </table>                        
</details> 
<details> 
    <summary>Teams Opinion On The Game</summary> 
    <table>
        <tr>
        <th>Name</th>
        <th>Game Rating</th>
        <th>Opinion</th>
        </tr>
        <tr>
        <td>Liam</td>
        <td style="background-color: #74ff2630">7/10</td>
        <td>Due to covid restrictions and other things the game did not reach the original brief, however what we did manage to achieve was a smooth and interesting experience that looked nice  and was fun to play.</td>
        </tr>   
        <tr>
        <td>Ethan</td>
        <td style="background-color: #74ff2630">7/10</td>
        <td>Although the game didn't reach the standards within our original brief, our game turned out pretty well. The visual aspect of the game are very well done and provides a tense atmosphere. Although it worked and played decently from a mechanical stand point, it was over complicated. Many features not being explained well for the player to understand them fully, leading to a more confusing player experience.</td>
        </tr>                                                   
        <tr>
        <td>Gabe</td>
        <td style="background-color: #74ff2630">8/10</td>
        <td>Sound could be better and there's a couple small things with the ships like some of the wakes being not quite right and the ship movement being a little unrealistic.</td>
        </tr>                                                   
    </table>                       
</details> 

<hr>

<h2 style="word-wrap: normal"> Final Evaluation & Reflection </h2>
<br />
<h4>Comparisons</h4>
<p>For the game jams we participated in, we got <strong>ranked</strong> using a ranking system on Itch.io, and these rankings were broken down into three criteria: <strong>Most Innovative</strong>, <strong>Best Gameplay,</strong> and <strong>Overall</strong>, I decided to put these rankings onto a line chart, as you can see here:</p>

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script type="text/javascript">
  google.charts.load('current', {'packages':['corechart']});
  google.charts.setOnLoadCallback(DrawChart);
  function DrawChart() 
  {
    var data = google.visualization.arrayToDataTable([
        ['Criteria', 'Blocky Road', 'Pet Pal', 'Poppin Hoppin Unlockin', 'Aqua Adventure'],
        ['Most Innovative',  1, 17, 12, 5],
        ['Best Gameplay',  2, 12, 15, 7],
        ['Overall',  1, 15, 15, 4],        
    ]);
    var options = {       
        chartArea: 
        {
            'backgroundColor': {
                'fill': '#F4F4F4',
                'opacity': 80
            },
        },         
        backgroundColor: {
            fill: '#1c1c1e',
            fillOpacity: 0
        }, 
        hAxis: {
            textStyle: {
                color: "#bcbcbc"
            },
            gridlines: {
                color: "#bcbcbc"
            },
            baselineColor: '#bcbcbc'
        },
        vAxis: {
            textStyle: {
                color: "#bcbcbc"
            },
            gridlines: {
                color: "#bcbcbc"
            },
            baselineColor: '#bcbcbc',
            direction: -1
        }, 
        legendTextStyle: {
            color: "#bcbcbc"
        },   
        titleTextStyle: {
            color: "#bcbcbc"
        },                                                   
        title: 'Ranking in each criteria (Data from itch.io)',
        legend: { position: 'right' },                 
    };
    var chart = new google.visualization.LineChart(document.getElementById('curve_chart'));
    chart.draw(data, options);
  }
</script>
<!-- <body padding="0.5in 0.5in 0.5in 0.5in" size="Letter"> -->
<div id="curve_chart" style="width: 100%; height: 500px;">&nbsp;</div>

<p><em>You can hover over the line chart to see the data at each point.</em><br />From this line chart <strong>you can see how each game did in comparison to each other</strong>, with <strong>Blocky Road being the highest-rated game</strong>, Aqua Adventure following, and then Pet Pal and Poppin’ Hoppin’ Unlockin’ (PHU) falling into the same overall ranking.</p>
<p>What’s interesting here is Pet Pal and PHU’s ranking, it’s interesting because we can see clearly from this chart, that Pet Pal’s highlight was its gameplay, but it didn’t do so well in innovation, whereas PHU’s highlight was its innovation, both games <strong>cross</strong> on the grid, and then get the <strong>same overall ranking</strong> at the end.<br />I agree with the rankings though, PHU has <strong>interesting concepts leading to it being innovative</strong>, with the cute player movement, and story behind the game, but <strong>its downfall is the gameplay</strong>, with the dash not working well, in comparison, with Pet Pal, it got a higher ranking in the ‘Best Gameplay’ criteria because <strong>the gameplay works</strong>, there are no apparent bugs, and it does exactly what we needed it to do, but <strong>Pet Pal isn’t innovative at all</strong>, it’s a <strong>very basic non-ambitious clicker game</strong>, nothing new or unique about it, which justifies the low score in innovation.</p>
<p>I decided to ask each team that I worked on what their <strong>personal overall rating</strong> of the game they worked on would be, to see if I can draw any <strong>similarities and trends</strong> between the rankings and the personal ratings. If we compare these personal ratings with the overall ranking for each game, this is what the data looks like:</p>

<div class="row">
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
    google.charts.load('current', {'packages':['corechart']});
    google.charts.setOnLoadCallback(DrawChart);
    function DrawChart() 
    {
        var data = google.visualization.arrayToDataTable([
            ['Game', 'Team Average Rating', 'My Personal Rating'],
            ['Blocky Road',  9, 9],
            ['Pet Pal',  3.75, 2],
            ['Poppin Hoppin Unlockin',  8.4, 9],  
            ['Aqua Adventure',  7.2, 7],       
        ]);
        var options = {       
            chartArea: 
            {
                'backgroundColor': {
                    'fill': '#F4F4F4',
                    'opacity': 80
                },
            },         
            backgroundColor: {
                fill: '#1c1c1e',
                fillOpacity: 0
            }, 
            hAxis: {
                textStyle: {
                    color: "#bcbcbc"
                },
                gridlines: {
                    color: "#bcbcbc"
                },
                baselineColor: '#bcbcbc'
            },
            vAxis: {
                textStyle: {
                    color: "#bcbcbc"
                },
                gridlines: {
                    color: "#bcbcbc"
                },
                baselineColor: '#bcbcbc'
            }, 
            legendTextStyle: {
                color: "#bcbcbc"
            },   
            titleTextStyle: {
                color: "#bcbcbc"
            },                                                   
            title: 'Game Rating (Out of 10)',
            legend: { position: 'right' }                    
        };
        var chart = new google.visualization.LineChart(document.getElementById('curve_chart_rank_comparison'));
        chart.draw(data, options);
    }
    </script>
    <!-- <body padding="0.5in 0.5in 0.5in 0.5in" size="Letter"> -->
    <div id="curve_chart_rank_comparison" style="width: 50%; height: 500px;">&nbsp;</div>
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
    google.charts.load('current', {'packages':['corechart']});
    google.charts.setOnLoadCallback(DrawChart);
    function DrawChart() 
    {
        var data = google.visualization.arrayToDataTable([
            ['Game', 'Most Innovative', 'Best Gameplay', 'Overall Rank'],
            ['Blocky Road',  1, 2, 1],
            ['Pet Pal',  17, 12, 15],
            ['Poppin Hoppin Unlockin',  12, 15, 15],  
            ['Aqua Adventure',  5, 7, 4],       
        ]);
        var options = {       
            chartArea: 
            {
                'backgroundColor': {
                    'fill': '#F4F4F4',
                    'opacity': 80
                },
            },         
            backgroundColor: {
                fill: '#1c1c1e',
                fillOpacity: 0
            }, 
            hAxis: {
                textStyle: {
                    color: "#bcbcbc"
                },
                gridlines: {
                    color: "#bcbcbc"
                },
                baselineColor: '#bcbcbc'
            },
            vAxis: {
                textStyle: {
                    color: "#bcbcbc"
                },
                gridlines: {
                    color: "#bcbcbc"
                },
                baselineColor: '#bcbcbc',
                direction: -1
            }, 
            legendTextStyle: {
                color: "#bcbcbc"
            },   
            titleTextStyle: {
                color: "#bcbcbc"
            },                                                   
            title: 'Game Ranks',
            legend: { position: 'right' }                    
        };
        var chart = new google.visualization.LineChart(document.getElementById('curve_chart_rank_comparison2'));
        chart.draw(data, options);
    }
    </script>
    <!-- <body padding="0.5in 0.5in 0.5in 0.5in" size="Letter"> -->
    <div id="curve_chart_rank_comparison2" style="width: 50%; height: 500px;">&nbsp;</div>
</div>

<p>With these comparisons, you can see the<strong> same trends</strong> between the itch.io rankings and team/personal ratings, with <strong>one exception being Poppin’ Hoppin’ Unlockin’</strong>, from this it’s easy to see that <strong>we all enjoyed working together, but the game we made wasn’t so great</strong>, so, if we were to work on another game as the same team, things could work out better!</p>
<p>I also took game ratings for the rest of the games, and here is that chart:</p>

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script type="text/javascript">
  google.charts.load('current', {'packages':['corechart']});
  google.charts.setOnLoadCallback(DrawChart);
  function DrawChart() 
  {
    var data = google.visualization.arrayToDataTable([
        ['Game', 'Team Average Rating', 'My Personal Rating'],
        ['Blocky Road',  9, 9],
        ['Pet Pal',  3.75, 2],
        ['Poppin Hoppin Unlockin',  8.4, 9],  
        ['Aqua Adventure',  7.2, 7],  
        ['Submarine Simulator',  7.3, 8],      
    ]);
    var options = {       
        chartArea: 
        {
            'backgroundColor': {
                'fill': '#F4F4F4',
                'opacity': 80
            },
        },         
        backgroundColor: {
            fill: '#1c1c1e',
            fillOpacity: 0
        }, 
        hAxis: {
            textStyle: {
                color: "#bcbcbc"
            },
            gridlines: {
                color: "#bcbcbc"
            },
            baselineColor: '#bcbcbc'
        },
        vAxis: {
            textStyle: {
                color: "#bcbcbc"
            },
            gridlines: {
                color: "#bcbcbc"
            },
            baselineColor: '#bcbcbc'
        }, 
        legendTextStyle: {
            color: "#bcbcbc"
        },   
        titleTextStyle: {
            color: "#bcbcbc"
        },                                                   
        title: 'Game Rating (Out of 10)',
        legend: { position: 'right' }                    
    };
    var chart = new google.visualization.LineChart(document.getElementById('curve_chart_rank'));
    chart.draw(data, options);
  }
</script>
<!-- <body padding="0.5in 0.5in 0.5in 0.5in" size="Letter"> -->
<div id="curve_chart_rank" style="width: 100%; height: 500px;">&nbsp;</div>

<p>Looking at these charts, I can see that <strong>when I work solo, I produce my best work</strong>, which is really strange! I think this is due to the fact that I can go my <strong>own pace</strong> and only have myself to worry about, I can do what I personally feel I can do in the time I have, and cater the work and the style toward what I know, by this I mean that I know I can’t make a game with hundreds of 3D models, as that isn’t my specialism, instead I should focus on something which looks simpler and put all of my efforts into my specialism of Programming.</p>
<p>I can also see that the <strong>two games that I took a lead role</strong> in got <strong>lower rankings in innovation and gameplay</strong>, and I’ve noticed that maybe if I had done more programming on both of those teams and less project management, or even not been a lead and took a programming role, we may have been able to implement more gameplay mechanics as there would’ve been more programmers.<br />From the ratings of the games on the chart, the teams experience with developing Pet Pal was pretty low with <strong>3.75/10</strong>, but from the written reviews, that rating was given because of the lack of creativity with this game theme, but with PHU, the teams average experience was much much higher, with <strong>8.4/10</strong>, meaning that <strong>the group dynamics have definitely improved between being a lead for both of those games</strong>.</p>
<p>Aqua Adventure and Submarine Simulator are slightly <strong>above average in team ratings</strong>, between the two getting an average of <strong>7.15/10</strong>, for both of these games, for these games I’ve taken on a programmer role, so I was able to focus on programming, and implement mechanics which have been asked from group leaders, although between the two groups, <strong>I felt a much better group dynamic and leadership for Submarine Simulator</strong>, hence the higher personal rating.</p>
<br />
<h4>Interpratations</h4>
<p>For <strong>Blocky Road</strong>, the most important thing I’ve learnt is <strong>I can definitely write unoptimized code for a game jam</strong>, and although optimized code is really great practice, for game jams, we have a very short period of time to make a prototype of a game, and prototypes really don’t have to be optimized! They just need to show an idea.<br />Another thing that Blocky Road has taught me, is about <strong>how far a simplistic game can go</strong>, I’ve found that I really like making hyper-casual games, and it’s certainly something I’m going to be making more of for gamejams in the future.</p>
<p>For <strong>Pet Pal</strong>, the most important thing I’ve learnt is <strong>how a lack of creativity and a boring theme can really impact a team’s motivation for producing a game</strong>, this is apparent because, for the game, we only stuck with the most basic of clicking mechanics and didn’t expand any further.</p>
<p>For <strong>Poppin’ Hoppin’ Unlockin’</strong>, the most important thing I’ve learnt is <strong>how a great team can still produce a sub-par rated game!</strong> We’ve personally rated the experience of making the game really high, but there is much which can be changed about the game itself. I would love to work with this team again, I think they’re amazing!</p>
<p>For <strong>Aqua Adventure</strong>, I’ve learnt that <strong>I shouldn’t take on an entire role myself</strong>, and <strong>I shouldn't be afraid to ask for help</strong>, I was happy I experienced this so that I know for the future, there was a lot of stress of taking on all of the programming, so it would’ve been good to ask for an extra hand the next time that something like this happens.</p>
<p>For <strong>Submarine Simulator</strong>, I’ve learnt about <strong>how beneficial it is to scope down a brief if you feel it wouldn’t be done on time</strong>, this is important to avoid producing bad quality, rushed work!</p>

<br />
<h4>Outcome</h4>
<p>Overall, I’ve learnt so many skills which I can use for any future projects, I have also learnt a lot about <strong>how I perform in both leadership and programmer roles</strong>, these skills are crucial to understand.</p>
<p>There are so many areas which I feel I could improve in a team setting, with both programming and leadership, my most important area I feel I should improve and practice in is that <strong>people may not work in the way that I work!</strong> I feel this would really improve my leadership skills.</p>
<p>In the future, I hope I can see this improvement in my leadership skills and mindset, so I can help <strong>make a better group dynamic</strong>.</p>
<hr>

<details> 
    <summary>Bibliography</summary> 
        <p>BlueBubbleBee. (2020, January 29). <em>The beauty of Scriptable Objects in Unity3D</em>. Medium. https://bluebubblebee.medium.com/the-beauty-of-scriptable-objects-in-unity3d-c92b3a3783d3</p>
        <p>ChamferZone. (2017, February 23). <em>Unwrap Special—Full guide to efficient and fast UV Mapping—3Ds Max 2017</em>. https://www.youtube.com/watch?v=BbZ7ip-eCcI&amp;ab_channel=ChamferZone</p>
        <p><em>Cookie Clicker</em>. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Cookie_Clicker&amp;oldid=1016380860</p>
        <p>Di Luca, M., Seifi, H., Egan, S., &amp; Gonzalez-Franco, M. (2021). Locomotion Vault: The Extra Mile in Analyzing VR Locomotion Techniques. <em>Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems</em>, 1–10. https://doi.org/10.1145/3411764.3445319</p>
        <p>Ferro, L. (n.d.). Understanding the Basics of Blueprints. In <em>Unreal Engine Blueprints Visual Scripting Projects</em> (pp. 38–53). Packt.</p>
        <p><em>Figure 1. The six degree-of-freedom model of submarine</em>. (n.d.). ResearchGate. Retrieved 8 May 2021, from https://www.researchgate.net/figure/The-six-degree-of-freedom-model-of-submarine_fig1_274622739</p>
        <p><em>How Submarines Work</em>. (2000, August 17). HowStuffWorks. https://science.howstuffworks.com/transport/engines-equipment/submarine.htm</p>
        <p>Hyper-casual game. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Hyper-casual_game&amp;oldid=1010567757</p>
        <p>Jain. (2015, February 9). <em>Can Stress Help Students?</em> Edutopia. https://www.edutopia.org/blog/can-stress-help-students-renee-jain</p>
        <p>Jerrett, A. (2020, November). <em>Define Games—Theme 1</em>.</p>
        <p>Kantilaftis, H. (2014, November 25). How To Form A Solid Indie Game Development Team. <em>Student Resources</em>. https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/</p>
        <p><em>Latency Compensating Methods in Client/Server In-game Protocol Design and Optimization—Valve Developer Community</em>. (n.d.). Retrieved 8 May 2021, from https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization</p>
        <p>Navy Lookout. (2020, November 2). <em>Preview - On Board Britain’s Nuclear Submarine: Trident</em>. https://www.youtube.com/watch?v=3CMvMaUtd0Q&amp;ab_channel=NavyLookout</p>
        <p>Platform game. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Platform_game&amp;oldid=1020610399</p>
        <p>Quintans, D. (2013, January 22). <em>Game UI by Example: A Crash Course in the Good and the Bad</em>. Game Development Envato Tuts+. https://gamedevelopment.tutsplus.com/tutorials/game-ui-by-example-a-crash-course-in-the-good-and-the-bad--gamedev-3943</p>
        <p><em>Royal Navy personnel in the control room on HMS Vigilant, submarine...</em> (n.d.). Getty Images. Retrieved 8 May 2021, from https://www.gettyimages.co.uk/detail/news-photo/royal-navy-personnel-in-the-control-room-on-hms-vigilant-news-photo/506044550</p>
        <p>Science Channel. (2016, April 29). <em>How Do Submarines Dive and Surface?</em> https://www.youtube.com/watch?v=BTis6GioP2g&amp;ab_channel=ScienceChannel</p>
        <p><em>Ship Control Station</em>. (n.d.). Retrieved 8 May 2021, from https://americanhistory.si.edu/subs/operating/attackcenter/controlstation/index.html</p>
        <p>Sokolovski, M. (2020, May 9). <em>“Dev Diaries” Should Become The Norm For Game Studios</em>. TheGamer. https://www.thegamer.com/dev-diaries-direct-updates-habit-game-studios/</p>
        <p><em>Star Fox</em>. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Star_Fox&amp;oldid=1019587969</p>
        <p>Substance Designer. (n.d.). <em>Substance 3D</em>. Retrieved 8 May 2021, from https://www.substance3d.com/products/substance-designer/</p>
        <p><em>Substance Designer—Substance Designer Overview</em>. (n.d.). Retrieved 8 May 2021, from https://docs.substance3d.com/home</p>
        <p>The DiNusty Empire. (2016, September 27). <em>Learning Substance: Introduction and Basics of Substance Designer [EP10]</em>. https://www.youtube.com/watch?v=BrIEYW59ld4&amp;ab_channel=TheDiNustyEmpire</p>
        <p><em>Unreal Engine 4 For Unity Developers</em>. (n.d.). Retrieved 8 May 2021, from https://docs.unrealengine.com/en-US/Basics/UnrealEngineForUnityDevs/index.html</p>
        <p>Weesner, J. (2011, August 3). <em>Opinion: Classic Problems With Level Design</em>. /view/news/126332/Opinion_Classic_Problems_With_Level_Design.php</p>
        <p>Zotero. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Zotero&amp;oldid=1022053488</p>                        
</details> 
