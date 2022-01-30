---
layout: post
title:  "I Learnt About The Different Pathfinding Algorithms & Made A Tool In C++. Here's My Process."
type: "Study Blog"
color: "background-color: darkslateblue"
summary: "Pathfinding algorithms have always been something which interests me, and so I decided to make myself a pathfinding tool!"
author: dylan
date: '2022-01-10'
category: ['study', 'research', 'development', 'improvement']
thumbnail: /assets/img/posts/TOGA/cover.png
keywords: personal, education, teaching, reflection, development, improvement
permalink: /blog/i-learnt-about-pathfinding/
usemathjax: true
---
<hr>
<div class="table-mobile">
    <table>
        <tr>
            <th style="border: 0px !important">Date Project Finished:</th>
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">20th</small><small class="btn btn-col status-button">May</small><small class="btn btn-col status-button">2021</small></th>
        </tr>
    </table>
</div>
<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/cover.png">
<p>I once had a programming test that involved pathfinding, and I hadn’t really studied any pathfinding algorithms at all before that. The test was timed, so I had a little time to briefly do research into it, and in the end, I <strong>wasn’t</strong> able to complete the test, I felt like I was <strong>almost there</strong> though! <br />I’m so thankful that I at least <em>attempted</em> the test as it was really interesting and made me want to further look into pathfinding algorithms!</p>
<p>So, I did that!</p>
<p>In this blog, I talk about my process of studying the different pathfinding algorithms and making my own pathfinding tool in C++.</p>

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/1.jpg" style="height: 200px !important; object-position: 50% 40% !important;">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Blog Content</h3>
<p style="text-align:center"><i class="fas fa-pencil-ruler fa-2x" style="vertical-align: middle;"></i> &emsp; Before approaching any big project, I plan for how I’m going to approach it.</p>
<p>As you know from looking at my portfolio, I <strong>LOVE</strong> to write blogs, so this plan helps me break the project down into sections that I can write about! This helps me with ensuring I write everything which I think is important, so you can read about everything from the start to the end of development!</p>
<p>Here are some links to these chapters in this Blog:</p>
<li><a href="#Proposal">Proposal</a>
<li><a href="#Research">Research</a></li>
<li><a href="#ProblemSolvingPrototyping">Prototype / Problem Solving</a></li>
<li><a href="#DrawingBoard">Back To The Drawing Board</a></li>
<li><a href="#Production">Production</a></li>
<li><a href="#QuestionsEvaluationsReflections">Questions, Evaluations & Reflections</a></li>
<li><a href="#FinalConclusion">Final Conclusion - 8 months after</a></li>


<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/2.jpg" style="height: 200px !important; object-position: 50% 60% !important;">
<h3 id="Proposal" style="text-align:center; margin-top: 20px; margin-bottom: 20px">My Proposal</h3>
<p>For the project, I wrote a proposal, and for this proposal document, I include many things, like the concept of what I will be doing, and videos and photographs or programs which inspire me.</p>
<p>I also write an evaluation on how I’m going to tackle this project, including the different libraries and skills I would need for this and how I think I’m going to approach the project, with a bibliography section at the bottom for all researched resources I am going this use. This would involve primary and secondary research.</p>
<p>Here are the important parts of my proposal:</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Concept</h4>
<p>The bare minimum I wanted to do was produce a graph from inputted values and my code would find a path from point x to y.</p>
<p>My extended task is to make a handful of ‘maps’ with certain characters being certain things, like <strong>‘X’</strong> being a wall and <strong>‘.’</strong> Being an empty spot. I would let the user input the directory of any map, and even their own custom maps, and then the program would output the shortest route to the finish point.</p>
<p>If I’m able to finish this project quickly and I have some extra time, I have the idea to visualize the program using OpenGL with simple squares for each space in the map, an empty square would be white and a wall would be black, and then I could have the process of the pathfinding make the squares glow up the shortest route.</p>
<details>
    <summary>Software/Sources Needed</summary>
    <p>There are a few software and sources which came in handy to use throughout the project these include but aren’t limited to:</p>
    <div>
        <table style="border-collapse: collapse; width: 100%; height: 180px;" border="1">
        <tbody>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px; text-align: center;">Tool/Software</td>
        <td style="width: 50%; height: 18px; text-align: center;">Reason For Use</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">Microsoft Word/PowerPoint</td>
        <td style="width: 50%; height: 18px;">Planning documents</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">Trello &amp; Tape</td>
        <td style="width: 50%; height: 18px;">Project management</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">WordPress</td>
        <td style="width: 50%; height: 18px;">Writing development blog</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">YouTube</td>
        <td style="width: 50%; height: 18px;">Inspiration, research &amp; study</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">C++ Documentation / Books</td>
        <td style="width: 50%; height: 18px;">Any C++ help I need</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">OpenGL Documentation</td>
        <td style="width: 50%; height: 18px;">Any OpenGL help I need</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">Google</td>
        <td style="width: 50%; height: 18px;">General help</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">Zotero</td>
        <td style="width: 50%; height: 18px;">Manage all my sources for the bibliography</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 50%; height: 18px;">Programming Game AI By Example (Book)</td>
        <td style="width: 50%; height: 18px;">Study graph theory and algorithms</td>
        </tr>
        </tbody>
        </table>
    </div>
