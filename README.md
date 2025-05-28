# cs6250-summer-2025-distance-vector-solved
**TO GET THIS SOLUTION VISIT:** [CS6250 Summer 2025 Distance Vector Solved](https://www.ankitcodinghub.com/product/cs6250-summer-2025-distance-vector-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;135986&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6250  Summer 2025  Distance Vector Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<strong>Distance Vector</strong>

<strong>Table of Contents </strong>

<a href="#_Toc12179">PROJECT GOAL………………………………………………………………………………………………………………… 2 </a>

<a href="#_Toc12180">Part 0: Getting Started………………………………………………………………………………………………….. 2 </a>

<a href="#_Toc12181">Part 1: Files Layout……………………………………………………………………………………………………….. 2 </a>

<a href="#_Toc12182">Part 2: TODOs………………………………………………………………………………………………………………. 3 </a>

<a href="#_Toc12183">Part 3: Testing and Debugging……………………………………………………………………………………….. 4 </a>

<a href="#_Toc12184">Part 4: Assumptions and Clarifications……………………………………………………………………………. 4 </a>

<a href="#_Toc12185">Part 5: Correct Logs for Provided Topologies……………………………………………………………………. 6 </a>

<a href="#_Toc12186">Part 6: Spirit of the Project……………………………………………………………………………………………. 7 </a>

<a href="#_Toc12187">Part 7: FAQs…………………………………………………………………………………………………………………. 8 </a>

<a href="#_Toc12188">What to Turn In………………………………………………………………………………………………………………. 9 </a>

<a href="#_Toc12189">What you can and cannot share………………………………………………………………………………………… 9 </a>

<a href="#_Toc12190">Rubric…………………………………………………………………………………………………………………………… 10 </a>

&nbsp;

&nbsp;

&nbsp;

<strong>&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong>

<h1><a name="_Toc12179"></a>PROJECT GOAL</h1>
In the lectures, you learned about Distance Vector (DV) routing <strong>protocols,</strong> one of the two classes of routing protocols. DV protocols, such as RIP, use a fully distributed algorithm to find shortest paths by solving the Bellman-Ford equation at each node. In this project, you will develop a distributed Bellman-Ford algorithm and use it to calculate routing paths in a network. This project is similar to the Spanning Tree project, except that we are solving a routing problem, not a switching problem.

In “pure” distance vector routing protocols, the hop count (the number of links to be traversed) determines the distance between nodes. Some distance vector routing protocols, that operate at higher levels (like BGP), must make routing decisions based on business valuations. These protocols are sometimes referred to as Path Vector protocols. We will explore this by using weighted links (including negatively weighted links) in our network topologies.

We can think of Nodes in this simulation as individual Autonomous Systems (ASes), and the weights on the links as a reflection of the business relationships between ASes. Links are directed, originating at one Node, and terminating at another.

<h2><a name="_Toc12180"></a>Part 0: Getting Started</h2>
You should review some materials on Bellman-Ford. Some resources include:

<ul>
<li>Wikipedia (<a href="https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm">https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm</a><a href="https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm">)</a></li>
<li>“Computer Networking: A Top-Down Approach” by Kurose and Ross o 7<sup>th</sup> edition discusses the algorithm on pages 384-385 in Chapter 5 (“The Network Layer: Control Plane”)</li>
</ul>
Download and unzip the Project Files for Distance Vector from Canvas in the Assignments section. This project can be completed in the class VM or on your local machine using Python

3.10.x. You must be sure that your submission runs properly in Gradescope.

<h2><a name="_Toc12181"></a>Part 1: Files Layout</h2>
The DistanceVector directory contains the following files:

<ul>
<li>py – This is the only file you will modify. It is a specialization (subclass) of the Node class that represents a network node (i.e., router) running the Distance Vector algorithm, which you will implement.</li>
<li>py – Represents a network node, i.e., a router.</li>
<li>py – Represents a network topology. It is a container class for a collection of DistanceVector Nodes and the network links between them.</li>
<li>py – A simple “driver” that loads a topology file (see *Topo.txt below), uses that data to create a Topology object containing the network Nodes, and starts the simulation.</li>
<li>*Topo.txt – These are valid topology files that you will pass as input to the run.sh script (see below). Topologies should end with “.txt”.</li>
<li>txt – This is an invalid topology file, provided as an example of what not to do, and so you can see what the program says if you pass it a bad topology.</li>
<li>py – This script can be run on the log output from the simulation to verify that the output file is <strong>formatted</strong> correctly. It does not verify that the contents are correct, only the format.</li>
<li>sh – A helper script that runs some basic system checks, the topology, and the validator, a wrapper for run_topo.py and output_validator.py .</li>
</ul>
<h2><a name="_Toc12182"></a>Part 2: TODOs</h2>
There are a few TODOs in DistanceVector.py:

<ol>
<li><strong><em>Review the methods already implemented in Node.py</em></strong>.
<ol>
<li>Because DistanceVector is a subclass of Node, consider how you might use the existing methods to complete the TODOs in this list.</li>
<li><strong>Do NOT modify Node.py</strong>.</li>
</ol>
</li>
<li><strong><em>Decide on how each node will represent its distance vector</em></strong>.
<ol>
<li>Consider what might be the simplest data structure to keep track of path weights (i.e., the distance vector).</li>
<li>The distance vector variable should be local to the Node, i.e., defined in the init function as a variable accessible via the `self` object (i.e. self.mylist). C. <strong><em>Implement the Bellman-Ford algorithm</em></strong>.</li>
<li>Each Node will:
<ol>
<li>send out an initial message to its neighbors</li>
<li>process messages received from other nodes</li>
</ol>
</li>
</ol>
</li>
</ol>
<ul>
<li>send updates to other nodes as needed</li>
</ul>
<ol>
<li>Initially, a node only knows of:</li>
<li>itself and that it is reachable at cost 0,</li>
<li>its neighbors and the weights on its links to its neighbors</li>
</ol>
<ol>
<li>NOTE: a node’s links are <strong>unidirectional</strong>.</li>
<li>NOTE: The Bellman-Ford algorithm implementation should terminate naturally without external intervention.</li>
<li><strong><em>Write a logging function</em></strong> that is specific to your distance vector structure.</li>
</ol>
<ol>
<li>You should use the <em>add_entry</em> function to help with logging.</li>
<li>You should assume that the logging function only knows itself.</li>
<li><strong>Do NOT access the topology for logging</strong>; logging should happen at the Node level.</li>
</ol>
<h2><a name="_Toc12183"></a>Part 3: Testing and Debugging</h2>
To run your algorithm on a specific topology, execute the run.sh bash script:

./run.sh *Topo

Substitute the correct, desired filename for *Topo. Don’t use the .txt suffix on the command line. This will execute your implementation of the algorithm in DistanceVector.py on the topology defined in *Topo.txt and log the results (per your logging function) to *Topo.log .

<strong>NOTE</strong>: You should <em>not</em> include the full filename of the topology when executing the run.sh script. For example, to run the algorithm on topo1.txt you should only specify topo1 as the argument to run.sh.

For this project, you may create as many topologies as you wish and share them on Ed Discussion. We encourage sharing new topologies with log outputs. Topologies with format errors will get an error back when you try to run them.

We’ve included four good topologies for you to use in testing and one bad topology to demonstrate invalid topology. <strong>The provided topologies do not cover all the edge cases; your code will be graded against more complex topologies</strong>.

<h2><a name="_Toc12184"></a>Part 4: Assumptions and Clarifications</h2>
<ol>
<li><strong>Node behavior: </strong></li>
<li>The direction of a link indicates how <strong>traffic</strong> will flow; two nodes connected with a link <strong><em>may pass messages regardless of traffic direction</em></strong>.</li>
<li>Example: Node B has an incoming link from Node A, but has no outgoing link to Node A, Node B will send its distance vector to node A to</li>
</ol>
“advertise” &nbsp;&nbsp;&nbsp; other &nbsp;&nbsp;&nbsp; nodes &nbsp;&nbsp;&nbsp; it &nbsp;&nbsp;&nbsp; can &nbsp;&nbsp;&nbsp; reach &nbsp;&nbsp;&nbsp; (Nodes &nbsp;&nbsp; C &nbsp;&nbsp;&nbsp; and &nbsp;&nbsp;&nbsp; D).

&nbsp;

<ol>
<li>A Node’s distance vector is comprised of the nodes it can reach via its outgoing links (<strong><em>including</em></strong> to itself at distance = 0).</li>
<li>A Node will never advertise a negative distance to itself. (Important for negative cycles.)
<ol>
<li>A Node advertises its distance vector to its <strong><em>upstream</em></strong></li>
<li>Nodes do <strong>not</strong> implement poison-reverse.</li>
</ol>
</li>
<li><strong>Edge and Path weights: </strong>
<ol>
<li>Edge weight values may be between <strong>-50 and 50, inclusive.</strong></li>
<li>The edge weight value type is an <strong>integer</strong>.</li>
<li>There is no upper limit for path weights.</li>
<li>The lower limit for path weights is “-99”, which is equivalent to “negative infinity” for this project. <strong> Negative cycles: </strong></li>
<li>A Node can forward traffic through a negative cycle.</li>
<li>Negative cycles are a series of directed links that originate and terminate at a single node, where the sum of the link weights is less than 0.
<ol>
<li>This can lead to a negative “count-to-infinity” problem. Therefore, your implementation must be able to detect negative cycles to <strong>terminate on its own</strong>.</li>
<li>Any node that can reach a destination node and infinitely traverse a negative cycle enroute will set the distance to that node to -99.</li>
<li>Your implementation only needs to detect and record these traversals appropriately; it does not need to mitigate them.</li>
</ol>
</li>
</ol>
</li>
</ol>
<ul>
<li>A Node can advertise a negative distance for other nodes (but not for itself).</li>
</ul>
<ol>
<li>A Node that receives an advertisement with a distance of -99 from a downstream neighbor should also assume that it can reach the same destination at infinitely low cost (-99).</li>
<li><em>Example</em>: Traffic from Node F to Node D can route through A-&gt;B-&gt;C-&gt;A indefinitely to reach an extremely low (very negative) value.</li>
</ol>
&nbsp;

<ol>
<li>A Node will <strong><em>not</em> </strong>forward traffic destined to itself.</li>
<li>Example: The below topology will <strong><em>not</em></strong> result in a count-to-infinity problem, as there are no possible pairs of source and destination nodes where traffic could indefinitely traverse a negative cycle. Node A will not forward traffic for Node A, and similarly for Nodes B and C.</li>
</ol>
&nbsp;

&nbsp;

<ol>
<li>Topologies used in grading:</li>
</ol>
<ol>
<li>We will be using many topologies to test your project. This includes but is not limited to:
<ul>
<li>topologies with and without cycles (loops), including odd length cycles o topologies of varying sizes, including topologies with more than 26 nodes&nbsp; o topologies with nodes with names longer than one character o topologies with multiple paths to different nodes</li>
<li>topologies that include any combination of positive weights, zero weight, and negative weight</li>
<li>topologies with negative cycles, meaning a node may reach another at infinitely low cost</li>
<li>topologies with Nodes that do not have incoming or outgoing links ▪ All nodes will be connected but:
<ul>
<li>some may have both incoming and outgoing links</li>
<li>some may only have incoming links some may only have outgoing links</li>
</ul>
</li>
</ul>
</li>
</ol>
<ol>
<li>We will NOT test your submission against the following topologies (which means your algorithm does not need to account for them):
<ul>
<li>topologies with more than one link from <em><u>the same origin to the same</u> <u>destination</u></em> (multi-graphs)</li>
<li>topologies with portions of the network disconnected from each other</li>
</ul>
</li>
</ol>
(partitioned networks) o topologies that do not require intermediate steps (such as a topology with a single node)

<ul>
<li>topologies with a valid path between two indirectly linked nodes with no cycle with an actual total cost of ≤ -99 (topologies will respect that -99 is “negative infinity” for this project)</li>
</ul>
<h2><a name="_Toc12185"></a>Part 5: Correct Logs for Provided Topologies</h2>
Below are the correct final logs for the provided topologies. We are providing them to help you identify correct behavior with respect to negative cycles and the assumptions in the instructions. <strong><em>We are only providing the final round; each topology should produce at least 2 rounds of output. </em></strong>

SimpleTopo:

A:(A,0) (B,1) (C,3) (D,3) B:(B,0) (A,1) (C,2) (D,2) C:(C,0) (B,2) (A,3) (D,0) D:(D,0) (C,0) (B,2) (A,3) E:(E,0) (D,-1) (C,-1) (B,1) (A,2)

&nbsp;

SingleLoopTopo:

A:(A,0) (D,5) (E,6) (B,6) (C,16) B:(B,0) (A,2) (D,7) (C,10) (E,0) C:(C,0) D:(D,0) (E,1) (B,1) (A,3) (C,11) E:(E,0) (B,0) (A,2) (D,7) (C,10)

&nbsp;

SimpleNegativeCycle:

<h3>AA:(AA,0) (AD,-2) (AE,-1) (AB,0) (CC,-99) AB:(AB,0) (AA,-1) (AD,-3) (CC,-99) (AE,-2) AD:(AD,0) (AE,1) (AB,2) (AA,1) (CC,-99) AE:(AE,0) (AB,1) (AA,0) (AD,-2) (CC,-99) CC:(CC,0) (AB,0) (AA,-1) (AD,-3) (AE,-2)</h3>
&nbsp;

ComplexTopo:

ATT:(ATT,0) (CMCT,-99) (TWC,-99) (GSAT,-8) (UGA,-99) (VONA,-11) (VZ,-3) CMCT:(CMCT,0) (TWC,-99) (ATT,1) (VONA,-10) (GSAT,-7) (UGA,-99) (VZ,-2) DRPA:(DRPA,0) (EGLN,1) (GT,-1) (UC,-1) (CMCT,-99) (TWC,-99) (ATT,13) (OSU,-1) (VONA,2) (GSAT,5) (UGA,-99) (PTGN,1) (VZ,10) EGLN:(EGLN,0) (GT,-2) (UC,-2) (DRPA,1) (CMCT,-99) (OSU,-2) (TWC,-99) (ATT,13) (PTGN,0) (VONA,3) (GSAT,5) (UGA,-99) (VZ,11) GSAT:(GSAT,0) (VONA,-3) (VZ,5) (UGA,-99) (ATT,7) (CMCT,-99) (TWC,-99) GT:(GT,0) (UC,0) (EGLN,2) (OSU,0) (DRPA,3) (PTGN,2) (CMCT,-99) (VONA,5) (TWC,-99) (ATT,15) (VZ,13) (GSAT,7) (UGA,-99) OSU:(OSU,0) (UC,0) (GT,0) (EGLN,2) (PTGN,2) (VONA,5) (DRPA,3) (VZ,13) (GSAT,7) (CMCT,-99) (ATT,15) (UGA,-99) (TWC,-99) PTGN:(PTGN,0) (OSU,-1) (UC,-1) (GT,-1) (EGLN,1) (VONA,3) (VZ,11) (GSAT,5) (DRPA,2) (ATT,13) (UGA,-99) (CMCT,-99) (TWC,-99) TWC:(TWC,0) (CMCT,-99) (ATT,1) (VONA,-10) (VZ,-2) (GSAT,-7) (UGA,-99) UC:(UC,0) (GT,0) (EGLN,2) (OSU,0) (PTGN,2) (DRPA,3) (VONA,5) (CMCT,-99) (VZ,13) (GSAT,7) (TWC,-99) (ATT,15) (UGA,-99) UGA:(UGA,0) (ATT,50) (CMCT,-99) (TWC,-99) (GSAT,42) (VONA,39) (VZ,47) VONA:(VONA,0) (VZ,8) (GSAT,2) (ATT,10) (UGA,-99) (CMCT,-99) (TWC,-99) VZ:(VZ,0) (ATT,2) (CMCT,-99) (TWC,-99) (GSAT,-6) (UGA,-99) (VONA,-9)

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h2><a name="_Toc12186"></a>Part 6: Spirit of the Project</h2>
The goal of this project is to implement a simplified version of a network protocol using a distributed algorithm. This means that your algorithm should be implemented at the network node level. Each network node only knows its internal state, and the information passed to it by its direct neighbors. Declaring global variables will be a violation of the spirit of the project.

The skeleton code we provide you runs a simulation of the larger network topology. For simplicity, the Node class defines a link to the overall topology. This means it is possible using the provided code for one Node to access another Node’s internal state. <strong>This goes against the spirit of the project and is not permitted. </strong>If you have questions about whether your code is accessing data it should not, please ask on Ed Discussion or during office hours!

You should not use any global variables for managing any data relating to the Nodes. However, you may use a global variable as a setting. I.E.: NEGATIVE_INFINITY = -99

<h2><a name="_Toc12187"></a>Part 7: FAQs</h2>
<strong><em>Q: May I import a python module into DistanceVector.py? For example, may I use import collections, typing, etc.&nbsp; </em></strong>

A: Your solution should not require any outside Python modules. Please do not import any other modules.

<strong><em>Q: What is the best way to format and process node messages? </em></strong>

A: There is no right or wrong way to format messages. For best results keep things simple.

<strong><em>Q: Is it required that the distance vectors displayed in my log files be alphabetized? </em></strong>

A: Look at the <em>finish_round</em> function in Toology.py. Note how the DVs are alphabetized each round, and this is reflected in the provided correct output logs. The nodes within individual vectors are not required to be sorted.

<strong><em>Q: Should my solution include an implementation of split horizon? </em></strong>

A: That is not a requirement for this project.

<strong><em>Q: What if there really is a valid path between two indirectly linked nodes with no cycle and the total cost is -99 or less? </em></strong>

<ol>
<li>We will not test your submission against a topology that does this. However, from the “Assumptions and Clarifications”, note: <u>“a Node seeing an advertised vector of -99 from a</u> <u>downstream neighbor can assume this means it can reach that same destination at infinitely</u> <u>low cost (-99)</u>.”</li>
</ol>
<h1><a name="_Toc12188"></a>What to Turn In</h1>
To complete this project, submit ONLY your DistanceVector.py file to Gradescope as a single file. Do not modify the name of DistanceVector. You can make an unlimited number of submissions to Gradescope. Your last submission will be your grade unless you activate a different submission.

&nbsp;

There are some very important guidelines for this file you must follow:

<ol>
<li><strong>Ensure that your submission self-terminates.</strong> If your submission runs indefinitely (i.e., contains an infinite loop) or throws an error at runtime, it will not receive full credit. Manually killing your submission via console commands or interrupts is NOT an acceptable means of termination.</li>
<li><strong>Remove any print statements from your code before turning it in.</strong> Print statements left in the simulation, particularly for inefficient but logically sound implementations, have drastic effects on run-time. Ideally, your submission should take less than 10 seconds to process a topology. If your leave print statements in your code and they adversely affect the grading process, your work will not receive full credit. (Feel free to use print statements during the project and during debugging but remove them before you submit.)</li>
<li><strong>Ensure your logs are formatted properly</strong>. Logging is the only way that we can verify that your algorithm is running correctly. The output validator will catch most formatting mistakes, but you should inspect your output manually to make sure it matches the requested format. (See the TODO comment for logging located in DistanceVector.py for format details.)</li>
<li>Incorrectly formatted logs will fail the auto grader and <em>will receive no credit</em>. We will not be manually inspecting incorrectly named/formatted/etc. logs due to the number of students in the class.</li>
<li><strong>Ensure your solution generates completely correct output. </strong>Partial credit for individual topologies will not be awarded, even if the distance vector logs are “mostly correct.”</li>
<li><strong>Check your submission after uploading. </strong>As usual, we do not accept resubmissions past the stated deadlines.</li>
</ol>
<h1><a name="_Toc12189"></a>What you can and cannot share</h1>
Do not share the content of your DistanceVector.py file with your fellow students, on Ed Discussion, or elsewhere publicly. You may share any log files for any topology, and you may also share new topologies. Additionally, code that you write that is not required for turn-in, like testing suites may be shared. It may be a good idea to share a “correct” log for a particular topology, if you have one, when you share the code for that topology.

When sharing log files, leave alphabetization on so that your classmates can use the diff tool to see if you are getting the same log outputs as they are.

All work must be your own, and consulting Distance Vector Routing solutions, even in another programming language or just for reference, are considered violations of the honor code. Do not reference solutions on Github! Do not use IDE extensions (like Github Copilot) that write or recommend blocks of code to you (autocomplete for function names is fine). For more information see the Syllabus Definition of Plagiarism. We have worked hard to provide you with all the material you need to complete this project without help from Google/Stack Overflow (Searching basic Python syntax is fine). Don’t risk an honor code violation for the project.

<h1><a name="_Toc12190"></a>Rubric</h1>
&nbsp;

<table width="632">
<tbody>
<tr>
<td width="35">40 pts</td>
<td width="126">Provided

Topologies&nbsp; (4 total)

&nbsp;
</td>
<td width="471">For correct Distance Vector results (log file) on the provided topologies.</td>
</tr>
<tr>
<td width="35">60 pts</td>
<td width="126">Unannounced

Topologies (4 total)

&nbsp;
</td>
<td width="471">For correct Distance Vector results (log file) on topologies that you will not see in advance. They are slightly more complex than the provided ones and test some edge cases.

&nbsp;
</td>
</tr>
</tbody>
</table>
&nbsp;

GRADING NOTE: There is no partial credit for individual topologies; each topology is either “passed” or “failed”.

As with previous projects in this course, due to the size of the class, we will not accept resubmissions, modifications to old submissions past the deadline, etc.
