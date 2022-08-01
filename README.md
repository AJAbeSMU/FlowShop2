# FlowShop2

The aim for this research project is identify the optimal job sequence in a flowshop. 

We want to find out:
  <li> The ideal locations for the jobs.
  <li> How to decluster the monster jobs.
  <li> Can a formula be generated.  
    
    
    
<dl>
<dt>What is my introduction? </dt>
<dd>Knowingly or unknowingly most of us would have dealt with scheduling challenges as part of our daily life. </dd>
<dd>If you think about it; the monthly payments we carry out; be it for rent; health insurance payments; car insurance payments; internet and phone bills all are scheduled for payment before the due date. </dd>
<dd>We need scheduling to plan our transactions. </dd>
<dd>As mentioned in the Introduction Chapter of Operations Scheduling with Applications in Manufacturing and Services; book by Michael Pinedo and Xiuli Chao; “The scheduling function in a company uses mathematical techniques or heuristic methods to allocate limited resources to processing of tasks. A proper allocation of resources enables the company to optimize its objectives and achieve its goal. Resources may be machines in a workshop; runways at an airport, stages in a construction project or computer programs to be executed. </dd>
<dd>In Industrial Scheduling by D.R Sule; “As the industrialized world develops, more and more resources are becoming critical. Machines, manpower, and facilities are now commonly thought of as critical resources in production and service activities. Scheduling these leads to increased efficiency, utilization and ultimately profitability. </dd> 
<dd>Scheduling is an act of defining priorities or arranging activities to meet certain requirements, constraints or objective. Scheduling critical resources machines, manpower & facilities leads to increased efficiency, utilization and ultimately profitability. </dd>
<dd>Scheduling is a tool that optimizes use of available resources. Scheduling leads to increased efficiency and capacity utilization reducing time required to complete jobs and consequently increasing the profitability of an organization. </dd>
<dd>An industry example: I would like to highlight with respect to how important of a role scheduling plays; Capacity Utilization for car manufacturers in the Indian market. The below figures are from the year 2016; and there are many new manufacturers; who are not listed here who are now available in the Indian market. </dd>
<dd>Even though this list is not current; one critical factor I would like for your attention is capacity utilization. Most organization with poor capacity utilization did not survive and are out of the market. </dd>
<dd>This example reinforces the fact that scheduling leads to increased efficiency and profitability of an organization for long-term growth. </dd>
<dd>I have personally experienced many petrochemical/ refinery plants turnarounds/shutdowns; both planned and in emergency situations, and it is always the contractor that bids with the best schedule; the schedule that completes the turnaround with the least days wins the bid. It does not matter if you have a lower quotation, because finishing the job in fewer days; helps the processing to come back on-line for the operating plant to begin production. If a plant is idle even for one day; the organization would loss millions in potential revenue generation. </dd>
<dd>So; again we see a good schedule wins contracts and beneficial for long term growth of an organization. </dd>
<dd>A usual objective is to develop a schedule that minimizes the makespan. </dd>
<dd>In a flowshop, a schedule that minimizes the makespan also minimizes other major objectives</dd>
<ul>
<li>Minimizing the sum of job waiting times and the sum of machine idle times.  </li>
</ul>

  <dt>Draft comments from Antithetic sequences in flowshop scheduling Research Project</dt>
  
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
<dd>Another manner dominace defined- flowshop problems with makespan minimization; </dd> 
<dd>In this case processing time (Job completing in machine) is larger then respective sums of processing times before and after that particular machine; to time considering tken to process after this machine for the same job. </dd>
<dd>Monster Machine Dominaces; MMD </dd>
<dd>Colume is largest across the board; </dd>
<dd>Monster Job Dominance; MJD </dd>
<dd>Processing times of given job are order of magnitude larger than all processing time. A particular job compared to all other jobs take the most amount of time to complete; irrespective of the machine completing the job. </dd>
<dd>Plot of average lateness of antithetic sequence; MJD is an extension of Type V dominance; </dd>
 <dd>New Type of Machine Dominance Proposed; </dd>
 <dd>Plotting average lateness of antithetic job sequence pairs under certain conditions of processing time matrix. - (Identify what are the certain conditions?) </dd>
