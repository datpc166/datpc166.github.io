---
layout: post
title:  "Somewhere In Berkshire"
type: "Game Development Blog"
color: "background-color: seagreen"
summary: "Somewhere in Berkshire is an exploration game designed to fit around a few randomly selected tricky themes. <small>(Portsmouth University Game Jam 2020)</small>"
author: dylan
date: '2022-01-31'
category: ['game-development', 'game-jam', 'unity']
thumbnail: /assets/img/posts/SomewhereInBerkshire/cover.png
keywords: dragonsitter, gamejam, here
permalink: /blog/somewhere-in-berkshire/
usemathjax: true
published: false
---

<hr>
<!--- ------------------ -->
<!--- Status of the game -->
<!--- ------------------ -->
<div class="table-mobile">
    <table>
        <tr>
            <th style="border: 0px !important">Status:</th>
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">Done</small></th>
        </tr>
        <tr>
            <th style="border: 0px !important">Project Type:</th> 
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">Game Jam</small></th>
        </tr>
        <tr>
            <th style="border: 0px !important">Development Duration:</th>
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">72 Hours</small></th>
        </tr>
        <tr>
            <th style="border: 0px !important">Software Used:</th>
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">Unity</small><small class="btn btn-col status-button">Photoshop</small></th>
        </tr>
        <tr>
            <th style="border: 0px !important">Primary Roles:</th>
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">Programming</small><small class="btn btn-col status-button">UI</small><small class="btn btn-col status-button">Design</small><small class="btn btn-col status-button">Shaders</small><small class="btn btn-col status-button">Art</small></th>
        </tr>
    </table>
</div>

<hr>
<!--- ---------------------------- -->
<!--- Main description of the game -->
<!--- ---------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">About Somewhere In Berkshire</h2>
    <p style="text-align: center;">Somewhere in Berkshire is an exploration game designed to fit around a few randomly selected tricky themes. The three themes were picked randomly from Wikipedia. <br /> The themes which were picked for this were: The 1999 Saskatchewan Scott Tournament of Hearts, Bockhampton Berkshire, and finally a Professor called Jillian Banfield. In this gamejam, I worked with Team Horsehead, there was 5 of us on the team, including me. I mostly worked on Programming, Design, UI Shaders and Art for the game. <br />Through making this game I learnt a lot more about shaders in Unity.</p>
</div>

<!--- ------------------------------------ -->
<!--- Embed or Youtube Footage of the game -->
<!--- ------------------------------------ -->
<div style="text-align: center;"><iframe frameborder="0" src="https://itch.io/embed-upload/2385357?color=333333" allowfullscreen="" width="100%" height="688"><a href="https://horsehead.itch.io/somewhere-in-berkshire">Play Somewhere in Berkshire on itch.io</a></iframe></div>

<hr>
<!--- ------------------------------------ -->
<!--- Gallery and screenshots for the game -->
<!--- ------------------------------------ -->
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Gallery & Screenshots</h3>
<div class="panel-heading active" role="tab" id="headingOne">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGall" aria-expanded="true" aria-controls="collapseGall" style="font-size: 18px; padding: 0px !important">
        Gameplay GIFs
    </a>
    </h2>                                
</div>
<div id="collapseGall" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne">
    <div class="panel-body">
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire2.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire3.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire4.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
    </div>
</div>

<hr>
<!--- ------------------------------------------------------- -->
<!--- Development overviews for the game, to give an insight. -->
<!--- ------------------------------------------------------- -->
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Development Overview</h3>
<p>This game is an action-adventure game where you must travel around Bockhampton, a tiny abandoned village in Berkshire. <br /> Some mysterious person called Jillian is texting you, but how are you getting these messages when there is no signal in this village? <br /> </p>
<p> This GameJam is usually a GameJam which is held in person at the University of Portsmouth, and it runs for a whole week, but considering this jam was running during the Covid-19 pandemic we had to run this online. <br />The three themes were picked randomly from Wikipedia, the themes which were picked for this were: The 1999 Saskatchewan Scott Tournament of Hearts, Bockhampton Berkshire, and finally a Professor called Jillian Banfield.<br /> </p>

