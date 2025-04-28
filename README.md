# ce295-homework-3-optimal-economic-dispatch-in-distribution-feeders-solved
**TO GET THIS SOLUTION VISIT:** [CE295 Homework 3-Optimal Economic Dispatch in Distribution Feeders Solved](https://www.ankitcodinghub.com/product/ce295-hw3-optimal-economic-dispatch-in-distribution-feeders-with-renewables-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119335&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CE295 Homework 3-Optimal Economic Dispatch in Distribution Feeders  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
This assignment will provide hands-on practice for optimization with application to the economic dispatch problem in power systems. The assignment is organized in a tutorial fashion, thereby allowing you to practice optimization theory on a relevant real-world energy system example.

Background

Consider the IEEE 13-node Test Feeder shown in Fig. 1, adopted from [2]. We mathematically represent this test feeder by a radial undirected graph

G = (N,L). Symbol N = {0,1,2,··· ,12} represents the set of nodes (a.k.a. “buses” in power systems jargon). Symbol L ⊂ N × N represents the set of edges (a.k.a. “lines” in power systems jargon). For notational convenience, we introduce the concepts of parent nodes and the adjacency matrix. The parent of j, ρ(j), is the adjacent node in the direction toward node 0. The adjacency matrix, A, encodes the network topology. Mathematically, it is a 13 × 13 matrix of zeros and ones. Aij = 1 if node i is the parent node of node j. Otherwise, Aij = 0.

At each node j ∈ N, we have ljP, ljQ active and re-

active power consumed, respectively. Additionally,pj,qj active and reactive power are generated, re- 12 7

spectively. Note that total power is complex num-

Power is supplied in two ways. First, power can be imported from the transmission grid connected to node 0. Second, power can be generated from distributed generators within the feeder network. We have a gas generator on node 3, and solar generator on node 9.

Your objective is to supply all electricity demand at minimum cost. Simultaneously, you must ensure all generator output powers, nodal voltages, and line currents are within safe operating bounds. Table 1: Nomenclature

Symbol Description Units

N Set of nodes (a.k.a. buses) [-]

E Set of edges (a.k.a. lines) [-]

ρ(i) Parent of node i, e.g. ρ(6) = {1}, ρ(12) = {10} [-]

A Adjacency Matrix (13×13) encoding network structure [-]

pi active power generated at node i [MW]

qi reactive power generated at node i [MVAr]

si apparent power generated at node i [MVA]

si,max apparent power generation capacity at node i [MVA]

active, reactive power consumed at node i [MW], [MVAr]

Vi Squared voltage magnitude at node i [p.u.]

vmin,vmax Minimum, maximum nodal voltage [p.u.]

ci Marginal cost of apparent power generation at node i [USD/MVA]

rij resistance of line (i,j) [p.u.]

xij reactance of line (i,j) [p.u.]

Pij active power flowing on line (i,j) [MW]

Qij reactive power flowing on line (i,j) [MVAr]

Lij Squared magnitude of complex current on line (i,j) [p.u.]

Iij Maximum magnitude of complex current on line (i,j) [p.u.]

WA,WB Uncertain &amp; weather-dependent power capacity of PV panels A,B [MVA]

σA,σB Percentage power output of PV panels A,B [%]

Note: The acronym “p.u.” stands for per-unit. It’s power systems jargon for “normalized to a unitless quantity”. For your convenience, all the data has been normalized to simplify your analysis. For interested readers, the base parameters for normalization in this HW are Sbase = 1 MW, Vbase = 4.17 kV.

∀ j ∈ N, i = ρ(j) (1)

∀ j ∈ N, i = ρ(j) (2)

∀ j ∈ N, i = ρ(j) (3)

∀ j ∈ N, i = ρ(j) (4)

∀ j ∈ N (5)

∀ j ∈ N (6)

∀ j ∈ N (7)

∀ j ∈ N (8)

∀ j ∈ N, i = ρ(j) (9)

Problem 1: Network Parameters

Download and open the data file HW_Data.xls. Copy over the test network parameters from the xls file into the Matlab/Python skeleton code file.

(a) Create a bar plot of the active and reactive power consumption. Make the x-axis the node index number, while the y-axis is the power consumption. Place the active &amp; reactive powers side-by-side for each node. Add a legend.

(b) Fill out the adjacency matrix with zeros and ones. Include in your report.

Problem 2: Balancing Supply &amp; Demand without a Network

Start simple: In this problem, we will optimally dispatch our generators to minimize cost, while disregarding the network completely. That is, we seek to balance active &amp; reactive power supply &amp; demand, while minimizing generation cost and completely ignoring line losses and constraints.

(a) What are the optimization variables?

(b) Write down the objective function, using the notation in Table 1.

(c) Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint. For this problem, ignore voltages and all constraints associated with line flows.

(d) Is this a linear program (LP), quadratic program (QP), or convex program (CP)? Why or why not? What happens when we relax (6) from an equality constraint to an inequality (≤) constraint?

(e) Code and numerically solve this problem in Matlab or Python using cvx or cvxpy, respectively. Use the relaxed version of (6), so your optimization program is convex. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost.

Problem 3: Add Line Power Flows

Next, we add line power flows Pij,Qij but still neglect the nodal voltage Vj and Lij terms.

(a) What are the optimization variables?

(b) Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint. For this problem, ignore (3)-(4) and drop the Lij terms from (1)-(2).

(c) Code and numerically solve this problem in Matlab or Python using cvx or cvxpy, respectively. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. Should the minimum and minimizers be different or the same as Problem 2? Why?

(d) In your code, declare a dual variable µs corresponding to the inequality (7). Re-compute the optimal solution and dual variable. If we could increase the solar power capacity by 1MW, then how much money would we save?

Problem 4: The Complete Optimal Economic Dispatch with DistFlow Equations

Now we add the nodal voltages Vj, squared current magnitudes Lij, and their bounds (8)-(9). This incorporates impedance (i.e. losses) across the network, along with nodal voltage and line transmission limits.

(a) What are the optimization variables?

(b) Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint.

(c) Is this a convex program (CP)? Why or why not? What happens when we relax (4) from an equality constraint to an inequality (≥) constraint?

(d) Code and numerically solve this problem in Matlab or Python using cvx or cvxpy, respectively. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. Use vmin = 0.95,vmax = 1.05 as your voltage limits. Is the solution equivalent to the solution in Problem 3? Why or why not?

(e) Use the dual variables to determine which constraints are active. Specifically, identify at which nodes the voltage constraint (8) and line current constraint (9) are active.

(f) Now re-solve the problem with vmin = 0.98,vmax = 1.02 as your voltage limits. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. Why did the solution change?

Problem 5: [OPTIONAL] Robust Economic Dispatch with Renewables. Next, we explore robust economic dispatch in the face of uncertain renewable generation. Imagine the solar generator at node 9 is comprised of two solar panels, A and B. The output of each panel is uncertain, and weather dependent. Mathematically, we write:

s9 ≤ WA · σa + WB · σb (10)

(a) Re-arrange (10) into the form aTy ≤ b. What are a, y, and b? Hint: a ∈ R3, y ∈ R3, b ∈ R.

(b) We now hypothesize that vector a is uncertain, but lies within an ellipsoid

a ∈ E = {a¯ + Eu | kuk2 ≤ 1} (11)

Provide the values for a¯ and E. Hint #1: a¯ ∈ R3 represents the center of the ellipsoid. Hint #2: encodes the lengths of the semi-axes. If E is diagonal, then the diagonal elements

represent the semi-axis lengths along each coordinate of a.

(c) The robust version of (10) is

aTy ≤ b, ∀ a ∈ E (12)

Convert this robust linear inequality into a second-order cone constraint. In your report, it is only necessary to provide the final written form of the second order cone constraint.

(d) In your report, write down the new robust optimization problem. What are the optimization variables? Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint.

(e) Now solve the optimization program with vmin = 0.95,vmax = 1.05 as your voltage limits. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. How did the solution change?

Interesting Remarks

• Power system operators utilize day-ahead load predictions to solve the economic dispatch problem and procure generation on an hourly basis. Mismatch between predicted and actual load is compensated by “spinning reserves”.

• This homework is not trivial. However, by completing it, you have quickly acquired sophisticated knowledge and skills in power systems and optimization. DistFlow equations, convex optimization, and robust optimization are skills one normally finds in power systems / optimization PhD students. Well done!

Deliverables

Submit the following on bCourses. Be sure that the function files are named exactly as specified (including spelling and case). Please do NOT zip files.

LASTNAME_FIRSTNAME_HW3.PDF

LASTNAME_FIRSTNAME_HW3.xyz which contains your respective Matlab or Python files, i.e. xyz ∈ {m, ipynb}.

How to Download and Install CVX

Matlab Instructions

• Go to http://cvxr.com/cvx/download/

• In the “Download Matrix”, focus your attention on the “Standard bundles, including Gurobi and/or MOSEK”.

• Click the package corresponding to your system. For example, I have a MacBook Pro Early 2015, so I’ll select mexmaci64. You can download a .zip or .tar.gz file.

• Download and unpack anywhere you like. The Downloads folder is a reasonable option.

• Start Matlab.

• Change directories to the top of the CVX distribution. Hint: Use command » cd /Users/scottmoura/

Downloads/cvx

• Run Matlab command » cvx_setup

• The cvx_setup command runs a variety of checks to verify your installation is correct.

• After successfully installing CVX, please go to http://cvxr.com/news/2014/02/cvx-demo-video/ to watch the Getting Started Demo from Prof. Stephen Boyd.

• To confirm a successful understanding, try coding and solving the example shown at http://cvxr.com/cvx/

Python Instructions

• Ensure you have installed Anaconda, as recommended in this class

• Go to https://www.cvxpy.org/install/index.html

• Follow the instructions corresponding to your system

• After successfully installing CVXPY, fire-up the iPython notebook. You can try the Portfolio optimization example linked here.

References

[1] M. Baran and F. Wu, “Network reconfiguration in distribution systems for loss reduction and load balancing,” IEEE Transactions on Power Delivery, vol. 4, no. 2, pp. 1401–1407, apr 1989. [Online]. Available: http://ieeexplore.ieee.org/document/25627/

[2] J. Fuller, Y. Xu, B. Kersting, R. Dugan, and S. Carneiro Jr., “IEEE PES Distribution Test Feeders,” 2010.

[Online]. Available: https://ewh.ieee.org/soc/pes/dsacom/testfeeders/
