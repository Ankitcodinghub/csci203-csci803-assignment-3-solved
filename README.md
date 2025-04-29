# csci203-csci803-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSCI203/CSCI803 ASSIGNMENT 3 Solved](https://www.ankitcodinghub.com/product/csci203-csci803-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;33673&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI203\/CSCI803 ASSIGNMENT 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This assignment involves an extension to the single source – single destination shortest path problem.

&nbsp;

<h1>The Program</h1>
&nbsp;

Your program should:

<ol>
<li>Open the text file “ass3.txt”. (Note: “ass3.txt” should be a hardcoded as a constant.)</li>
<li>Read a graph from the file.</li>
<li>Find the shortest path between the start and goal vertices specified in the file.</li>
<li>Print out the vertices on the path, in order from start to goal.</li>
<li>Print out the length of this path and the total number of vertices visited.</li>
<li>Devise a strategy for determining the second shortest path between the vertices.</li>
<li>Find the second shortest path between the start and goal vertices specified in the file.</li>
<li>Print out the vertices on the path, in order from start to goal.</li>
<li>Print out the length of this path and the total number of vertices visited.</li>
<li>Optimize your shortest and second shortest path algorithms to improve their performance.</li>
</ol>
The data files are constructed as follows:

&nbsp;

<ul>
<li>Two integers: nVertices and nEdges, the number of vertices and edges in the graph.</li>
<li>nVertices triples consisting of the label and the x- and y-coordinates of each vertex.</li>
<li>nEdges triples consisting of the labels of the start and end vertices of each edge, along with its weight. Note: the weight associated with an edge will be greater than or equal to the Euclidean distance between its start and end vertices as determined by their coordinates.</li>
<li>Two labels, the indicating the start and goal vertices for which the paths are required.</li>
</ul>
&nbsp;

A proposed solution to the second shortest path problem is as follows:

&nbsp;

For each edge e<sub>i</sub> on the shortest path:

Find the shortest path on (V, E – {e<sub>i</sub>}).&nbsp;&nbsp;&nbsp; <em>// shortest path without edge e<sub>i</sub></em> The shortest of these is the second shortest path.

&nbsp;

<h1>Questions</h1>
<strong>&nbsp;</strong>

Think about this! Is this proposed solution correct always?

<ul>
<li>What if we require that the second shortest path be longer than the shortest path?</li>
<li>What if the graph contains cycles?</li>
<li>What if the graph is undirected?</li>
</ul>
Explain your answers. If necessary explain how you might modify the proposed algorithm to address any issues that you identify.

&nbsp;

Note: you may implement either the proposed solution or any modification you develop. You are not required to implement a modified proposal if you do not wish to do so.

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</strong>

<strong>&nbsp;</strong>

<h1>Step-1 (Week-10 demo, 2 marks)</h1>
For step 1, you should read the data file into adjacency lists, or an adjacency matrix, and print on the screen the first 5 vertices and the vertices they are connected to together with their weights. e.g.:

&nbsp;

<strong>a:&nbsp; c(35)&nbsp; d(27)&nbsp; e(48) b:&nbsp; d(35)&nbsp; g(27) </strong>

<strong>c:&nbsp; b(125) e(20)&nbsp; f(56)&nbsp; h(31)&nbsp; . . . </strong>

Note: The data shown above is for format purposes only.

&nbsp;

<h1>Step-2 (Discovering the Shortest Path) (2 marks)</h1>
For step 2, you should implement Dijkstra’s algorithm and find the shortest path between the start and goal vertices specified in the input file. Print out the vertices on the path (in order from start to goal), the length of this path and the total number of nodes visited by the algorithm to discover the shortest path.

<strong>&nbsp;</strong>

<h1>Step-3 (Discovering the Second Shortest Path) (4 marks)</h1>
For step 3, you should devise a strategy for determining the second shortest path between the start and goal vertices specified in the file and implement your solution. Print out the vertices on the path (in order from start to goal), the length of this path and the total number of nodes visited by the algorithm to discover the second shortest path.

<strong>&nbsp;</strong>

<h1>Step-4 (Optimisation) (2 marks)</h1>
For step 4, implement the A* algorithm and repeat Step-2 and Step-3. Print the same information to show the improved performance.

<strong>&nbsp;</strong>

<h1>Step-5 (Report) (2 marks)</h1>
In a comment block at the bottom of your program (no more than 30 lines of text) list the data structures used by your program and describe your solution to the second shortest path problem. Also, provide answer to the questions. For this step, marks will be awarded based on accuracy and correctness.

<strong>&nbsp;</strong>

<strong>Compilation: </strong>

All programs submitted must compile and run on banshee:

<strong>C: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; gcc ass2.c&nbsp; </strong>

<strong>&nbsp;</strong>

<strong>C++: &nbsp;&nbsp;&nbsp;&nbsp; g++ ass2.cpp </strong>

<strong>&nbsp;</strong>

<strong>Java: &nbsp;&nbsp;&nbsp; javac ass2.java </strong>

<strong>&nbsp;</strong>

<strong>Python: python ass2.py </strong>

<ul>
<li>Programs which do not compile on banshee with the above commands will receive zero marks. It is your responsibility to ensure that your program compiles and runs correctly.</li>
</ul>
<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Marking Guide: </strong>

<ul>
<li>Marks will be awarded for the appropriate use of data structures and the efficiency of the program at processing the input and producing the correct output.</li>
<li>Marks may be deducted for untidy or poorly designed code.</li>
<li>Appropriate comments should be provided where needed.</li>
<li>There will be a deduction of up to 4 marks for using STL, or equivalent libraries, rather than coding the data structures and algorithms yourself. You may use <em>string</em> or <em>String </em>type for storing words or text, if you wish.</li>
<li>All coding and comments must be your own work.</li>
</ul>
&nbsp;

<strong>Submission: </strong>

Assignments should be typed into a single text file named “ass2.<em>ext” </em>where <em>“ext” </em>is the appropriate file extension for the chosen language. You should run your program and copy and paste the output into a text file named: “output.txt”

&nbsp;

<strong>Submit your files via the <em>submit</em> program on banshee: </strong>

&nbsp;

<h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; submit -u <em>user </em>-c csci203 -a 3 ass3.<em>ext output.txt</em></h2>
<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; – where <em>user</em> is your unix userid and <em>ext</em> is the extn of your code file. </strong>

&nbsp;

Late assignment submissions without granted extension will be marked but the points awarded will be reduced by 1 mark for each day late.&nbsp; Assignments will not be accepted if more than five days late. An extension of time for the assignment submission may be granted in certain circumstances.&nbsp; Any request for an extension of the submission deadline must be made via SOLS before the submission deadline. Supporting documentation should accompany the request for any extension.