</details>
<details> 
    <summary>Action Plan</summary> 
    <p>I find it very useful to make action plans, as it helps me make sure I stay on track and don’t spend too long on a specific task.<br />As I only had a few weeks to work on this, I made sure that my action plan was that long.</p>
    <div>
        <table style="border-collapse: collapse; width: 100%; height: 198px;" border="1">
        <tbody>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">Week</td>
        <td style="width: 65.211%; height: 18px;">Plan</td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">1</td>
        <td style="width: 65.211%;">
        <ul>
        <li aria-level="1"><strong>Prototype something! </strong><span style="font-weight: 400;">(Prototypes Page)</span></li>
        <ul>
        <li style="font-weight: 400;" aria-level="2"><span style="font-weight: 400;">Unity Visualisation, or</span></li>
        <li style="font-weight: 400;" aria-level="2"><span style="font-weight: 400;">C++ Small Example</span></li>
        </ul>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">2</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Plan a project. (Research Page)</span></li>
        <ul>
        <li style="font-weight: 400;" aria-level="2"><span style="font-weight: 400;">Flowchart/Diagram</span></li>
        <li style="font-weight: 400;" aria-level="2"><span style="font-weight: 400;">Trello organization</span></li>
        </ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Research into sorting algorithms (Research Page)</span></li>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Reflect on Prototype work (Research Page)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">3</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Project Work (Development Log)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">4</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Project Work (Development Log)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">5</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Project Work (Development Log)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">6</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Project Work (Development Log)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">7</td>
        <td style="width: 65.211%;">
        <p><strong>Finish Project</strong></p>
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Project Work (Development Log)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">8</td>
        <td style="width: 65.211%;">
        <p><strong>Tidy Project</strong></p>
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Project Polish/Cleaning (Development Log)</span></li>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Evaluation (Evaluation Page)</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">9</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Evaluation (Evaluation Page)</span></li>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Document</span></li>
        </ul>
        </td>
        </tr>
        <tr style="height: 18px;">
        <td style="width: 1.4556%; height: 18px; text-align: center;">10...</td>
        <td style="width: 65.211%;">
        <ul>
        <li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Document</span></li>
        </ul>
        </td>
        </tr>
        </tbody>
        </table>
    </div>                   
