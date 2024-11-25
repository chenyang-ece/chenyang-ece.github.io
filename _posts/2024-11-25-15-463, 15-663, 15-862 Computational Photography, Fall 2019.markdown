---
layout:     post
title:      电影记录 
subtitle:   
date:       2024-11-25
author:     Chen
header-img: img/facebook.jpg
catalog: false
tags:
    - 学习
    - 图像处理
    - 计算摄影
---

<!DOCTYPE html>
<!-- saved from url=(0052)http://graphics.cs.cmu.edu/courses/15-463/2019_fall/ -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<link rel="icon" href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/index_files/favicon.png" type="image/png">

	<title>15-463, 15-663, 15-862 Computational Photography, Fall 2019</title>
	<link rel="stylesheet" type="text/css" href="./15-463, 15-663, 15-862 Computational Photography, Fall 2019_files/style.css">
</head>

<body>

	<table style="width: 100%;">
		<tbody><tr>
			<td style="width: 90%"><div class="title">15-463, 15-663, 15-862<br> Computational Photography, Fall 2019</div></td>
		<td style="width: 10%; text-align:right;"><img style="width: auto;" src="./15-463, 15-663, 15-862 Computational Photography, Fall 2019_files/scslogo.gif"></td>
		</tr>
	</tbody></table>
	
	<table style="width: 100%; border-bottom: 1px solid #c0c0c0;">
		<tbody><tr>
			<td>Time:</td>
			<td>Mondays, Wednesdays 12:00 PM - 1:20 PM</td>
			</tr>
			<tr>
			<td>Location:</td>
			<td>GHC 5222</td>
			</tr>
			<tr>
			<td>Instructor:</td>
			<td><a href="http://www.cs.cmu.edu/%7Eigkioule/">Ioannis (Yannis) Gkioulekas</a></td>
			</tr>
			<tr>
			<td>Teaching Assistant:</td>
			<td><a href="http://www.cs.cmu.edu/%7Etzhi/">Tiancheng Zhi</a></td>
			</tr>
	</tbody></table>

	<div class="section">
		<div class="section-title">Course Description</div>
		<p>Computational photography is the convergence of computer graphics, computer vision, optics and imaging. Its role is to overcome the limitations of traditional cameras, by combining imaging and computation to enable new and enhanced ways of capturing, representing, and interacting with the physical world.</p>

		<p>This advanced undergraduate course provides a comprehensive overview of the state of the art in computational photography. At the start of the course, we will study modern image processing pipelines, including those encountered on mobile phone and DSLR cameras, and advanced image and video editing algorithms. Then we will continue to learn about the physical and computational aspects of tasks such as 3D scanning, coded photography, lightfield imaging, time-of-flight imaging, VR/AR displays, and computational light transport. Near the end of the course, we will discuss active research topics, such as creating cameras that capture video at the speed of light, cameras that look around walls, or cameras that can see below skin.</p>

		<p>The course has a strong hands-on component, in the form of seven homework assignments and a final project. In the homework assignments, students will have the opportunity to implement many of the techniques covered in the class, by both acquiring their own images of indoor and outdoor scenes and developing the computational tools needed to extract information from them. Example homeworks include building end-to-end HDR imaging pipelines and structured light scanners. For their final projects, students will have the choice to use modern sensors and other optical instrumentation provided by the instructors (lightfield cameras, time-of-flight sensors, projectors, laser sources, and so on).</p>

		<p><strong>Cross-listing:</strong> This class is cross-listed as 15-463 (for undergraduate students), 15-663 (for Master's students), and 15-862 (for PhD students). Please make sure to register for the section of the class that matches your current enrollment status.</p>
	</div>
	<div class="section">
		<div class="section-title">Prerequisites</div>
		<p>This course requires familarity with linear algebra, calculus, programming, and doing computations with images. In particular, either of the following courses can serve as proof that you satisfy these prerequisites:</p>
		<ul>
			<li>16-385 Computer Vision, OR</li>
			<li>16-720 Computer Vision, OR</li>
			<li>15-462 Computer Graphics, OR</li>
			<li>18-793 Image and Video Processing.</li>
		</ul>
		<p>If you have not taken any of the above courses but want to enroll, please contact the instructor   exceptions will be made on a case-by-case basis. The course does not require prior experience with photography or imaging.</p>
	</div>

	<div class="section">
		<div class="section-title">Textbook</div>
		<p>Readings will be assigned primarily from relevant papers. Readings will be posted at the last slide of each lecture.</p>

		<p>Additionally readings may be assigned from the following textbooks, which can also be useful references in general. All of them are available online from the CMU library:</p>
		<ul>
			<li><i><a href="http://szeliski.org/Book/">Computer Vision: Algorithms and Applications</a></i>, by Richard Szeliski.</li>
			<li><i>Multiple View Geometry in Computer Vision,</i> by Richard Hartley and Andrew Zisserman.</li>
			<li><i>Computer Vision: A Modern Approach,</i> by David Forsyth and Jean Ponce.</li>
			<li><i>Foundations of 3D Computer Graphics,</i> by Steven Gortler.</li>
			<li><i>Digital Image Processing,</i> by Rafael Gonzalez and Richard Woods.</li>
			<li><i>Photography,</i> by Barbara London and John Upton.</li>
		</ul>
	</div>
	
	<div class="section">
		<div class="section-title">Evaluation</div>
		<p>Your final grade will be made up of:</p>
		<ul>
			<li>Six two-week homework assignments (60%).</li>
			<li>Optional seventh homework assignment (10%).</li>
			<li>Final project (35%).</li>
			<li>Class participation (5%).</li>
		</ul>
		<p><strong>Homework assignments:</strong> All homework assignments will have a programming component and a photography component, where students will use a DSLR camera to capture and process their own images. The programming component of all assignments be done in Matlab. The first assignment will serve as a short tutorial in Matlab and DSLR cameras. We have collected a few useful Matlab resources <a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/matlab.html">here</a>.</p>
		<p><strong>Bonus homework assignment:</strong> There will be a seventh <i>optional</i> homework assignment that can be used to make up for lost credit.</p>
		<p><strong>Late days:</strong> For the homework assignments, students will be allowed a total of five free late days. Any additional late days will each incur a 10% penalty.</p>
		<p><strong>Collaboration policy:</strong> Students are encouraged to work in groups but each student must submit their own work. This includes: writing your own code, building your own imaging setups, taking your own photographs, and producing your own writeup. If you work as a group, include the names of your collaborators in your writeup. You absolutely should not share or copy code. Additionally, you should not use any external code unless explicitly permitted. Plagiarism is strongly prohibited and will lead to failure of this course.</p>
		<p><strong>Submitting homeworks:</strong> We will use <strong><a href="https://canvas.cmu.edu/courses/12162">Canvas</a></strong> for submitting and grading homeworks.</p>
		<p><strong>Final project:</strong> Details about the final project are available <a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/final_project.html">here</a>.
		</p><p><strong>15-663, 15-862:</strong> Students taking 15-663 or 15-862 will be required to do a more substantial final project, as well as submit a longer paper describing their project.</p>
	</div>
	
	<div class="section">
		<div class="section-title">Cameras</div>
		<p>Students are encouraged to obtain a digital camera for use in the course    any digital camera with manual controls should work. However, this is not a requirement, and about 20 cameras will be provided by the instructors for students who do not have one.</p>
	</div>
	
	<div class="section">
		<div class="section-title">Email, Office Hours, and Discussion</div>
		<p><strong>Email:</strong> Please use [15463] in the title when emailing the teaching staff!</p>
		<p><strong>Office hours:</strong> Teaching staff have regular office hours at the following times.</p>
		<ul>
			<li>Tiancheng: Tuesdays 5:00 - 7:00 PM, Smith Hall graphics lounge.</li>
			<li>Yannis: Fridays 5:00 - 7:00 PM, Smith Hall graphics lounge.</li>
		</ul>
		<p>Feel free to email us about scheduling additional office hours.</p>
		<p><strong>Discussion:</strong> We will use <strong><a href="https://piazza.com/class/jzoctlm269oe0">Piazza</a></strong> for class discussion and announcements.</p>
	</div>

	<div class="section">
		<div class="section-title">Interested in research?</div>
		<p>We are actively looking for students at all levels (undergraduates, MS, PhD) to help in projects on various aspects of computational photography, imaging, rendering, and graphics in general. If you are interested, please send Yannis an email (or talk to him in person in class).</p>
		<p>You should also take a look at the <strong><a href="http://imaging.cs.cmu.edu/">imaging group website</a></strong>, to find more information about related projects active here at CMU.</p>

		<p>Finally, you are welcome to attend the imaging group meetings, <strong>every Friday, 3:00 - 4:00 PM, at WEH 5421</strong>. If you want to receive announcements about the group meetings, as well as other emails regarding photography and imaging research, ask Yannis to add you to the imaging group's mailing list.</p>
	</div>

	<div class="section">
	<div class="section-title">(Tentative) Syllabus</div>
	<p>Slides will be updated on this website after each lecture.</p>
	<table class="sb-tb">
	<tbody>
		<tr><th>Date</th><th>Topics</th><th>Slides</th><th>Assignments</th></tr>
		<tr><td>M, Aug 26</td><td>Introduction</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture1.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Aug 28</td><td>Digital photography pipeline</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture2.pdf">pdf</a></td><td></td></tr>
		<tr><td>F, Aug 30</td><td></td><td></td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn1.zip">HW1 out</a></td></tr>
		<tr><td>M, Sep 2</td><td><strong>No class (Labor day)</strong></td><td></td><td></td></tr>
		<tr><td>W, Sep 4</td><td>Pinholes and lenses</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture3.pdf">pdf</a></td><td></td></tr>
		<tr><td>M, Sep 9</td><td>Photographic optics and aberrations</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture4.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Sep 11</td><td>Exposure and high-dynamic-range imaging</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture5.pdf">pdf</a></td><td></td></tr>
		<tr><td>F, Sep 13</td><td></td><td></td><td>HW1 due, <a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn2.zip">HW2 out</a></td></tr>
		<tr><td>M, Sep 16</td><td>Noise modeling and calibration</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture6.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Sep 18</td><td>Color</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture7.pdf">pdf</a></td><td></td></tr>
		<tr><td>M, Sep 23</td><td>Bilateral and edge-aware filtering</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture8.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Sep 25</td><td>Gradient-domain image processing</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture9.pdf">pdf</a></td><td></td></tr>
		<tr><td>F, Sep 27</td><td></td><td></td><td>HW2 due, <a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn3.zip">HW3 out</a></td></tr>
		<tr><td>M, Sep 30</td><td>Focal stacks and lighfields</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture10.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Oct 2</td><td>Focal stacks and lightfields (continued)</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture10.pdf">pdf</a></td><td></td></tr>
		<tr><td>M, Oct 7</td><td>Deconvoluion</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture12.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Oct 9</td><td>Coded photography</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture13.pdf">pdf</a></td><td></td></tr>
		<tr><td>F, Oct 11</td><td></td><td></td><td>HW3 due, <a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn4.zip">HW4 out</a></td></tr>
		<tr><td>M, Oct 14</td><td>Geometric camera models and calibration</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture14.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Oct 16</td><td><strong>No class</strong></td><td></td><td></td></tr>
		<tr><td>M, Oct 21</td><td>Radiometry and reflectance</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture15.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Oct 23</td><td>Photometric stereo</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture16.pdf">pdf</a></td><td></td></tr>
		<tr><td>F, Oct 25</td><td></td><td></td><td>HW4 due</td></tr>
		<tr><td>M, Oct 28</td><td>Two-view geometry</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture17.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Oct 30</td><td>Stereo and structured light</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture18.pdf">pdf</a></td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn5.zip">HW5 out</a></td></tr>
		<tr><td>M, Nov 4</td><td>Global illumination</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture19.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Nov 6</td><td><strong>Guest lecture: Aswin Sankaranarayanan</strong></td><td></td><td></td></tr>
		<tr><td>M, Nov 11</td><td>Computational light transport</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture21.pdf">pdf</a></td><td></td></tr>
		<tr><td>W, Nov 13</td><td>Time-of-flight imaging</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture22.pdf">pdf</a></td><td>HW5 due</td></tr>
		<tr><td>M, Nov 18</td><td>Fourier Optics</td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/lectures/lecture23.pdf">pdf</a></td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn6.zip">HW6 out</a></td></tr>
		<tr><td>W, Nov 20</td><td>Non-line-of-sight imaging</td><td></td><td></td></tr>
		<tr><td>M, Nov 25</td><td>Special topics</td><td></td><td></td></tr>
		<tr><td>W, Nov 27</td><td><strong>No class (Thanksgiving)</strong></td><td></td><td></td></tr>
		<tr><td>M, Dec 2</td><td>Special topics</td><td></td><td><a href="http://graphics.cs.cmu.edu/courses/15-463/2019_fall/assignments/assgn7.zip">HW7 out</a></td></tr>
		<tr><td>W, Dec 4</td><td>Special topics</td><td></td><td></td></tr>
		<tr><td>F, Dec 6</td><td></td><td></td><td>HW6 due, HW7 due</td></tr>
	</tbody>
	</table>
	</div>

	<div class="section">
		<div class="section-title">Previous Course Offerings</div>
		<ul>
			<li><a href="http://graphics.cs.cmu.edu/courses/15-463/2018_fall/">15-463 (15-663, 15-862), Fall 2018</a> (taught by Ioannis Gkioulekas)</li>
			<li><a href="http://graphics.cs.cmu.edu/courses/15-463/2017_fall/">15-463 (15-663, 15-862), Fall 2017</a> (taught by Ioannis Gkioulekas)</li>
			<li><a href="http://graphics.cs.cmu.edu/courses/15-463/2015_fall/">15-463 (15-663, 15-862), Fall 2015</a> (taught by Kris Kitani)</li>
		</ul>
	</div>

	<div class="section">
		<div class="section-title">Similar Courses at CMU and Elsewhere</div>
		<ul>
			<li><a href="http://stanford.edu/class/ee367/">Computational Imaging and Display</a> (Gordon Wetzstein, Stanford)</li>
			<li><a href="https://courses.engr.illinois.edu/cs445/fa2015/">Computational Photography</a> (Derek Hoiem, UIUC)</li>
			<li><a href="http://cs.brown.edu/courses/csci1290/">Computational Photography</a> (James Hays, Brown)</li>
			<li><a href="http://web.media.mit.edu/~raskar/photo/">Computational Photography</a> (Ramesh Raskar and Jack Tumblin, SIGGRAPH course)</li>
			<li><a href="http://stellar.mit.edu/S/course/6/sp12/6.815/index.html">Digital and Computational Photography</a> (Fredo Durand, MIT)</li>
			<li><a href="http://users.eecs.northwestern.edu/~ollie/eecs395/eecs395.htm">Introduction to Computational Photography</a> (Oliver Cossairt, Northwestern)</li>
			<li><a href="http://www.cs.toronto.edu/~kyros/courses/320/">Introduction to Visual Computing</a> (Kyros Kutulakos, University of Toronto)</li>
			<li><a href="http://graphics.cs.cmu.edu/courses/15769/fall2016/">Visual Computing Systems</a> (Kayvon Fatahalian, CMU)</li>
		</ul>
	</div>

	<div class="section">
		<div class="section-title">Special Thanks</div>
	<p>These lecture notes have been pieced together from many different people and places. Special thanks TBD.</p>
	</div>

	<div class="footer">
		<p>Website adapted from <a href="http://www.cs.cmu.edu/~16385/">16-385, Spring 2017</a>.</p>
	</div>

</body></html>









