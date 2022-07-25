# FlowShop2

The aim for this research project is identify the optimal job sequence in a flowshop. 

We want to find out:
  <li> The ideal locations for the jobs.
  <li> How to decluster the monster jobs.
  <li> Can a formula be generated.  
    
    
    
<dl>
<dt>Antithetic sequences in flowshop scheduling</dt>
  <dd></dd>  
<dd>Special cases of monster cell dominance</dd>
<dd>Describing effects of monster cell of dominance in flow shop – [A flowshop is one in which all of the jobs follow essentially same path from one machine to another] </dd>
<dd>Scheduling with minimization of mean lateness – [ The difference between the completion-time of a job and some pre-specified due date associated with that job] [ Lateness considers the algebraic difference for each job, regardless of the sign of the difference] </dd>
<dd>Difference between Lateness, Tardiness and Earliness – they are three different ways of comparing the actual completion-time [ The time at which processing of the last operation of the job is completed] with the desired completion-time.  Li= Ci-di=Fi-ai</dd>
<dd>Tardiness- is equivalent to lateness when lateness is positive, otherwise equal to zero; it considers only positive differences; jobs which are completed after their due-dates. Ti= max(0,Li) </dd>
<dd>Earliness- considers only negative differences; jobs completed ahead of their due-dates. Ei=max(0,-Li) </dd>

<dd>Monster cell has processing time [pi= Total processing time]; that is much larger than any other time in the system. </dd>
<dd>Other cases; </dd>
<ul>
<li>having two monster cell of equivalent processing times, much larger than any. </li>
<li>having two monster cells; one having time much larger than other; and both (times)- individually or combined dominating all other cells by considerable amount</li>
</ul>
<dd>Pair of sequence- Antithetic- when jobs of one are processed in reverse order of the other</dd>
<dd>Sequencing and scheduling – effects of dominance; basic case of machine dominance</dd>
<dd>In which the (smallest processing time)- {smallest time it or least amount of time taken to complete job} on the first machine is larger or greater than (largest processing time) – {biggest or most amount of time taken to complete job} on the second machine. </dd> 
<dd>When flowshop has more than two machines;- several patterns can happen- that could be observed, </dd>
<ul>
<li>Increasing chain of machine dominance</li>
<li>Decreasing chain of machine dominance</li>
<li>Increasing then decreasing chain of machine dominance (“pointed hat-pattern”)</li>
<li>Decreasing then increasing chain of machine dominance (“a V-pattern”)</li>
</ul>
<dt>Researchers found optimal solutions for pointed hat and V-pattern dominance</dt> 
<dd>To minimize the:</dd>
<ul>
<li>Maximum Flowtime [ The total time that the jobs spends in the shop] [Flowtime is also called manufacturing interval and shop-time.]</li>
<li>Maximum Lateness [ The difference between the completion-time of a job and some pre-specified due date associated with that job] [ Lateness considers the algebraic difference for each job, regardless of the sign of the difference] </li>
<li>Maximum Tardiness [- is equivalent to lateness when lateness is positive, otherwise equal to zero; it considers only positive differences; jobs which are completed after their due-dates. Ti= max(0,Li)] </li>
<li>Mean flowtime</li>
<li>Mean machine completion time</li>
<li>Number of tardy jobs</li>
</ul>
</dl>