</details>   

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/3.jpg" style="height: 200px !important; object-position: 50% 60% !important;">
<h3 id="Research" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Research</h3>
<p>I wasn’t going to go straight into the final project when starting this, because prototypes are really important to make sure you’re doing everything right! This was the first part of the research I have done.</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Read & Sort Input From Text Files</h4>
<p>For my first prototype, I was hoping to find the path by using a maze that was made with a text file, so I would need to learn how to read and output any text file.<br />I was then hoping to sort these file contents into something I can use with pathfinding.</p>
<p>To learn how to read files, I have done some googling into how it works, and I found out that it was very easy to do!</p>
<p>To sort the file contents, I needed to think about how I should store them.<br />I did planning into what class structure would work best for each space in the map, and I also researched into 2D arrays as these seemed like the best way to store the nodes at the time.</p>
<img src="/assets/img/posts/TOGA/sorting.PNG" class="center-img">
<h4 style="margin-top: 20px; margin-bottom: 20px">Sorting Algorithms</h4>
<p>I looked into how I can find the shortest route to the end position, and how I can check if my inputted maze was valid.</p>
<p>From this, I read up on Breadth-First Search, Depth First Search, A*, and Dijkstra’s Algorithm.</p>
<img src="/assets/img/posts/TOGA/4.jpg" class="center-img">
<p>Out of all of these algorithms, and with the timeframe I had for this project, I decided that I should put A* and Dijkstra’s Algorithm aside for now, so I can study Breadth/Depth First Search, another reason for picking these algorithms is because it would be overkill to use A*/Dijkstra’s because my mazes really wouldn’t be too large so the slower execution times of Breadth/Depth-First search is nothing to worry about.</p>

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/5.jpg" style="height: 200px !important; object-position: 50% 70% !important;">
<h3 id="ProblemSolvingPrototyping" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Problem Solving & Prototyping</h3>
<h4 style="margin-top: 20px; margin-bottom: 20px">Getting The Maze & Outputting</h4>
<p>I started my prototype by outputting the lines which were on the maze in the text file which I had made.</p>
<h5>Getting The Line Count & Printing The .txt: </h5>
{% highlight cpp %}
    int lineCount = 0;
    string line;
    ifstream route(".../maze.txt");

    while(getline(route, line))
    {
        cout << line << endl;
        ++lineCount;
    }
    cout << "Number of lines is: " << lineCount << endl;
{% endhighlight %}
<h5>User Input: </h5>
<p>This was the change I made to the first few lines so the user can put in whatever maze they want to put in, even their own made up mazes!</p>
{% highlight cpp %}
    cout << "Input a maze file directory: ";
    cin >> directory;
    ifstream route(directory);
{% endhighlight %}
<h5>Output: </h5>
{% highlight txt %}
    xxxxxxx
    xA...Bx
    xxxxxxx
    Number of lines is: 3
{% endhighlight %}
<h5>For Loop (Checking Everything Is Working): </h5>
<p>I then ran a for loop which printed out what each space was, so I can check the output and make sure it’s correct.</p>
{% highlight cpp %}
    for(int i = 0; i < map_length; i++)
    {
        switch(line[i])
        {
        case 'x':
            cout << "WALL!" << endl;
            break;
        case '.':
            cout << "Empty" << endl;
            break;
        case 'A':
            cout << "Start Point" << endl;
            break;
        case 'B':
            cout << "End Point" << endl;
            break;
        }
    }
{% endhighlight %}
<h4 style="margin-top: 20px; margin-bottom: 20px">Making a 2D Array</h4>
<p>I began thinking how I can organize my data to work like a 2D map.<br />And I thought a 2D array would work the best, and I can treat the 2D array like X and Y coordinates.<br />I used for loops to go through each character in each line and set its value.</p>
<h5>Setting Up The Map As A 2D Array: </h5>
{% highlight cpp %}
    char mapPoints[10][10];
    for(int i = 0; i < 9; i++)
    {
        //for each individual character in the array
        mapPoints[i][k] = line[k];
        cout << line[k];
    }
    //for each line in the array
    cout << endl;
    lineCount++;
{% endhighlight %}
<h5>Storing X & Y Coordinates For The Start & End Points: </h5>
{% highlight cpp %}
    switch(line[k])
    {
        case 'A':
            x_startPoint = k;
            y_startPoint = i;
            break;
        case 'B':
            x_endPoint = k;
            y_endPoint = i;
            break;
    }
{% endhighlight %}
<h4 style="margin-top: 20px; margin-bottom: 20px">Difference Between Points</h4>
<p>With the current code, I was able to calculate the difference between two coordinate points, and I did this by subtracting the x coordinate of the start and endpoint and subtracting the y coordinate of the start and endpoint, but this didn’t take obstacles into consideration.</p>
<h5>Difference Calculation: </h5>
{% highlight cpp %}
    cout << "Difference between: " << "(" << difference(x_endPoint, x_startPoint) << ", " << difference(y_endPoint, y_startPoint) << ")" << endl;
{% endhighlight %}
<h5>Output: </h5>
{% highlight txt %}
    Starting Point is: (5, 4)
    Ending Point is: (7, 0)
    Difference between: (2, -4)
{% endhighlight %}
<h4 style="margin-top: 20px; margin-bottom: 20px">Space Class</h4>
<p>I needed to check the state of a node, and so I decided to make a space class for each space in the maze. Looking back now, I should’ve called this ‘node’.<br />This class would check if it’s a wall, if it’s been visited and what its x and y coordinates are.</p>
{% highlight cpp %}
    class space
    {
        public:
            bool isWall;
            bool isVisited;
            int x_Space;
            int y_Space;

            space()
            {
                isWall = false;
                isVisited = false;
                x_Space = 0;
                y_Space = 0;
            }
    }
{% endhighlight %}
<h4 style="margin-top: 20px; margin-bottom: 20px">How Can I Proceed?</h4>
<p> <i class="fas fa-exclamation-circle fa-2x" style="vertical-align: middle;"></i> &emsp; At this point, I got stuck on how I could implement BFS.</p>
<p>So… I decided to start everything again as there had to be a better way to do this! I knew I was getting way too ahead of myself.<br />I found a book called ‘Programming Game AI by Example’ and used this to aid me with my research.</p>

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/6.jpg" style="height: 200px !important; object-position: 50% 70% !important;">
<h3 id="DrawingBoard" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Back To The Drawing Board!</h3>
<h4 style="margin-top: 20px; margin-bottom: 20px">Graph Data Structures</h4>
<p>Following my failed pathfinding attempt before the assessment, I knew exactly what was wrong with my approach, so I had to do some more research into Graphs in general.<br />I realized my mistake through presenting the pathfinding attempts to a few people who knew more about the subject and asking them for feedback, so using the book mentioned and google, I did more research into Graph Data Structures.</p>
<img class="center-img" src="/assets/img/posts/TOGA/datastruct.PNG" style="width: 100% !important;">
<p>I’ve taken some notes as I was studying, it’s very useful for me to make these so I can reference them whenever I’m stuck on remembering something about graphs later on. These notes were taken from Chapter 5 of Programming Game AI by Example.<br />This section of the book covered the basics of using graph data structures in code, it covered it in a great amount of detail that I didn’t have to do much further research into graph data structures after this.</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Searching Algorithms</h4>
<p>Now I had more of an understanding of how to deal with each node in a graph, a lot more began making sense after studying graph data structures!</p>
<p> <i class="fas fa-laugh fa-2x" style="vertical-align: middle;"></i> &emsp; This was a major turning point within the project.</p>
<h5 style="margin-top: 20px; margin-bottom: 20px">Breadth First Search Study</h5>
<p>I did lots of googling into BFS and I watched a lot of videos on pathfinding to see exactly how it works. Doing this research taught me about Adjacency Lists and Adjacency Matrices and their importance within a pathfinding algorithm like this.<br />It also taught me about queueing and what the terms ‘FIFO’ (First in first out) and ‘LIFO’ (Last in first out) meant.</p>
<blockquote> “An adjacency list is a collection of unordered lists used to represent a finite graph. Each unordered list within an adjacency list describes the set of neighbors of a particular vertex in the graph.” (‘Adjacency List’, 2021) </blockquote>
<img src="/assets/img/posts/TOGA/bfsStudy.PNG" class="center-img">

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/7.jpg" style="height: 200px !important; object-position: 50% 40% !important;">
<h3 id="Production" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Production</h3>
<p>This is where based upon the new stuff I’ve learned, I would change up my approach a bit, and instead of using a text file with crosses and dots as a maze I would draw out the maze, and use different data in the text file.</p>
<p>So, I drew out a maze to help me visualize this, and on this maze, I would need to put nodes on each important point of the maze.</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Simplified Nodes</h4>
<p>There was 2 options when putting in nodes, the first option is that I can make very simplified node points like this:</p>
<img src="/assets/img/posts/TOGA/simpNode.PNG" class="center-img">
<p> <i class="fas fa-plus-square fa-2x" style="vertical-align: middle;"></i> &emsp; The pros of having simplified nodes are it would be faster! And the adjacency list for this would be much smaller as there are fewer contact points!</p>
<p> <i class="fas fa-minus-square fa-2x" style="vertical-align: middle;"></i> &emsp; But this comes with the cons of it obviously being simplified so if this was made for a game, it wouldn’t feel as realistic as there are fewer walking points within the maze, this concept is similar to increasing the subdivisions in a model!</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Advanced Nodes</h4>
<p>The other option is to add more nodes, to have more points on the maze!</p>
<img src="/assets/img/posts/TOGA/advNode.PNG" class="center-img">
<p> <i class="fas fa-plus-square fa-2x" style="vertical-align: middle;"></i> &emsp; This would give much more realistic movement if this was a player navigating a maze as there are many more points to move between.</p>
<p> <i class="fas fa-minus-square fa-2x" style="vertical-align: middle;"></i> &emsp; But this comes with the cons of having a massive adjacency list and being slower to execute as there are more nodes.</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Adjacency List Text File</h4>
<p>So, the data which would be going into the text file for the input of the maze is the adjacency lists! So, I went ahead and wrote out the adjacency list into the text file, with the format of the two connecting nodes and then ending the line for the next connecting nodes.</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Adjacency List In Code</h4>
<p>There was two functions which I wrote to make the text file work with my code:</p>
<h5>Text Line Count Function</h5>
<p>This function gets the adjacency list text file and counts how many lines it has, it then returns that for us to put as an input for our graph, as that is how many nodes our graph would have.</p>
<p>But looking at this now, this wouldn't be the number of nodes on our graph at all! Instead, I should've counted the nodes by the highest number on the text file.</p>
{% highlight cpp %}
    int TextLineCount()
    {
        string txt;
        int lines = 0;
        ifstream input;
        input.open("adjList.txt");

        while (!input.eof())
        {
            getline(input, txt);
            lines++;
        }
        return lines;
    }
{% endhighlight %}
<h5>Adjacent List Graph Function</h5>
<p>This function takes a graph input and then uses our adjacency list text file to add all the edges onto our graph</p>
{% highlight cpp %}
    void adjacentListGraph(Graph g)
    {
        ifstream file("adjList.txt");
        vector<int> roots;
        vector<int> destinations;

        int r, d;

        while(file >> r >> d)
        {
            roots.push_back(r);
            destinations.push_back(d);
        }

        for(int i = 0; i < roots.size(); i++)
        {
            g.addEdge(roots[i], destinations[i]);
        }
    }
{% endhighlight %}
<h4 style="margin-top: 20px; margin-bottom: 20px">Creating The Graph Class</h4>
<p>The graph class was one of the biggest changes I made from the prototype, and my Programming Game AI By Example book helped me with understanding how I can make the best graph class I could.</p>
<h5>Graph Class</h5>
{% highlight cpp %}
    class Graph
    {
        int vertex;
        list<int>* adjacencyList;
    public:
        Graph(int v)
        {
            this->vertex = v;
            adjacencyList = new list<int>[v];
        }

        void addEdge(int fromNode, int toNode);
        void BFS(Graph g, int root, int dest);
    }
{% endhighlight %}
<p>This is my Graph Class.</p>
<p>In the constructor, I set the integer ‘vertex’ equal to the size we set our graph to.</p>
<p>I then made a new list under a private variable called ‘adjacencyList’ – This list is a list of integer values which is the length of the graphs' inputted size.</p>
<p>I also define 2 methods in this Graph class.</p>
<h5>Add Edge Function</h5>
{% highlight cpp %}
    void Graph::addEgde(int fromNode, int toNode)
    {
        adjacencyList[fromNode].push_back(toNode);
        adjacencyList[toNode].push_back(fromNode);
    }
{% endhighlight %}
<p>The addEdge function connects two graph nodes. <br />We need to push back both the fromNode and toNode if we want to backtrack through the adjacency list which means going (1-&gt;5) and (5-&gt;1).</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Implementing Breadth First Search</h4>
<p>Because of the research I’ve done, implementing BFS was one of the simpler tasks. I watched a few theory videos and studied the BFS Wikipedia article to help me with the implementation.</p>
<h5>BFS Function</h5>
{% highlight cpp %}
    void Graph::BFS(Graph g, int root, int dest)
    {
	    bool* nodeIsVisited = new bool[vertex];
	    list<int> queue;
	    nodeIsVisited[root] = true;
	    queue.push_back(root);

	    // Checking if our inputted values are valid.
	    if (root >= 27 || dest >= 27 || root < 0 || dest < 0)
	    {
		    cout << "Invalid path." << endl;
		    return;
	    }

	    // Setting all the booleans for each node to not visited
	    for (int i = 0; i < vertex; i++)
	    {
		    nodeIsVisited[i] = false;
	    }

	    // While our queue isn't empty, iterate though all the edges of our current node and set it to visited
	    while (!queue.empty())
	    {
		    int v = queue.front();
		    cout << v << endl;
		    queue.pop_front();

		    if (v == dest)
		    {
			    cout << "Got to destination: " << v << " = " << dest << endl;
			    return;
		    }	

		    for (list<int>::iterator it = adjacencyList[v].begin(); it != adjacencyList[v].end(); it++)
		    {
			    int vertex = *it;

			    if (!nodeIsVisited[vertex])
			    {
				    nodeIsVisited[vertex] = true;
				    queue.push_back(vertex);
			    }
		    }
	    }
    }
{% endhighlight %}
<p>This function runs a Breadth-First Search Traversal on our graph.<br />Starting from the parameters at the top, this function takes an input of our graph (we need something to search through!), a starting position, and an ending position.</p>
<p>Let's break this down a bit!</p>
<h6>The Function's Variables</h6>
{% highlight cpp %}
	bool* nodeIsVisited = new bool[vertex];
	list<int> queue;
	nodeIsVisited[root] = true;
	queue.push_back(root);
{% endhighlight %}
<p>Here, we make a bool, which is the visited check, and this is what each node has in our graph.<br />And then we make a list of integers that are empty for now for our queue.<br />And then we put our root into the queue so we don’t visit the root again.</p>
<h6>Setting Values</h6>
{% highlight cpp %}
	for (int i = 0; i < vertex; i++)
	{
		nodeIsVisited[i] = false;
	}
{% endhighlight %}
<p>Here we are simply setting all of the isVisited booleans for each node to false, so they can be visited.</p>
<h6>Setting Values In The While Loop</h6>
{% highlight cpp %}
	int v = queue.front();
	cout << v << endl;
	queue.pop_front();
{% endhighlight %}
<p>Inside the while loop that runs while our queue isn't empty, I made a variable called ‘v’ which sets it to the node which is at the front of the queue, and print out our current node, and pop the front node from the queue.</p>
<h6>Checking Values</h6>
{% highlight cpp %}
	if (v == dest)
	{
		cout << "Got to destination: " << v << " = " << dest << endl;
		return;
	}	

	for (list<int>::iterator it = adjacencyList[v].begin(); it != adjacencyList[v].end(); it++)
	{
        //...
	}
{% endhighlight %}
<p>In the same while loop, I check if ‘v’ (the variable we just set) is our destination, and if it’s not, we iterate through all the edges connected to the ‘v’ node.</p>
<h6>Within The Iterator</h6>
{% highlight cpp %}
	for (list<int>::iterator it = adjacencyList[v].begin(); it != adjacencyList[v].end(); it++)
	{
		int vertex = *it;

		if (!nodeIsVisited[vertex])
		{
			nodeIsVisited[vertex] = true;
			queue.push_back(vertex);
		}
	}
{% endhighlight %}
<p>Within that iterator, I set the vertex integer to be the currently connected node I am checking, this is so I can check the status of each node, which is what I want to do next.</p>
<p>If the node hasn’t been visited, set the node to visited and add them onto the queue.</p>
<p>We repeat this process until we get to the destination node!</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Video Showcase</h4>
<div class="video-container" style="padding-top: 0px !important">
    <iframe src="https://drive.google.com/file/d/1C8TiIuQeq4WS3JJyIAI0HcKs3fAvzNXC/preview" width="100%" height="500" frameborder="0"></iframe>
