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

<h2>Education</h2>

All three degrees are from the Faculty of Electrical Engineering, Czech Technical University in Prague.

<ul>
	<li>
		<b>Doctoral degree</b>, Ph.D. (Philosophiæ Doctor), 2018 &ndash; 2025<br>
		field of study: <b>Informatics / Artificial Intelligence and Biocybernetics</b><br>
		dissertation: <a href="https://dspace.cvut.cz/handle/10467/122044"><b>Dense Motion Estimation in a Monocular Video</b></a><br>
		supervisor: prof. Ing. Jiří Matas, Ph.D., co-supervisor: Mgr. Jan Šochman, Ph.D.
	</li><br>
	<li>
		<b>Master's degree</b>, Ing. (MSc equivalent), 2014 &ndash; 2017<br>
		programme: Open Informatics, specialization: <b>Computer Vision and Image Processing</b><br>
		thesis: <a href="https://dspace.cvut.cz/handle/10467/68536"><b>Object Scene Flow in Video Sequences</b></a><br>
		supervisor: Mgr. Jan Šochman, Ph.D.<br>
		awarded the Dean's Prize for an outstanding master thesis
	</li><br>
	<li>
		<b>Bachelor's degree</b>, Bc. (BSc equivalent), 2011 &ndash; 2014<br>
		programme: Cybernetics and Robotics, specialization: <b>Robotics</b><br>
		thesis: <b>Extraction of Features from Moving Garment</b><br>
		supervisor: Ing. Pavel Krsek, Ph.D.
	</li><br>
</ul>

<h2>Teaching</h2>

I have been teaching labs at the faculty since 2018, in Pattern Recognition and Machine Learning, Computer Vision Methods, and Digital Photography Processing. Details are under <a href="/teaching/">Teaching</a>, and the rest of the record is in my <a href="/cv/">CV</a>.

<h2>Contact</h2>

<ul>
	<li>Academic: <a href="mailto:{{ site.academic_email }}">{{ site.academic_email }}</a></li>
	<li>Personal: <a href="mailto:{{ site.general_email }}">{{ site.general_email }}</a></li>
	<li>Code: <a href="https://github.com/{{ site.github_username }}">github.com/{{ site.github_username }}</a></li>
</ul>
