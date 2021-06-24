---
layout: home
title: CSE-141L
nav_exclude: true
seo:
  type: Course
  name: 'Introduction to Computer Architecture Lab'

toc: true
toc_label : "On this page"
toc_hmin: 2
toc_hmax: 6
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }



The course offers hands-on computer architecture project aiming to familiarize students with instruction set architecture, design of processor, and control and memory systems, and I/O systems. This is a computer architecture project course. Together, we design a complete special-purpose processor from grounds up. 
I hope that you will have fun taking this course as much as we will enjoy teaching it!

This course is designed to run alongside [CSE 141](https://mktrm.github.io/cse141-s121/){:target="_blank"}. We expect that you are enrolled in both.



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
Lectures are Monday from 2:00 to 3:50 US/Pacific, on [Zoom](https://canvas.ucsd.edu/courses/27993/external_tools/628){:target="_blank"}.

Labs are Wednesday from 2:00 to 3:50 US/Pacific, on [Zoom](https://canvas.ucsd.edu/courses/27993/external_tools/628){:target="_blank"}.

Updated Office Hours on Canvas (See [Course Calendar](https://canvas.ucsd.edu/calendar?include_contexts=course_27993){:target="_blank"}).

## Prerequisites
CSE 110, CSE 140, and CSE 140L. 
CSE 141 should be taken either before or concurrently.

## Textbook
There is no textbook for the class, but you will find the CSE 141 textbook helpful in many ways during the lab:
Computer Organization and Design MIPS Edition, The Hardware/Software Interface, Fifth Edition (Patterson & Hennessy) (ISBN-13: 978-0124077263, ISBN-10: 0124077269)

## Format 
Course format is lectures over Zoom, two days per week, plus independent work over CloudLabs or self-contained at home on own computers. Attendance is strongly recommended, but not required, and all lectures are recorded.


## Online Discussion 
Discussions, Q&A, peer-to-peer instruction, etc. take place on our [edstem](https://edstem.org/){:target="_blank"}. You will receive an invitiation email to join the course a few days before the start of the class. You are encouraged to post questions, help answer other students' questions, and provide feedback and suggestions to your instruction staff. Constructive criticism is always welcome. 

{: .warning }
While the instruction staff will do their best to answer any question as soon as possible, be aware (and plan ahead) that instruction staff will not be available 24/7. 

## Assignments
Students shall work in teams of two to three members each. 
There are four lab reports, due at the starts of the 3rd, 4th, 5th weeks and the end (Sunday night) of the 5th week. See Canvas for specifics. Reports shall be submitted on [Gradescope](https://canvas.ucsd.edu/courses/27993/external_tools/80){:target="_blank"} (the canvas page needs Chrome or Firefox).

## Grading 
Each team shall design a microprocessor -- its ISA, its hardware, and its software (assembly code). 
These will be tested on three program assignments, and final course grades will depend mostly on Lab 4.
The first three labs each constitude 5% of your final grade. The remaining 85% depends on Lab 4.
Lab 4 will be graded on the number of programs your processor can run: 

- Only one program runs properly -> 80% of Lab 4's grade
- Two programs run properly -> 90% of Lab 4's grade
- Three programs run properly -> 100% of Lab 4's grade

We will use the following scale for your final grade:

<div class="table-responsive">
<table class="table grade-table">
  <tbody><tr>
    <th>A+<br><small>&gt;96.7</small></th>
    <th>A<br><small>[93,96.7)</small></th>
    <th>A-<br><small>[90,93)</small></th>
    <th>B+<br><small>[86.7,90)</small></th>
    <th>B<br><small>[83.3,86.7)</small></th>
    <th>B-<br><small>[80,83.3)</small></th>
    <th>C+<br><small>[76.7,80)</small></th>
    <th>C<br><small>[73.3,76.7)</small></th>
    <th>C-<br><small>[70,73.3)</small></th>
    <th>D<br><small>[60,70)</small></th>
    <th>F<br><small>[0,60)</small></th>
  </tr>
</tbody></table>
</div>

{:.warning}
This table might be revisited later in the class.



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

{: .danger}
Penalties -- anyone copying information or having information copied on a lab, or any other violation of class policy, will receive an F in the class and will not be allowed to drop.  They will be reported to their college dean.  If you can prove non-cooperative copying took place, your grade may be restored, but you must prove it to the dean -- I don't want to be involved.

## Late Assignments
No late turn-ins for any Lab. **Sunday night at the end of Week 5 is an absolute cutoff for Lab 4.**


## Agenda 
{% for module in site.modules %}
{{ module }}
{% endfor %}


## DISCLAIMER
Due to our unusual circumstances, the details in this syllabus may change (e.g. schedule, grading policy, assignments, etc.). We will update this syllabus in the event of changes as the course progresses.

## Credit
This page uses materials from John Eldon and Dean Tullsen.