</div>

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/8.jpg" style="height: 200px !important; object-position: 50% 40% !important;">
<h3 id="QuestionsEvaluationsReflections" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Questions, Evaluations & Reflections</h3>
<h4 style="margin-top: 20px; margin-bottom: 20px">Efficiency Of Code</h4>
<p>It’s really important to make sure your code is efficient, so I went through my code and made sure it was as efficient as possible, as well as I did some research into how to write more efficient code, in case I had missed anything, and I came across a video by James Scholz, (2019) titled: ‘Write BETTER Code! 7 Tips to Improve Your Programming Skills’ – Following the tips presented in this video, I further cleaned up my code!</p>
<h5>Limit Function Arguments</h5>
<p>I don’t have an example of this within my code, but an idea I had to further limit function arguments is with the BFS function, and make a class that holds all of the current inputs of the function, so that function only has one argument, but in a way, I don’t think the way I do it currently is bad either because it is quite clear what it’s asking for and making those arguments a single class may make things even more confusing.</p>
<h5>Declaring Variables Close To Their Usage</h5>
<p>I made sure I was doing this throughout my code, an example for seeing this is the textLineCount() function, where I’m declaring variables within the function and not at a global level, and each variable I’ve declared is close to the area which it’s being used in the code.</p>
<h5>Functions Should Do One Thing</h5>
<p>This was something I noticed right away! My BFS function does the breadth-first search, but it also checks if our inputted values are valid! This check would’ve been better in its own function which is called at that stage of the BFS!</p>
<p>Otherwise, I was efficient with my addEdge function as this only adds edge, the textLineCount is fine.</p>
<p>I was efficient with my adjacentListGraph function as this adds all of the edges onto our graph from the text file, but I feel I could’ve named this better.</p>
<h5>Stop Writing Zombie Code</h5>
<p>I made sure any unused commented-out code was deleted, to make everything clean!</p>
<details>
    <summary>What do other people think about this?</summary>
    <p>I thought it would be interesting to know what other people think about this, so I made a survey to ask what they think the most important aspects of efficient code were, I also asked them why they thought that.</p>
    <img src="/assets/img/posts/TOGA/surv1.png" class="center-img">
    <p>80% of the public thought that the most important way to write efficient code was to make functions only do one thing, and then 60% of the public thought limiting function arguments was the 2<sup>nd</sup> most important way to write efficient code.</p>
    <p>I personally think that avoiding abbreviation of variable names and making sure functions only do one thing is the most important.</p>
    <p>I also asked for their reasoning!</p>
    <img src="/assets/img/posts/TOGA/surv2.png" class="center-img">