<dd>Outline- efficient algorithm; </dd>
<dd>Software to implement algorithm; </dd>
<dd>Display and analyze visually (striking plots)- (What does this mean) </dd>
<dd>Result from plotting antithetic job sequence pairs; </dd>
<dd>Provide (insight) - reasons for striking formation </dd>
 <dt>Literature Review: Dominance in flowshop Research; dominance relation; facilitates(node pruning process?)  </dt>
<dd>Case;  σ1 & σ2; two partial schedules for same set of job S. σ1 dominates σ2; that means σ1 > σ2; if G(σ1σ) <= G(σ2σ); for every permutation σ of jobs in N-S- (What is N?) </dd>
<dd>Where G (σ)= is total tardiness for jobs in partial schedule σ & N; is the set of all jobs;- Did not understand! </dd>
<dd>Xia(2005)  </dd>
<ul>
<li>Minimization of makespan </li>
<li>And total flowtime of flowshops </li>
</ul>
<dd>With learning efects; polynominal algorithms- propose in machine have similar processing times & also case in which flowshops has increasing series of dominating machine. This is Type I </dd>
 
<dd>Modified (2012) to include learning effects; in which actual processing time of job is function of its position in a schedule. </dd>
<dd>Kuo(2012)- proposed heuristics to address objective function </dd>
<ul>
<li>Makespan </li>
<li>Total flowtime </li>
<li>Sum of weighted completion time</li> 
<li>Maximum lateness</li> 
<li>In minimization of maximum lateness for case-time- dependent learning effects in flowshop. </li> 
 </ul>
<dd>Monster Dominace </dd>
<dd>2 Cases </dd>
<dd>Case 1- Monster Machine Dominace(MMD)- occurs when processing times of a given machine are an order of magnitude larger than all other processing times; </dd>
<dd>The processing time is the time taken to complete task in one machine is most time taken comparing to the rest of machine. </dd>
<dd>Case 2- Monster Job Dominance(MJD)- occurs when processing times of given job are an order of magnitude larger than all other processing times. A given job takes the most time in total or also in each machine? </dd>
<dd>Comparing to other jobs that go through the same machines; as the largest job tasks? </dd>
<dd>This paper intorduces the Monster cell dominance. </dd>
 
<dt>Introduction </dt>
 <dd>Monster cell dominace; </dd>
<dd>In simplest form; it is defined as having a single job processing time that is order of magnitude larger than all other times in processing time matrix. </dd>
<dd>Antithetic properties of flowshop sequences used as vechile to formally define & analyze effects of monster cell dominace.  </dd>
<dd>Flowshop sequences is anthithetic= the order in which the jobs of one of the sequences are processed results if recersal in the other </dd>
<dd>Moras(1997) = Antithetic sequences may be used to obtain quick estimate of mean makespan when job processing times are randomly structured. - The jobs appear to be derived from the same probability distribution. </dd> 
<dd>The premises is the makespan distribtuion appears to follow a normal or near normal distribution. And in general; there is a certain degree of negative correlation in makespan obtained from an antithetic pair of sequenc. Reversing a sequence with relatively large makespan tends to result in sequence with shorter makespan. </dd>
 
<dd>Makespan in operations research, makespan of a project is the length of time that elapses from the start of work to the end.  </dd>
<dd>Type of Multi-mode resource constrained project scheduling problem (MRCPSP), seeks to create the </dd>
<ul>
<li>Shortest logical project schedule</li> 
<li>By efficiently using project resources </li>
<li>Adding the lowest number of additional resources </li>
</ul>
<dd>As possible to achieve the minimum makespan appears in context of scheduling. </dd>
<dd>Histograms= of makespan and mean lateness distributions; </dd>
<dd>Result in bell-shape curves; at first impression; resemble normal distribution; </dd>
<dd>Negative coorelation= appears to characterize </dd>
<ul>
<li>Makespan  </li>
<li>Mean lateness or antithetic sequence in randomly structured flowshops, </li>
 </ul>
