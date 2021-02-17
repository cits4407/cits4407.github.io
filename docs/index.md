---
title: "Open Source Tools and Scripting"
layout: default
---

<style>

ul, ol, dl, li p {
  margin: 0 0 0.70em;
}
</style>

## Welcome to Open Source Tools and Scripting

Welcome to the website for CITS2003 and CITS4407
in {{ site.data.globals.year }}. **All material (lectures, workshops,
assignments) for this unit will be published on these pages, and not on
the LMS**{: class="hi-pri" :} -- with the exception of recorded lectures
and the unit outline (which are available through the
[LMS][lms]{: target="_blank" :}).

[lms]: https://lms.uwa.edu.au

See below for quick details of the
[**weekly activities**](#weekly-activities){: class="hi-pri" :}
and
[**assessment**](#assessment){: class="hi-pri" :}
for the unit, as well as [who will be facilitating](#facilitators) the labs/workshops.

At the top of the page, you should find links that
give you more detail on the
[**schedule**](schedule){: class="hi-pri" :} of topics
covered and the online
[**resources**](resources){: class="hi-pri" :}
available to you (including lecture slides and lab/tutorial exercise
sheets).

If you have queries regarding the unit, a good place to ask them is
on the [**discussion forum**][help]{: target="_blank" :}
for the unit, [help{{ site.data.globals.citscode }}][help]{: class="hi-pri" target="_blank" :} --
that way, all students can benefit from answers to your questions.

[help]: https://secure.csse.uwa.edu.au/run/help{{ site.data.globals.citscode }}

#### Overview

This unit introduces students to the philosophy, design, tools and
practices that enable and facilitate the success of open source
software, which runs much of the world's computing infrastructure.
Important topics covered include the use of the shell as a programming
language, the use of the file system and pipes to support interprocess
communication, fundamental software components, tools supporting the
software development and maintenance process, and the importance of
consistent interfaces to support software integration.

#### Unit Coordinator

[**{{ site.data.coordinator.name }}**][coordinator-dir]{: target="_blank" :}  

| **Office** |{{ site.data.coordinator.room }}
| **Email** | {{ site.data.coordinator.email | unescape }}
| **Availability** | I am at UWA (physically or virtually) on Tuesdays, Thursdays and Fridays. 
| **Consultation** | {{ site.data.coordinator.consultation | unescape }} 
{: class="inline-table"}

[coordinator-dir]: {{ site.data.coordinator.directory }}

#### Textbook

See the
[**resources**](resources){: class="hi-pri" :}
page.


#### Weekly activities

- There is one lecture each week. You should either attend in person,
  attend online (details to be advised – we will use either Zoom or Microsoft
  Teams), or watch the recorded lecture.
- You should attend one lab each week, starting in week
  ***two***{: class="hi-pri" :}.
  If there is room available for you, you are welcome to attend other
  lab sessions as well.

Note that materials presented during class sessions
**<span>*do not*</span> define the whole unit**{: class="hi-pri" :}.
A six-point unit is deemed to be equivalent to one quarter of a
full-time workload, and so you will be expected to commit 10--12 hours
per week to the unit, averaged over the entire semester.
Outside of the contact hours (3 hours per week) for the unit, the
remainder of your time should be spent reading the recommended reading,
attempting exercises and working on assignment tasks.

The [**schedule**](schedule){: class="hi-pri" :}
contains the list of **recommended readings**{: class="hi-pri" :} for each
topic. To gain maximum benefit from the lectures and workshops, I
recommend you at least review these *before* attending class.

#### Assessment

{{ site.data.globals.assessment | unescape }} See the
[Assessment]({{ "/assets/css/responsive-nav.css" | relative_url }})
page for further details.

| Assessment | % of final mark | Assessment Dates
|-
| [Quiz]({{"/assessment#quiz"| relative_url }}) (online) | {{ site.data.globals.q1marks }}% | {{ site.data.globals.q1date }}
| [Assignment 1]({{"/assessment#asst1"| relative_url }}) | {{ site.data.globals.a1marks }}% | {{ site.data.globals.a1date }}
| [Assignment 2]({{"/assessment#asst2"| relative_url }}) | {{ site.data.globals.a2marks }}% | {{ site.data.globals.a2date }}
| [Examination]({{"/assessment#exam"| relative_url }}) | {{ site.data.globals.exammarks }}% | June examination period
{: class="csse-table" style="width: 80%; text-align: center;" }

{{ site.data.globals.submission | unescape }} As the
semester proceeds, your marks will be updated and recorded in
[csmarks][csmarks]{: target="_blank" :}.

[csmarks]: https://secure.csse.uwa.edu.au/run/csmarks

#### Who'll be helping in labs/workshops {#facilitators}

| ![Alvaro]({{"/assets/images/alvaro.jpg"| relative_url }}){: style="box-shadow: 4px 4px 2px #888888; width: 166px; height: 140px;" :}<center><span style="font-size: 0.9em;">Alvaro Monsalve</span></center> | <span style="display: inline-block; width: 2em;"></span> | ![Alvaro]({{"/assets/images/daniel.jpg"| relative_url }}){: style="box-shadow: 4px 4px 2px #888888; width: 131px; height: 140px;" :}<center><span style="font-size: 0.9em;">Daniel Smith</span></center>

## Policies

Before undertaking this unit,
students are strongly encouraged to read the university policies that apply
to this unit:

- UWA's [University charter of student rights and responsibilities][charter]{: target="_blank" :}
- UWA's [Policy on Assessment][assessment-policy]{: target="_blank" :} -- particularly &sect;10.2 <i>Principles of submission and penalty for late submission</i>,
- UWA's [Policy on Academic Conduct][academic-conduct]{: target="_blank" :}

[charter]: https://www.uwa.edu.au/policy/-/media/Policy/Policy/Student-Administration/Charter-of-Student-Right-and-Responsibilities/Charter-of-Student-Rights-and-Responsibilities.doc
[assessment-policy]: https://www.uwa.edu.au/policy/-/media/Policy/Policy/Teaching-and-Research-Training/Learning-and-Teaching/Assessment/Assessment-Policy.doc
[academic-conduct]: https://www.uwa.edu.au/policy/-/media/Policy/Policy/Student-Administration/Academic-Conduct/Academic-Conduct-Policy.doc

<!--
  vim: tw=72
-->