</details>
<h4 style="margin-top: 20px; margin-bottom: 20px">Problem Solving</h4>
<p>Throughout the development of the project, there were a few problems that I had to solve, one of the biggest being understanding the fundamentals of graph data structures and how to write my node class.<br />I initially made a class called ‘space class’ which had many parameters to check for each space, but through my research on Graph Theory and Path Searching Algorithms, I was able to write a Graph class that was able to do everything I needed for this program.</p>
<details>
    <summary>I asked people how they might add creativity & originality into their code...</summary>
    <p>I was interested to see how other people would do this, so I made a survey to ask, some of their answers were great! I believe the creativity from code comes from how you structure it and the problem-solving you perform!</p>
    <img src="/assets/img/posts/TOGA/surv3.png" class="center-img">
</details>
<h4 style="margin-top: 20px; margin-bottom: 20px">Professionalism</h4>
<p>I read a blog by Punit Sharma, (2016) titled: ‘Writing Professional Code in C++’ – Following the steps presented in this blog, I was able to change my code to be more professional and understand the best coding practices.<br />The tips I followed were:</p>
<p>Indent code properly so it’s following the agreed style, this also makes it easier to read!</p>
<p>Comment and Document code!</p>
<p>And, an extra one - Avoid abbreviations of variable names!</p>
<details>
    <summary>I also asked how other people make their code as professional as possible!</summary>
    <p>I asked in the survey how other people might make their code as professional as possible – So many people are able to work on it without getting confused, there were some really good answers here!</p>
    <img src="/assets/img/posts/TOGA/surv4.png" class="center-img">
