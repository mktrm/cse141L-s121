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

Computer Organization and Design MIPS Edition, The Hardware/Software Interface, Fifth Edition (Patterson & Hennessy) (ISBN-13: 978-0124077263, ISBN-10: 0124077269)

## Format 
Course format is a 1-hour lecture two days per week, plus independent work over CloudLabs or self-contained at home on own computers. Attendance is strongly recommended, but not required, and all lectures are recorded.
Discussions, Q&A, peer-to-peer instruction, etc. take place on our Piazza website. You are encouraged to post questions, help answer other students' questions, and provide feedback and suggestions to your instruction staff.
What is important to me is that students put forth an honest effort and treat one another, and the instructors, courteously. Constructive criticism is always welcome. 

## Assignments
Students shall work in teams of one to three members each. 
There are four lab reports, due at the starts of the 3rd, 4th, 5th weeks and the end (Sunday night) of the 5th week. See Canvas for specifics. Reports shall be submitted on Gradescope.

## Grading 
Each team shall design a microprocessor -- its hardware, its firmware (machine code), and its software (assembly code). These will be tested on three program assignments, and final course grades will depend solely on Lab 4, on how many programs a given processor can run successfully. 

A-/A: all three programs run almost/properly; 

B/B+: two programs run almost/properly;

C+/B-: one program runs almost/properly;

C: programs do not run properly, but design compiles and shows some thought/effort

D, F: rarely given, reserved for those who do not apply themselves

## Academic Integrity  
This is a collaborative course, but students are expected to do their own work and to refrain from taking credit for the work of others. 

## Late Assignments
No late turn-ins for Lab 4. Sunday night at the end of Week 5 is an absolute cutoff.

## Accommodations for Students with Disabilities
If you have a disability for which you are or may be requesting accommodations, please contact Office for Students with Disabilities.  You must have documentation from the the Office before accommodations can be granted.

## Agenda 
{% for module in site.modules %}
{{ module }}
{% endfor %}