<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Flowing 2D Grass</h3>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/grass.gif">
<p>On the first day, we had got given the themes, so we were all planning out what we could do with them, a ideas document was made where stuff was planned.<br />
I knew we were going for an abandoned village, so I began right away with making a grass texture for the ground, along with this I attempted to make a shader which would make the grass flow in the wind, but it never ended up working with 3D.</p>
<img src="/assets/img/posts/SomewhereInBerkshire/notuniformgrass.png" style="object-fit: cover; height: 200px; width: 100%; object-position: 0 70%">
<p>I tried finding a solution, but I couldn’t at the time since I felt like I was spending too much time on something small like this, but Joe ended up finding a solution and it ended up that the solution was that the image itself was a sprite, and we just needed to change the sprite to default and put it on 3D geometry.<br />
I then worked on grass variation, I wrote a script on each grass which would randomise the grasses scale and rotation, and the result of this meant that the grass looked less uniform and much more natural!</p>

<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Phone User Interface</h3>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/ui1.png">
<p>For the UI in the game, we knew we needed a mobile phone, as in this game, the main character is going to receive text messages. So I began to work on that. <br />
I started by doing research on Phone UI on google, nothing too in depth. I drew the outline of a phone, just a generic outline, since I didn’t want to put any branding on it, and then filled in the screen, and saved all the phone sections separately. <br />
Once that was done I began putting in all the Phone UI, making sure it all scaled correctly and it was all in-tact.<br />
I managed to get all of this working as it does by using a vertical layout group on the phone, and instantiating the text boxes inside of it each time I pressed a button to trigger the text being sent, obviously this would be different in the final project. I also used DOTween to work on the smooth UI transitions, since I feel like smooth UI makes a game feel much more polished. <br />
On the second day of the game jam, I worked on was updating the Phone UI, since at this point, the messages that the player received showed up on the right hand side, and it should be on the left hand side if the player is getting the messages, I also added a name above each message, but it didn’t look right in the end so this was changed later on.<br />
All of the programming was done so the messages set in the message data is set onto the messages which get instantiated onto the phone.<br />
Later on during the second day of the jam, I worked on a quick mechanic for the phone, making to so when you get a text, the phone pops up for a few seconds and then slides back down again if a message doesn’t get received within the time value which I’ve set.<br />
I really like how the phone has ended up looking, since it really looks like a real phone.</p>


<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Collectible Particles & Other User Interfaces</h3>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/collectible.gif">
<p>During the first day, I worked on a particle, for a collectable, this means that we could just have the sparking collectable particles in the world instead of the actual 3D objects, so it’s a mystery what the player picks up, a lot of games do this. <br />
I made these particles by making a circle ring and a solid circle ring, along with some star parts, and then I manipulated their particle settings to stay in place, I’m quite proud with how it looks!</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/collectible2.gif">
<p>We decided that if we have collectables like this, we would need a collectable notification box, so that is what I began working on, it was pretty simple to make and I made use of DOTween to make the UI transition and fade in/out smoothly.</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/collectible3.gif">
<p>The next thing I had to work on once I finished that was the visuals for the collectables which are picked up, there currently isn’t loads of collectables to collect, but they can easily be added to the game, since the collectables are data objects.<br />
The only thing I needed to do was link up the titles, descriptions and the item images to the collectable UI, and then I had to draw images for the 2 collectables which we had in the game at the moment, soil and bugs, I also decided to add a little polish and make a nice shine behind the object, this was heavily inspired by BOTW’s UI when you pick up an object, I then added some tweening and this is the result of the collectable UI, overall I really love this!</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/collectible.png">
<p>To give the game more ‘life’ I decided to add a few more collectables to it instead of just having dirt and bugs, so I began to draw pictures for each collectable and add that data into the game (I didn’t draw the rock image, the rock image is a placeholder)</p>


<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Shader Graph Work</h3>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/watershader.gif">
<p>I began my shader work by making basic flowing water. I duplicated the grass shader and began building the water shader off of that, now I’m pretty new to shader graphs and I came by a problem where it just wasn’t working properly for a cube, since the water is a cube, and the faces were just clipping when the water was waving, so I looked through the shader graph to see what the problem was, and it turns out that I just needed to change a few world options to object since the shader was moving the square relative to word space instead of the object itself.</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/fireshader.gif">
<p>The next shaders I worked on were the fireball shader and a fireball actor, this wasn’t too hard, since to make the fireball shader, all I had to do was duplicate the water shader and adjusted it accordingly, with making the actor, I simply made the empty actor script and added into it what I wanted the fireball to do, which is move in a direction with every move I do, I also done the same to make a ghost shader, I just needed to make it a light blue colour, and I also made the empty ghost actor script so stuff can be added to it later on.</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/stripes.gif">
<p>Another shader I worked on was the 'next movement' tile shader, this is scrolling stripes to show more clearly that the tile which has stripes on is different from the rest since it’s the one that the enemy would land on.</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/berkshire.gif">
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/berkshire2.gif">
<p>I needed to work on an electricity shader effect which would be used when the player uses the lightning magic, I followed along with a video to help me create this effect, since I don’t fully understand shader graphs yet, but I learnt lots of stuff as I was following along with the video, I had also made the lightning icon which is on the lightning button, I just improved this from a placeholder one which we had there. And to give feedback to the player, I found some lightning sound FX which were used when the player was casting the lightning and when the player got shocked with the lightning</p>