</details>
<h5>Indentation Styles</h5>
<p>This is very important to writing professional-looking code, and easy-to-understand code, because if the indentation is all over the place, it doesn’t look right!</p>
<p>Throughout the entirety of my code, I use the ‘Allman Style’ of indentation, which uses broken brackets, although sometimes on other projects, I find myself using ‘Java Style’ indentation, which uses attached brackets.</p>
<p>The Allman style of indentation is something which I find myself doing without thinking about it, and in my opinion, I think it looks the neatest!</p>
<h5>Documentation</h5>
<p>With my code, I made sure it was commented, but not too heavily as I don’t want to be commenting on anything which is very obvious! <br />I commented on things that I thought were important to know, but I didn’t go into too much detail with these comments as I believe I have written my code out in a way that it should be easy enough to read through and understand!</
<h5>Avoiding Abbreviation Of Variables</h5>
<p>Within my work, I made sure each variable name was as descriptive as possible, without being too wordy, but I knew I missed out on a few variables which could have better names, like the integer ‘v’ in the Graph declaration which is the current vertex point, but I couldn’t use the variable name ‘vertex’ as I was already using it. In the future, I will make sure I don’t use one-letter variable names.</p>
<h4 style="margin-top: 20px; margin-bottom: 20px">Initial Conclusion</h4>
<p>Writing a Breadth-First Search (BFS) Traversal tool was great fun.</p>
<p>Initially, I thought doing this wouldn’t be too hard, but it soon turned out to be a great challenge to develop my knowledge and learning skills.</p>
<p>Realizing that I was taking the wrong approach was one of the most important and interesting mistakes I made as it led to me finding the ‘Programming Game AI by Example’ book which I’ve talked about throughout this blog, this book is now one of my favorite books, as it helped me learn so many new things, and gave me a different perspective on how I can think of graphs! This book has also made me discover my interest in learning AI in the future.</p>
<p>This new knowledge gained from the book allowed me to confidently write a successful BFS tool, and this is important to me as a learner, as it’s made me realize, I can code anything which I want to as long as I put in the time to study and not rush headfirst into things.</p>
<p>Another important experience taken from producing this is understanding more about how pathfinding works, as previously, I didn’t know too much about this, and I was using built-in tools within the game engines to make pathfinding work.</p>
<p>So now, having learned and applied pathfinding to a simple maze, I think I can create my own pathfinding tools for any games which I am making!</p>
<p>As a next step, I need to learn about other pathfinding algorithms and apply them to my code, this would allow me to compare the complexity and outcome of these algorithms and use that knowledge for any pathfinding I want to do.</p>

