---
title: "How to Pass the Splunk Core Certified User Certification in 2 Days"
description: "Last October, or Cyber Security Awareness month, I had <a rel=\"noreferrer noopener\" href=\"https://santoshganjur.wordpress.com/blog/thoughts-about-the-giac-se"
pubDate: 2021-01-24T05:09:50.000Z
categories: ["Cyber Security", "Learning", "Trainings and Certifications"]
tags: []
author: "santoshgs"
draft: false
updatedDate: 2025-11-11T20:44:07.000Z
wpId: 608
---
<p>Last October, or Cyber Security Awareness month, I had <a rel="noreferrer noopener" href="https://santoshganjur.wordpress.com/blog/thoughts-about-the-giac-security-essentials-gsec-and-the-sans-sec401-security-essentials-bootcamp/" target="_blank">just completed acquiring two GIAC certifications</a> - the GSEC and GCIH. I was in a non-technical role, and trying hard to move back into IT. Wanting to continue in the high from the GIAC exams, and encouraged by our mentor Nik Alleyne, I along with a few others from the Ryerson University cohort started on a journey to learn more about the tools we had come across recently.  Our mentor had created a learning path for us - first the SIEMs, and then firewalls. With this, we would be able to understand how to analyze logs, the tools used for the same (SIEMs), and packet analysis. </p>



<figure class="wp-block-image size-large"><img src="https://santoshganjur.wordpress.com/wp-content/uploads/sites/2/2021/01/image-1.png" alt="" class="wp-image-610"><figcaption>Verify my <a href="https://www.youracclaim.com/badges/5b0f7d75-fed5-467c-a3f5-87cf3e8f5fdb">Splunk Core Certified User on Acclaim (youracclaim.com)</a></figcaption></figure>



<p>Learning the SIEMs required for a Cyber Security Analyst role seemed quite easy on paper - start by creating a couple of virtual machines (VM), setup a SIEM such as QRadar or Splunk on one of them, and forward all of the logs from the VMs to the SIEM. You're basically setting up a virtual lab at home on your personal computer. Fair enough. Now, this post is about the Splunk Core Certified User, so I'm going to come back and write another post on setting up a virtual lab. Just need to tidy up the notes I have. For now, onward toward the Splunk Core certification then. </p>



<p>I chose to study Splunk after a battle setting up QRadar on my laptop. The darn brought my 12 gig laptop to its knees. I was almost going to buy an actual physical server and host QRadar on that, but decided to go with Splunk given it's ease of setup, configuration and use. I setup Splunk on a Kali box, and bought a license to VMware Workstation Pro 16 for ease of back up and restore if something went wrong. I then signed myself up for the <a href="https://www.splunk.com/en_us/training/courses/splunk-fundamentals-1.html" target="_blank" rel="noreferrer noopener">Splunk Fundamentals 1 course </a>on the official website and started studying. It's very nicely designed and laid out, with the man in the videos wearing a different t-shirt with a witty Splunk caption for each module (not kidding). So why not.</p>



<p>Fast forward a few weeks to mid-November, I had never really got around to finishing the course as I started a few interviews, coffee chats and otherwise 40 hours of work. I had two days left for my exam and I had no idea how I was going to get through it. To make matters worse, the course is only valid for 30 days and my access had expired. Yay!</p>



<h2>How did I do it?</h2>



<ol><li><strong>Certification Blueprint -</strong> This should be step-0 really. You cannot start studying without knowing what topic is on the exam. Download and go through the <a rel="noreferrer noopener" href="https://www.splunk.com/pdfs/training/Splunk-Test-Blueprint-User-v.1.1.pdf" target="_blank">blueprint </a>carefully. Understand the weightage given to each topic. This is going to give you the clue needed to excel in step-3 as well.</li><li><strong>Course work - </strong>First Friday night after work, I signed up for another account on Splunk and ran through the modules over an entire day. I completely skipped the lab portion. The license to Splunk on my VM had expired and I was too tensed to start over with it.</li><li><strong>Quizzes - </strong>I went through all the quizzes in the Splunk course twice. This is a great way of understanding the topics and seeing where you're falling behind. Some of the questions are not multiple choice requiring you to fill in the exact answer. This was extremely helpful as it made me understand those topics with high weightage towards the certification really well - and most of these were fundamental to learning Splunk. </li><li><strong>YouTube - </strong>For the doubts I had, I went into YouTube and searched for videos about those topics. <a rel="noreferrer noopener" href="https://www.youtube.com/channel/UCjwOFZzLPnji1EstaVyyvAw" target="_blank">Splunk How-to</a> guides were quite handy. From these, I understood the general working of Splunk, how to search for events, use expressions to refine searches, and control a search job.</li><li><strong>Flashcards - </strong>I had previously found that a helpful bloke had put together <a rel="noreferrer noopener" href="https://quizlet.com/298321919/splunk-core-certified-user-splunk-fundamentals-1-flash-cards/" target="_blank">flashcards for Splunk Fundamentals 1</a>. Spent the morning of the exam going through them. The Quizlet website gamifies the experience with something called "gravity". This was a nice light hearted approach towards learning, but quickly turned into getting on the top of the leaderboard. I managed to finish it in 32s before I gave up, let me know yours!</li></ol>



<p></p>



<p>That's it. I stopped an hour and a half before the exam, setup my desk and removed all electronics from the room (not taking any chances with these online proctored exams), went in and PASSED!</p>



<p>In all honesty, it's a very simple exam structured around understanding what Splunk can do, learning to search Splunk and filtering the results as needed. In my opinion, it's meant to whet your appetite for diving deeper into Splunk, which I think it did for me but not professionally.</p>



<p>What would I do differently - put in more time to studying, of course. Without hands-on experience, this certification, or any other SIEM certification for that matter, is not going to be of any use. I went back in after the exam, setup my lab, and played around with it for another week. Quite frankly I think it's a great platform, and a nice little certification to help bolster that resume for entry-level Security Analyst roles where a SIEM is used everyday. Per my understanding from speaking with industry insiders, the <a href="https://www.splunk.com/en_us/training/certification-track/splunk-core-certified-power-user/overview.html" target="_blank" rel="noreferrer noopener">Splunk Core Certified Power User certification</a> is something that's recognized well within the industry. So if you could do this in 2 days, put in some time and effort, and you can definitely go after the Power User certification. Good luck!</p>