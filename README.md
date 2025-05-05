# cse512-project-phase2-solved
**TO GET THIS SOLUTION VISIT:** [CSE512 Project-Phase2 Solved](https://www.ankitcodinghub.com/product/cse512-project-phase2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99754&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE512 Project-Phase2 Solved&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

In Project Phase 2, you need to write two User Defined Functions ST_Contains and ST_Within in SparkSQL and use them to do four spatial queries:

<ul>
<li>● &nbsp;Range query: Use ST_Contains. Given a query rectangle R and a set of points P, find all the points within R.</li>
<li>● &nbsp;Range join query: Use ST_Contains. Given a set of Rectangles R and a set of Points S, find all (Point, Rectangle) pairs such that the point is within the rectangle.</li>
<li>● &nbsp;Distance query: Use ST_Within. Given a point location P and distance D in km, find all points that lie within a distance D from P</li>
<li>● &nbsp;Distance join query: Use ST_Within. Given a set of Points S1 and a set of Points S2 and a distance D in km, find all (s1, s2) pairs such that s1 is within a distance D from s2 (i.e., s1 belongs to S1 and s2 belongs to S2).
A Scala SparkSQL code template is given. You must start from the template. The main code is in “SparkSQLExample.scala”

The detailed requirements are as follows:

1. ST_Contains

Input: pointString:String, queryRectangle:String Output: Boolean (true or false)

Definition: You first need to parse the pointString (e.g., “-88.331492,32.324142”) and queryRectangle (e.g., “-155.940114,19.081331,-155.618917,19.5307”) to a format that you are comfortable with. Then check whether the queryRectangle fully contains the point. Consider on-boundary point.

2. ST_Within

Input: pointString1:String, pointString2:String, distance:Double Output: Boolean (true or false)

Definition: You first need to parse the pointString1 (e.g., “-88.331492,32.324142”) and pointString2 (e.g., “-88.331492,32.324142”) to a format that you are comfortable with. Then check whether the two points are within the given distance. Consider on-boundary point. To simplify the problem, please assume all coordinates are on a planar space and calculate their Euclidean distance.

3. Use Your UDF in SparkSQL
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The code template has loaded the original data (point data, arealm.csv, and rectangle data, zcta510.csv) into DataFrame using tsv format. You don’t need to worry about the loading phase.

Range query:

Range join query:

Distance query:

Distance join query:

4. Run your code on Apache Spark using “spark-submit”

If you are using the Scala template, note that:

1. You only have to replace the logic (currently is “true”) in all User Defined Function. 2. The main function in this template takes 21 parameters as follows:

<ul>
<li>❍ &nbsp;Output file path: /Users/ubuntu/Downloads/output.csv</li>
<li>❍ &nbsp;Range query data file path, query window: /Users/ubuntu/Downloads/arealm.csv
<pre>    -155.940114,19.081331,-155.618917,19.5307
</pre>
</li>
<li>❍ &nbsp;Range join query data file path, range join query window data file path: /Users/ubuntu/Downloads/arealm.csv /Users/ubuntu/Downloads/zcta510.csv</li>
<li>❍ &nbsp;Distance query data file path, query point, distance: /Users/ubuntu/Downloads/arealm.csv -88.331492,32.324142 10</li>
<li>❍ &nbsp;Distance join query data A file path, distance join query data B file path, distance: /Users/ubuntu/Downloads/arealm.csv /Users/ubuntu/Downloads/arealm.csv 10</li>
<li>❍ &nbsp;Range query data file path, query window: /Users/ubuntu/Downloads/arealm.csv -155.940114,19.081331,-155.618917,19.5307</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>select *
from point
where ST_Contains(point._c0,'-155.940114,19.081331,-155.618917,19.5307')
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>select *
from rectangle,point
where ST_Contains(rectangle._c0,point._c0)
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>select *
from point
where ST_Within(point._c0,'-88.331492,32.324142',10)
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>select *
from point p1, point p2
where ST_Within(p1._c0, p2._c0, 10)
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>❍ &nbsp;Range join query data file path, range join query window data file path: /Users/ubuntu/Downloads/arealm.csv /Users/ubuntu/Downloads/zcta510.csv</li>
<li>❍ &nbsp;Distance query data file path, query point, distance: /Users/ubuntu/Downloads/arealm.csv -88.331492,32.324142 10</li>
<li>❍ &nbsp;Distance join query data A file path, distance join query data B file path, distance: /Users/ubuntu/Downloads/arealm.csv /Users/ubuntu/Downloads/arealm.csv 10</li>
</ul>
<ol start="3">
<li>Two example datasets are put in “src/resources” folder. arealm is a point dataset and zcta510 is a rectangle dataset. You can can use them to test your code but eventually you must run your code on NYC taxi trip dataset. Our auto-grading system will also run your code on NYC taxi trip data.</li>
<li>Here is an example that tells you how to submit your jar using “spark-submit”</li>
</ol>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>./bin/spark-submit
~/GitHub/CSE512-Project-Phase3-Template/target/scala-2.11/CSE512-Project-Phase2-Tem
plate-assembly-0.1.0.jar ~/Downloads/output.csv ~/Downloads/arealm_small.csv
-155.940114,19.081331,-155.618917,19.5307 ~/Downloads/arealm_small.csv
~/Downloads/zcta510_small.csv ~/Downloads/arealm_small.csv -88.331492,32.324142 10
~/Downloads/arealm_small.csv ~/Downloads/arealm_small.csv 10
~/Downloads/arealm_small.csv -155.940114,19.081331,-155.618917,19.5307
~/Downloads/arealm_small.csv ~/Downloads/zcta510_small.csv
~/Downloads/arealm_small.csv -88.331492,32.324142 10 ~/Downloads/arealm_small.csv
~/Downloads/arealm_small.csv 10
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
5. Vocareum (submission site)

In Vocareum, all groups share a single but powerful cluster.

Vocareum is for submission only. After uploading your jar, directly click “submit”.

Do not test your code here. You have limited submission times. Every submission impacts your grade!

Website

<blockquote class="wp-embedded-content" data-secret="LfsQ2rAxy9"><a href="https://www.vocareum.com/">Home – 2020</a>
</blockquote>
<iframe class="wp-embedded-content lazyload" sandbox="allow-scripts" security="restricted" style="position: absolute; clip: rect(1px, 1px, 1px, 1px);" title="“Home – 2020” — Vocareum" data-src="https://www.vocareum.com/embed/#?secret=Q7ubIjGtjn#?secret=LfsQ2rAxy9" data-secret="LfsQ2rAxy9" width="600" height="338" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-load-mode="1"></iframe>

Submission

<ol>
<li>Submit your code on Vocareum website in order to get your grade.</li>
<li>Submit your project source code onto Blackboard in a compress zip file of
“cse512-phase2-GROUPNAME” for plagiarism detection. Note that: you need to make sure your code can compile and package by entering sbt assembly. We will run the compiled package on our cluster directly using “spark-submit”.
</li>
<li>If your code cannot compile and package, you will not receive any points.</li>
</ol>
How to debug your code in IDE

If you are using the Scala template

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
1. Use IntelliJ Idea with Scala plug-in or any other Scala IDE.

2. Replace the logic of User Defined Functions ST_Contains and ST_Within in SparkSQLExample.scala.

3. Append .master(“local[*]”) after .config(“spark.some.config.option”, “some-value”) to tell IDE the master IP is localhost.

4. In some cases, you may need to go to “build.sbt” file and change % “provided” to % “compile” in order to debug your code in IDE

5. Run your code in IDE

&nbsp;

</div>
</div>
</div>
