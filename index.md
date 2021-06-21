---
layout: home
title: CSE-141L
nav_exclude: true
seo:
  type: Course
  name: 'Introduction to Computer Architecture Lab'
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }



The course offers hands-on computer architecture project aiming to familiarize students with instruction set architecture, design of processor, and control and memory systems, and I/O systems. This is a computer architecture project course.

This course is designed to run alongside [CSE 141](#). We expect that you are enrolled in both.


<!-- <details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details> -->

 
<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Meetings
Lectures are Monday from 2:00 to 3:50 US/Pacific, on [Zoom](#).

Labs are Wednesday from 2:00 to 3:50 US/Pacific, on [Zoom](#).

Office Hours: TBD 

## Prerequisites
CSE 110, CSE 140, and CSE 140L. 
CSE 141 should be taken either before or concurrently.

## Textbook
There is no textbook for the class, but you will find the CSE 141 textbook helpful in many ways during the lab:
Computer Organization and Design MIPS Edition, The Hardware/Software Interface, Fifth Edition (Patterson & Hennessy) (ISBN-13: 978-0124077263, ISBN-10: 0124077269)

## Format 
Course format is lectures over Zoom, two days per week, plus independent work over CloudLabs or self-contained at home on own computers. Attendance is strongly recommended, but not required, and all lectures are recorded.
Discussions, Q&A, peer-to-peer instruction, etc. take place on our [Piazza](#). You are encouraged to post questions, help answer other students' questions, and provide feedback and suggestions to your instruction staff.
What is important to me is that students put forth an honest effort and treat one another, and the instructors, courteously. Constructive criticism is always welcome. 

## Assignments
Students shall work in teams of two to three members each. 
There are four lab reports, due at the starts of the 3rd, 4th, 5th weeks and the end (Sunday night) of the 5th week. See Canvas for specifics. Reports shall be submitted on [Gradescope](#).

## Grading 
Each team shall design a microprocessor -- its ISA, its hardware, and its software (assembly code). 
These will be tested on three program assignments, and final course grades will depend mostly on Lab 4.
The first three labs each constitude 5% of your final grade. The remaining 85% depends on Lab 4.
Lab 4 will be graded on the number of programs your processor can run: 

- Only one program runs properly -> 80% of Lab 4's grade
- Two programs run properly -> 90% of Lab 4's grade
- Three programs run properly -> 100% of Lab 4's grade




## Academic Integrity  
This is a collaborative course, but students are expected to do their own work and to refrain from taking credit for the work of others. 
Cheating WILL be taken seriously. It is not fair to honest students to take cheating lightly, nor is it fair to the cheater to let him/her go on thinking that is a reasonable alternative in life. 

"Don't test me on this one." ~Prof. Dean Tullsen


The following is not considered cheating:

- discussing the tools or logic design techniques with other groups.

The following is:

- Copying lab designs from someone who is not your partner, or lab report text from anyone. 
- Viewing lab designs or lab reports from anyone who is not your partner, including those who have taken the class in previous years. 
- Altering timing data produced by simulation, e.g. to make a non-working design appear to be working.

Penalties -- anyone copying information or having information copied on a lab, or any other violation of class policy, will receive an F in the class and will not be allowed to drop.  They will be reported to their college dean.  If you can prove non-cooperative copying took place, your grade may be restored, but you must prove it to the dean -- I don't want to be involved.

## Late Assignments
No late turn-ins for any Lab. Sunday night at the end of Week 5 is an absolute cutoff for Lab 4.


## Agenda 
{% for module in site.modules %}
{{ module }}
{% endfor %}


## DISCLAIMER
Due to our unusual circumstances, the details in this syllabus may change (e.g. schedule, grading policy, assignments, etc.). We will update this syllabus in the event of changes as the course progresses.