<details>
    <summary>Bibliography/Mentioned Sources</summary>
    <p>Adjacency list. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Adjacency_list&amp;oldid=1016707698</p>
    <p><em>Adjacency list representation of graph | Adjacency list</em>. (n.d.). Retrieved 24 February 2021, from https://www.log2base2.com/data-structures/graph/adjacency-list-representation-of-graph.html</p>
    <p>Breadth-first search. (2021). In <em>Wikipedia</em>. https://en.wikipedia.org/w/index.php?title=Breadth-first_search&amp;oldid=1005991607</p>
    <p>Buckland, M. (2004). <em>Programming Game AI by Example</em>. Wordware.</p>
    <p>cplusplus. (n.d.). <em>Input/output with files</em>. Retrieved 22 April 2021, from https://www.cplusplus.com/doc/tutorial/files/</p>
    <p>James Scholz. (2019, January 20). <em>Write BETTER Code! 7 Tips to Improve Your Programming Skills</em>. https://www.youtube.com/watch?v=vfqvzgkYYF0&amp;ab_channel=AndySterkowitz</p>
    <p>Parmpreet Gill. (2020, June 5). <em>03. Graph Data Structure | Creating Adjacency List in C++ | Coding Blocks</em>. https://www.youtube.com/watch?v=dhgKr8942rs&amp;ab_channel=mycodeschool</p>
    <p>Sharma, P. (2016, November 14). <em>Writing Professional Code in C++</em>. http://theoryofprogramming.com/2016/11/14/writing-professional-code-c/</p>
    <p>W3Schools. (n.d.). <em>C++ Files</em>. Retrieved 22 April 2021, from https://www.w3schools.com/cpp/cpp_files.asp</p>
