---
layout: page
title: About
permalink: /about/
---

{% include image.html url="/images/profile.jpg" width=300 align="right" %}

I am a computer vision researcher at the <a href="https://cmp.felk.cvut.cz/"><b>Center for Machine Perception (CMP)</b></a>, Czech Technical University in Prague, in the <a href="https://vrg.fel.cvut.cz/"><b>Visual Recognition Group (VRG)</b></a> at the Faculty of Electrical Engineering. I finished my Ph.D. there in 2025, after a bachelor's degree in robotics and a master's in computer vision at the same faculty.

<h2>Research interests</h2>

Most of my work so far has been about <b>motion</b>: what moves in a video, and where every pixel goes. That covers optical flow with explicit occlusion reasoning, discovery and segmentation of independently moving objects seen from a moving camera, and long-term dense tracking, where correspondences have to survive hundreds of frames rather than two. My dissertation, <a href="https://dspace.cvut.cz/handle/10467/122044">Dense Motion Estimation in a Monocular Video</a>, collects that line of work.

More recently I have been working on <b>detection, classification and fine-grained recognition</b>: object detection and classification in large video archives with fast incremental learning of new classes, open-set recognition where unknown classes appear at inference time, and compact image descriptors distilled from frozen vision-language models.

Much of this work was done in a long collaboration between CTU and <b>Toyota Motor Europe</b>, which ran from 2015 to 2025 and produced most of my papers and four patent filings.

<h2>Background</h2>

Bc. in Cybernetics and Robotics (2014), Ing. in Open Informatics with a specialization in Computer Vision and Image Processing (2017, awarded the Dean's Prize), and Ph.D. in Informatics / Artificial Intelligence and Biocybernetics (2025), all at the Faculty of Electrical Engineering, CTU in Prague. The full detail is on the <a href="/">homepage</a> and in my <a href="/cv/">CV</a>, the work itself under <a href="/publications/">Publications</a> and <a href="/experience/">Experience</a>.

I have also been teaching labs at the faculty since 2018, in Pattern Recognition and Machine Learning, Computer Vision Methods, and Digital Photography Processing. Details are under <a href="/teaching/">Teaching</a>.

<h2>Contact</h2>

<ul>
	<li>Academic: <a href="mailto:{{ site.academic_email }}">{{ site.academic_email }}</a></li>
	<li>Personal: <a href="mailto:{{ site.general_email }}">{{ site.general_email }}</a></li>
	<li>Code: <a href="https://github.com/{{ site.github_username }}">github.com/{{ site.github_username }}</a></li>
</ul>