<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Environmental Work & Other Work</h3>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/sky.png">
<p>For the game, I decided maybe a new skybox was needed so it doesn't look so generic, I have never worked with skyboxes before, so I decided this was the best time to work on them! I watched a tutorial to give me an idea of how to make skyboxes in Unity, and then I went ahead and made my own, I really like how I drew the clouds.</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/lightning.gif">
<p>After this I began working on the lightning particle FX, since in the story plan for our game, we were planning to have the player struck with electric to gain electric powers, this was pretty simple to make, I began by making a sprite sheet of all of the lightning stages, I then made the particle work by making a texture sheet animation and set the grid to 4 x 1</p>
<img class="image-heading" src="/assets/img/posts/SomewhereInBerkshire/atmosphere.png">
<p>The next environmental work which needed to be done was the atmosphere and fog for the game to make it feel like the player was really in an abandoned English town on a spring day, the artist of the group put together a colour palette to give us a better understanding of the atmosphere we should go for in the game, and so I followed it and created 2 different atmospheres, and in the end, the morning atmosphere was chosen.</p>
<p>To go along with the mood of the game I added ambient music, we knew that Brockhampton and Berkshire were english towns, and we knew Brockhampton was an abandoned village, so we decided since these atmosphere felt spring-like we were going to go for a morning spring feeling, so I found a spring atmosphere on Gamesound.xyz, and cut it down slightly so it seamlessly looped, and I inserted it into the game, along with this, I found a guitar loop which was on looperman.com which was free to use and sounded very calming and perfect for the atmosphere of the game. <br />Once I done that I decided to add more to the atmosphere, this included small grass particles to the players feet when they move, and a grass footstep sound FX for feedback to the player, I felt like all of this is very important to add into the game to set the mood.<br /></p>
<p>To make the beginning cutscene make sense, I decided to make a model for the sign which points toward Bockhampton, this didn’t take me long to model and texture at all and it appears in the beginning cutscene of the game, the spawn area which the player starts in and the icon.<br /></p>
<p>To give the game more of a story, I began to add in more conditions and text messages, since in the end, we didn’t really have much of a game, so the player only ended up getting text messages when they collected a collectable, I made some extra text boxes and conditions for the player to meet so the game felt like it had more content in it. <br />Another thing which I worked on was an end screen, which would show the player their statistics when they finish playing the game, that was pretty easy to get working, and it is a nice thing to add into the game so people can have a little competition with competing for who can finish the game the fastest, or who can attack the most enemies.</p>
<p>I also worked on random enemy movement as well, making it so the next direction which the enemy decides to move in is random, and it’s not just going in circles like it used to, this adds a challenge to the game (and makes it 1000x harder to attack enemies) and I was really proud with the result. I also worked on the intro cutscene for the game, I didn’t use the Unity Timeline, or the Animation tool, I made it so the cutscene was hard-coded into the beginning of the game, and I simply made it by lerping between camera transforms, it was a lot easier to make than I thought it would be<br /></p>
<p> By this point it was getting closer to the final deadline, so I decided to work on the itch page, and I worked on making a logo/icon for the game, I made these using Blender and Photoshop.<br /></p>

<hr>
<!--- ------- -->
<!--- Credits -->
<!--- ------- -->
<h3 style="text-align:center">Game Jam Participants</h3>
<p style="text-align:center">This game was made by 5 members of the <a class = "a-text" href="/blog/authors/teamhorsehead" target="_blank">Team Horsehead</a> team, including me. <br /> You can see more information about the team on the <a class = "a-text" href="https://horsehead.itch.io/somewhere-in-berkshire" target="_blank">Itch.io page</a>.</p> 

<hr>

