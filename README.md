# cs5335-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [CS5335 Homework 6 Solved](https://www.ankitcodinghub.com/product/cs5335-please-remember-the-following-policies-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109468&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS5335 Homework 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
• You are welcome to discuss the programming questions (but not the written questions) with other students in the class. However, you must understand and write all code yourself. Also, you must list all students (if any) with whom you discussed your solutions to the programming questions.

We recommend that you first familiarize yourself with MATLAB and the Robotics Toolbox by following these steps: • Install MATLAB R2020b. Visit the following article for Northeastern-specific instructions: https://service.northeastern.edu/tech?id=kb_article&amp;sys_id=68c93fd6dbf37bc0c5575e38dc961918

– If you have an older version of MATLAB, we recommend installing the R2019b version to ensure better support from the teaching staff.

– If you have sufficient space on your computer, we recommend installing all of the toolboxes as well. At a minimum, you should install the Robotics System Toolbox, the toolboxes listed on the following page, and the Optimization and Symbolic Math toolboxes.

https://www.mathworks.com/support/requirements/robotics-system-toolbox.html You can always choose to install additional toolboxes later if you are uncertain.

• If you need an introduction or refresher on MATLAB, see the “MATLAB Resources” section of the “Resources” page on Piazza for slides and practice questions (with answers) from a short but intensive introductory course. • Install Peter Corke’s Robotics Toolbox (version 10.4). This is different from the official MATLAB Robotics System Toolbox installed in the previous step. http://petercorke.com/wordpress/toolboxes/robotics-toolbox

– The simplest way to install this is from the .mltbx file: http://petercorke.com/wordpress/?ddownload=778

To install, open the downloaded file within MATLAB. Then run rtbdemo to check that it is working.

– Version 10.x of the toolbox is the only version compatible with the second edition of the Robotics, Vision and Control textbook, which is the version we are using.

• You will inevitably encounter errors. Here are some debugging tips:

– The MATLAB documentation is very extensive and available both online and offline. To look up a function within the interactive session, type help &lt;function&gt; (e.g., help SE3). The description often contains links to further documentation and related functions.

– Use disp liberally to print out variables and other debugging information.

– If you are used to coding in MATLAB purely with matrices, note that the Robotics Toolbox defines many entities as classes and objects (e.g., SE3, SerialLink, etc.). Know the difference, and do not fret when you encounter type conversion issues – fixing them is similar to debugging dimension mismatch issues.

– Tables 2.1 and 2.2 in the textbook (data type conversions) are extremely useful.

Configuration Space and Motion Planning

C0. 2 points. Consider the diagram above. Two square robots A and B operate in a 2-D workspace. The two robots do not rotate, and each moves on a fixed track, so that its center remains on the solid gray line shown in the figure. The robots must move so as not to collide with each other. The diagram is to scale, with each tick denoting a distance of one unit.

(a) Even though there are two robots both moving in a 2-D workspace, we can still use a 2-D configuration space to represent the above system. Specify what the axes of our configuration space correspond to in the workspace, what the axis limits are, and what configuration the above diagram depicts.

(b) Draw the configuration space. For each configuration-space obstacle, label the coordinates of the vertices, and sketch the workspace configuration corresponding to each. Since the workspace is symmetric, only makes sketches for the left side of the workspace.

Download the starter code from Piazza (hw2.zip). In this file, you will find:

• hw2 cspace.m: Main function. Call hw2 cspace(&lt;questionNum&gt;) with an appropriate question number (1–7) to run the code for that question. Do not modify this file! (Feel free to actually make changes, but check that your code runs with an unmodified copy of hw2 cspace.m.)

• C1.m – C7.m: Code stubs that you will have to fill in for the respective questions.

• q2poly.m: Code stub that you will have to fill in, helper function for various questions.

• plot obstacles.m: Helper function to draw workspace obstacles defined in hw2 cspace.m.

C1. 2 points. Plot the robot in the workspace, as shown above. The demonstration code in C1.m shows how to plot the robot at the zero configuration (q = (0,0)). You will need to make appropriate transformations to both links’ polygons and their pivot points (frame origins). Consider filling in q2poly.m first, which is a useful helper function for C1 and future questions. If you provide qstart and qgoal as input, you should get the figures above.

Useful functions: Read the documentation for polyshape, a MATLAB class for defining 2-D polygons.

C2. 2 points. Convert the problem into configuration space by discretizing the configuration space, and checking for collisions at each discrete grid point. Using the specified grid for each axis given in q grid, compute whether the configuration at each point is in collision or not, by intersecting the links’ 2-D polygon with the obstacles’ 2-D polygons. Assume that the robot is never in collision with itself. The resulting matrix should look similar to the configuration space diagram shown on the slide. Useful functions: intersect

cspace = hw2 cspace(2); hw2 cspace(3, cspace);

C3: Distance transform from goal configuration. C4: Path from start to goal.

C3. 2 points. Given a specified goal configuration and the configuration-space grid from C2, compute the distance transform from the grid point nearest to the goal.

C4. 2 points. Using the distance transform from C3, find a path from the specified start configuration’s closest grid point to the goal’s grid point. Descend the distance transform in a greedy fashion, breaking ties with any strategy you wish. Diagonal neighbors are allowed.

C5. 1 point. Convert the path in grid point indices, found in C4, into a path in configurations. Remember to include the actual start and goal configurations. This should trigger a visualization similar to the one shown above.

C7. 1 point. Most of the collisions above were caused by planning a path that was too close to obstacles. One simple conservative way to avoid such collisions is to pad the obstacles by a small buffer zone. Pad the obstacles in configuration space by one grid cell (including diagonal neighbors), and verify that the resulting trajectory does not contain any swept-volume collisions.
