# cs303-project-2--heuristic-search-for-capacitated-arc-routing-problem-solved
**TO GET THIS SOLUTION VISIT:** [CS303 Project 2- Heuristic search for capacitated arc routing problem Solved](https://www.ankitcodinghub.com/product/cs303-heuristic-search-for-capacitated-arc-routing-problem-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116221&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS303 Project 2- Heuristic search for capacitated arc routing problem Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
(CARP)

1 Overview

In this project you need to design and implement heuristic search algorithms for CARP, a classical NP-hard arc routing problem. An introduction to CARP (including problem formulation and solution representation) can be found in the slides we provide (CARP.pdf). Overall, CARP is a constrained optimization problem, and your algorithm needs to find high-quality feasible solutions to it. The scores you get in this project will be given according to your algorithm’s performance in our test.

2 General Rules

After you submit your project, we will run some scripts to test your CARP solver on different CARP problem instances. To make this process as smooth as possible, the package you submit must satisfy the following requirements.

1) Project Report

A report about CARP(in pdf format) must be submitted, in which you should describe the core idea of your design, entail each component of your algorithm, illustrate the algorithm structure and give the pseudo code. (Grading criteria of the

2) Programming aspects

Project2_Score = Coding_Score *0.7+ Report_Score *0.3

3) Input and output

a) Input

In the test, we will repeatedly call your CARP solver through scripts. Specifically, the format of the solver call is as follows (the test environment is Unix-like):

python CARP_solver.py &lt; CARP instance file &gt; -t &lt;termination&gt; -s &lt;random

seed&gt;

𝐂𝐀𝐑𝐏_𝐬𝐨𝐥𝐯𝐞𝐫. 𝐩𝐲 is your executable CARP solver.

&lt; 𝐜𝐚𝐫𝐩 𝐢𝐧𝐬𝐭𝐚𝐧𝐜𝐞 𝐟𝐢𝐥𝐞 &gt; −𝐭 &lt; 𝐭𝐞𝐫𝐦𝐢𝐧𝐚𝐭𝐢𝐨𝐧 &gt; −𝐬 &lt; 𝐫𝐚𝐧𝐝𝐨𝐦 𝐬𝐞𝐞𝐝 &gt; are the arguments passed to your CARP solver

&lt; 𝐜𝐚𝐫𝐩 𝐢𝐧𝐬𝐭𝐚𝐧𝐜𝐞 𝐟𝐢𝐥𝐞 &gt; is the absolute path of the test CARP instance file −𝐭 &lt; 𝐭𝐞𝐫𝐦𝐢𝐧𝐚𝐭𝐢𝐨𝐧 &gt; specifies the termination condition of your algorithm. Specifically, &lt;termination&gt; is a positive number which indicates how many seconds (in Wall clock time, range: [60s, 600s]) your algorithm can spend on this instance. Once the time budget is consumed, your algorithm should be terminated immediately.

−𝐬 &lt; 𝐫𝐚𝐧𝐝𝐨𝐦 𝐬𝐞𝐞𝐝 &gt; specifies the random seed used in this run. In case that your solver is stochastic, the random seed controls all the stochastic behaviors of your solver, such that the same random seeds will make your solver produce the same results. If your solver is deterministic, it still needs to accept −𝐬 &lt; 𝐫𝐚𝐧𝐝𝐨𝐦 𝐬𝐞𝐞𝐝 &gt;, but can just ignore them while solving CARPs.

You can use multithread, but the number of thread shall not exceed 8.

In summary, your CARP solver needs to:

 handle the arguments passed from our scripts while being called as above

 measure the runtime, and terminate after the time budget is consumed.

Typically, in python 3.6 you can measure runtime using time.time(): start = time.time()

…solving carp

run_time = (time.time() – start)

Note here although our tests rely on your solver’s internal time measurement, we will still measure your solver’s runtime from external, so make sure that your solver’s internal time measurement is accurate.

 use random seeds to control all the stochastic behaviors

b) Output

Your solver must print messages to the standard output. These messages will be used to evaluate this solver run. Your solver has to print two lines. Each of them, according to its first char, must belong to one of the categories described below. Lines that do not start with one of the patterns below will be considered a comment and hence ignored.

Solution line begins with a lower case “s” followed by a space (ASCII code 32). Only one such line is allowed and it is mandatory. The best solution your solver has found for the CARP problem instance must be printed in this line. The format of the solution can be found in the slides we provide (CARP.pdf). For example, for the CARP instance given below, the “s” line is:

s 0,(1,2),(2,4),(4,1),0,0,(4,3),(3,1),0

Quality line begins with a lower case “q” followed by a space (ASCII code 32). Only one such line is allowed and it is mandatory. The solution quality (i.e., the total cost) of your best found solution must be printed in this line. The “q” line of the above example is:

q 15

4) Format of CARP problem instance

The format of the CARP problem instances can be found in the instruction we provide (CARP_format.txt), and we also provide some CARP instance files as examples (CARP_samples/). 3 Evaluation

We divide the solver evaluation into three parts:

Usability test 50%): In this test we will use some CARP problem instances to check whether your solvers are usable. Here the meanings behind usability are twofold:

a) (25%) Your solvers can satisfy the input and the output requirements (See Section 2). The failure cases include: cannot handle the inputs, the output messages are undesirable (missing ‘s’ line or ‘q’ line, the format of the output solution is incorrect or the total cost of the output solution is not correctly calculated), crash.

b) (25%) The best found solution output by your solver is a feasible solution (since CARP is a constrained problem). Infeasible solutions violate at least one constraints of CARP.

Once your solvers have passed a test, you will get all the corresponding scores. Note only those solvers that have been through test a) will be tested in b).

Efficacy test (50%): In this test we will focus on how good your solvers are. Specifically, we will select different CARP instances with different sizes from existing CARP benchmarks to test your solvers. For each instance, we will set a common cutoff time for all participant solvers and compare their solution quality.

The scores you get in this test depend on the rankings your solvers obtain. Note only those solvers that have been through usability tests will be tested in efficacy tests.

The scores you get in this test depend on the rankings your solvers obtain. Note only those solvers that have been through the usability test will be tested in the robustness test. A bonus will only be awarded if you perform well on both the efficacy and robustness tests.

4 Test Environment

A website for you to submit your code and online judge: http://10.20.99.199/.

When signing in for the first time, your username is your student ID, and your initial Password can be found in the comments of CARP OJ Password on gradebook of Sakai You can try to submit your code to OJ, when the task is finished, you can see your result in “RankList Stage 1”, it gives -1 when your cost is wrong. It gives 0 when your codes have issues. You can click “Download All” to download all log files. We will grade the last version of your code (not the best version).

Configuration of the OJ environment：

1) Operation System: Debian 10

2) Server CPU：2.2GHz*2, 8-core total

3) Python version: 3.9.7