<dd>Plot of makespan or mean lateness- of antithetic pair of sequence results in vaguely cloud of points; following 45-degree diagonals; cloud is symmetrical with a 45-degree line emerging at origin. </dd> 
 
<dd>Analysis= of several types of monster cell dominance in flowshop problem with minimization of mean lateness, plots- propose analytical methods to formally define monster cell dominance.  </dd>
 
<dd>First essential characteristic of monster job dominance is point clusters are grouped by the position of the monster job in the antithetic job sequence used to calculate the associated forward & reverse average lateness values of each point. </dd>
<dd>The forward job sequence with points in the bottommost and topmost point clusters start and end with the monster job. (I don’t understand the six point clusters in Fig.3; I am guessing each cluster is representation of an individual job) </dd>
<dd>Second esstential characterisitic of monster job dominance is the relative sizes of monster job’s processing times grow & shrink the point clusters shrink & grow. </dd>
<dd>This expanding characteristic of cluster implies there are relative minimum sizes of monster job’s processing time that result in complete/ horizontal & vertical sepearation of point clusters; (fundamental idea behind machine cell dominace) </dd>
<dd>Machine Cell Dominance, informally defined, the state of a prcessing time matrix in which a processing time cell is set to a minimum value that results in the complete sepeartion of the point clusters in associated plot of average lateness of antithetic job sequences pair, results in complete horizontal & vertical separation of point clusters. </dd> 
<dd>All other dominace; defined by characterisitic relationships among processing time; </dd>
<dd>MCD- defined by characterisitic relationships of the plot </dd>
<dd> (antithetic job) of performance measure(average lateness) </dd>
<dd>Associated with each solution in solution space. </dd>
<dd>Example of MCD- machine 1, job 1 </dd>
<dd>Clusters given unique colors to show horizontal & vertical bounds and fact do not cross their neighbor’s bounds. If monster cell value increased; then point clusters would start overlapping and no longer be completely separated. </dd>
<dd>Point cluster- in figure 4; are grouped by position of monster cell’s job in antithetic job sequences, used to calculate associated forward & reverse( average lateness) values of each point. </dd>
<dd>Algorithm to find MCD critical values; outlined next section; MCD; finding MCD critical value; exhaustive search may be conducted over large range of potential values until MCD value is found; this trail-and-error; “brute-force” process; processing time matrix may used to generate the mean lateness; </dd>
<dd>Cluster limits may be examined to verify whether overlap exists, process repeated until value at which no overlap occurs is found;  </dd>
<dd>Propose – search algorithm to find value of MCD given processing time matrix; </dd>
<dd>This method an elegant improvement over trail-and-error approach;  </dd>
<dd>Efficiency of algorithm to find MCD value is measured in terms of number of attempts it takes to find MCD value.  </dd>
<dd>Less attempts it takes to find MCD values better the efficiency. </dd>
<dd>More attempts it takes to find MCD values lesser the efficiency. </dd>
<dd>Outline binary search heurisitic to reduce number of attempts takes to find MCD value; </dd>
<dd>Line 1- Defines function (find_MCD_value)- finds MCD value of cell at postion (MCD_value_index) in processing time matrix (processing_time_matrix) </dd>
<dd>Line 2- Initialize lower limits of search range. </dd>
<dd>Line 3- Initialize upper limits of search range. </dd>
<dd>Line 4- Intialize the processing time matrix with initial upper bound of search range, </dd>
<dd>Line 5- Initialize(average lateness) points; using initial processing time matrix, </dd>
<dd>Line 6 to 10- Adjust lower & upper limits of search range. </dd>
<dd>Line 11 to 18- Uses binary search- like algorithm to find MCD values </dd>
<dd>Line 19- Returns MCD value </dd>
<dd>Efficiency of algorithm makes it possible to find multiple MCD values in same processing time matrix within reasonable amount of time.  </dd>
<dd>Special cases of MCD found by taking advantage of idea of finding new MCD value, while previous MCD values already present in processing time matrix. </dd>
<dd>Developed software package= lableled MLTPlot Generator; main function to generate plots of  </dd>
<ul>
<li>Makespan </li>
<li>Average Lateness </li>
<li>Average Tardiness- of antithetic job sequence pairs. </li>
</ul>
<dd>MLTPlot- Originally developed to generate characteristic plots associated with given processing time matrix; but evolved into custom research tool to help progress research efforts. </dd>
<dd>To generate plots user enters processing times into appropriate input boxes & clicks “Generate plots” button</dd>
<dd>To generate plots- user enters processing times into appropriate input boxes & clicks “Generate plots” button </dd>
<dd>Processing time and due date input boxes are arranged like typical processing time matrix with one column for each machine and due dates and one row for each job; number of machines and jobs are configurable. </dd>
<dd>After plots are generated; </dd>
<ul>
<li>They are individually accessible within associated tabs. </li>
</ul>
<dd>Program features controls that allow users to</dd>
<dd>Pan, zoom and save plots as image files</dd>
<dd>To find MCD value of given cell; user clears cell for which MCD value sought; then clicks after clicking Generate Plots button; MLTPlot Generate performs MCD value search algorithm, inputs found MCD value into cleared cell, then displays generated plots associated with new (processing time matrix) that contains MCD value. </dd>
<dd>Other features of MLTPlot include; </dd>
<ul>
<li>Randomly setting the input boxes with initial values. </li>
<li>Saving & restoring values of the input boxes. </li>
<li>Adjusting the way, the points are colored. </li>
<li>Annotating the points with their associated forward job sequences and generating Gantt Charts. </li>
</ul>
<dd>MLTPlot Generator; developed using Python programming language;along with PyQt, NumPy and matplotlib Python module. </dd>
<dd>PyQt module used to create graphical user inferace (GUI) </dd>
<dd>NumPy module used to help perform some calculation </dd>
<dd>Matplotlib used to generate the plots</dd>
<dd>Next chapter; special cases of MCD- were found using MLTPlot Generator</dd>
<dd>3 special cases of MCD and their variations; </dd>
<dd>Definitions of special cases are presented & backed by numerical examples. </dd>
<dd>Two MCD values on different Jobs & Machines</dd>
<dd>1st Special case of MCD results from finding two consecutive MCD values; first cell of MCD value may be any processing time cell; another cell; selected for which second MCD value is sought. Two variation of this special case arise depending on position of the two MCD in processing time matrix. </dd>
<dd>First Variation; arises when second MCD value found is associated with a machine that comes after the machine of the first MCD value. </dd>
<dd>M2 (4642)MCD 2nd comes after M1(746) MCD 1st </dd>
<dd>Size of M2 > M1</dd>
<dd>If figure 7; we show plot of (average lateness) of antithetic job sequence pairs that accompanies the (processing time matrix). </dd>
<dd>Five point clusters in this plot & each point cluster appears to have a horizontal & vertical subcluster, and these subcluster appear most in middle point cluster, and this point cluster appears to form a right angle. </dd>
<dd>Addition of color evidences the fact that there are actually six point clusters instead of five, point clusters in the middle of the plot are made of two subclusters; separated by some distance; </dd>
<dd>Point cluster grouping is conceptually same as grouping point cluster are grouped by position of job which contains the monster cell in antithetic job sequences. </dd>
<dd>Second variation; arises when second MCD value found is associated with machine that comes before the machine of the first MCD value. </dd>
<dd>M2 (836)MCD 1st come before M1 (3417)MCD 2nd </dd>
<dd>Figure 9</dd>
<dd>Plot of average lateness; of antithetic job sequence pairs; that accompanies the processing time matrix; </dd>
<dd>Slight differente between two variations leads to two radically different plots; </dd>
<dd>Point cluster in figure 9; are made of subclusters that form lines of negative slope. </dd>
<dd>Each point cluster has five subcluster; It has been observed these subclusters are grouped by position of the job of the first cell the MCD value was found for in the job sequence of each point. </dd>
<dd>Since the six main point clusters are grouped by the position of the job of the second cell the MCD value was found for in the job sequence of each point. </dd>
<dd>There are five positions in each job sequence; that are not constant; </dd>
<dd>These five variable positions in each job sequence are the cause of the five subcluster groupings; that appear within each main point cluster. </dd>
<dd>One MCD value repeated on different Jobs & Machine 2;second special case of MCD results; from finding the MCD value and repeating it in a new (processing time cell) What is the difference between processing time cell & processing time matrix</dd>
<dd>Value of the first cell the MCD value is to be found; for can be any processing time cell. The new cell must be a processing time of a different job and machine. </dd>
<dd>Multiple variations of this special case arise depending on the number of times the found MCD value is repeated in new processing time cells. </dd>
<dd>This section; we report the variations that arise when the first MCD value is repeated in one & two new processing time cells. </dd>
<dd>The first variation considered arises when MCd value is repeated in one new processing time cell; </dd>
<dd>Ex. MCD value was found for cell (1,1) & repeated n cell (2,2); </dd>
<dd>Next figure show plot of average lateness of antithetic job sequence pairs that accompanies the processing time matrix; show in (table 15) </dd>
<dd>The processing time matrix; is in a state between processing time matrices shown in Table 12 & 13. The processing time matrix shown in Table 15; can converge – (What us the meaning of converge? For processing time matrix) to processing time matrix shown in Table 12 or 13; if value of cell (2,2) </dd>
<dd>Difference between is cell is an individual cell; in the given matrix while matrix; in this thesis has 30 individual cells; Machine and Jobs combinations fact Table 15; is in an-in-between state appears to be reason why plot features seemingly to be horizontal, vertical & negative -slope lines. (Figure 10) </dd>
<dd>Table 15; potentially be example of first special case, first or second variation depending on values of cells fluctuate – (only one cell fluctuates; or does more than one cell fluctuate?) </dd>
<dd>Second Variation arises when MCD value is repeated in two other processing time cells associated with different jobs & machines. </dd>
<dd>Table 16; shows an example processing time matrix of this variation; MCD value found for cell (1,1) and repeated in cells (2,2) and (3,3). </dd>
<dd>Figure 11; furnish plot of average lateness of antithetic job sequence pairs that accompanies processing time matrix Table 16; Reasoning behind appearance of Fig. 11 conceptually same as the reasoning behind appearance of Fig. 10, there appear to be horizontal, vertical & negative-slope lines in Fig. 11 because processing time matrix shown in Table 16; is in an in-between state. Table 16; potentially an example of first special cases first or second variation. Since there is one more processing time cell contributing to in-between state of Table 16, there is one more way can potentially leave its in-between state; These potential in-between state exits superimpose on top of each other result in the appearance of more horizontal, vertical & negative-slope lines in figure 11 than there were in figure 10. </dd>
<dd>One MCD value in an MMD flowshop problem; </dd>
<dd>Third special case of MCD results from finding one MCD value in a monster machine flowshop problem. </dd>
<dd>Cell with MCD value must be on a different machine than the monster. Two variations of this special case arise depending on position of MCD value in processing time matrix; </dd>
<dd>First variation arises; when MCD value is associate with machine that comes before the monster machine. Table 17; shows the processing time matrix an example of this variation; In this example; MCD value was found for cell (1,1) & the monster machine is machine 3; </dd>
<dd>Fig. 12= we show plot of (average lateness) of antithetic job sequence pairs that accompanies (processing time matrix) in table 17; </dd>
<dd>In figure 13; we show the plot of average lateness of antithetic job sequence pairs that results from changing MCD value found in Table 17; from 3212 to 1500. – (Why was this change made; is this random or a particular reason to this change. Could not find mentioned past pages, why this was changed?) </dd>
<dd>Increasing the MCD value found in Table 17; eventually results in six point clusters in fugure 12; forming a negative-slope point cluster line similar to figure.3; </dd>
<dd>This implies that the appearance of figure 12;is the result of the right-angle point cluster shape shown in figure 13; converging to a negative-slope point cluster line as MCD value found in Table 17 increases. </dd>
</dd>More precisely, curvature in figure 12; is result of it being an in-between state between being either right-angle shape or negative-slope line; </dd>
  
</dl>