</details>

<hr>
<img class="image-heading" src="/assets/img/posts/TOGA/9.jpg" style="height: 200px !important; object-position: 50% 40% !important;">
<h3 id="FinalConclusion" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Final Conclusion</h3>
<p>As you can see from the publish date of this blog, I've written this in January of 2022, around 8 months after I've completed this.</p>
<p>Within these 8 months, I've <strong>finished my first year of University</strong>, <strong>worked an internship at Jagex</strong>, and am currently <strong>working on a placement year at Sumo Digital</strong>, working in <strong>C++</strong> and <strong>C#</strong> in a <strong>professional setting</strong>, so I now look back at this work and can see how much I've improved in my programming skills since then.</p>
<p>Learning about the different pathfinding algorithms has most definitely made an impact on my programming skills over those months, as, like mentioned, it made me realize that I can do and implement anything as long as I put the time in to study it, no matter how complicated it looks.</p>
<p>Working in a professional setting made me realize that some of the code I've written <strong>isn't</strong> as professional as it can be, and something that's been sticking out to me is the <strong>inconsistent style</strong> and <strong>naming conventions</strong> throughout the code!</p>
<p>Naming conventions are <em>really</em> important, and in my time in the industry, there is always a style guide which is stuck to which <strong>ensures that everything stays neat and easy to search through</strong> as the codebase gets bigger and bigger. The other benefit of this is that if a new person joins, it would be easier for them to pick up the code as everything is all neat and tidy!</p>
<p>A weakness with my approach to this is that I feel I should've tried to contact some professional programmers as I was doing this to get feedback on the professionalism of my code and to ask them questions.</p>
<p>If I were to approach something like this in the future again, I would most definitely do more research into what I'm working on to ensure I understand what I'm doing before I do it, and also talk to more people for feedback!</p>
<p>And from this, I know I'm going to do lots more studying into algorithms as they're so much fun!</p>
<p>I'm really excited to carry on growing and improving as a programmer! </p>
<hr>

