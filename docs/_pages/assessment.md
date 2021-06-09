---
title: "Assessment"
tags: ['toppage']
layout: page
---

<style>
.hi-pri {
  color: #053cc9;
}

ul, ol, dl, li p {
  margin: 0 0 0.70em;
}
</style>

{{ site.data.globals.assessment | unescape }}
{{ site.data.globals.submission | unescape }}

### Quiz ({{ site.data.globals.q1marks }}%) {#quiz}

There will be an online quiz in {{ site.data.globals.q1date }}.

Details are as follows:

- The quiz will be accessible by logging into UWA's
  [**LMS**][lms]{: target="_blank" class="hi-pri" :} (Learning Management System),
  accessing the CITS2003/CITS4407 content,
  and selecting "Week 3 quiz". (Be aware that, for reasons LMS admins
  seem unable to explain, CITS4407 content is listed under
  the LMS as CITS2003 content.)
- The quiz will be available on the LMS from **9am Tuesday 9th March**{:
  class="hi-pri" :} until **5pm Friday 12th March**{: class="hi-pri" :}.   
  But ensure you leave at least 1-2 hours available in which to complete
  the quiz. If you wait until after 3pm Friday 12th March to start the quiz,
  and don't complete it, you will be awarded 0 marks.   
  The quiz will need to be completed in one sitting, and students are
  allowed one attempt at it.  
- The questions will be either multiple choice or short answer.   
  The quiz is open-book; you can make use of any book, website or
  software you like.  
  Questions may be drawn from any content contained in lectures, lecture
  slides, lab/workshop exercises or assigned readings up until the end
  of week 2 (i.e. the week commencing Monday 8 March), or may require
  you to make reasonable inferences from that material or to investigate
  questions arising from that material.   
- Ensure you have a good Internet connection when sitting the quiz --
  you should sit it either on a UWA lab computer, or at home,
  but not using WiFi or a mobile device, as these could drop out
  part-way through.   
  If you use a  WiFi or mobile connection and it fails, you won't be
  given extra time to complete the quiz.  
  If for some reason you can't access the quiz on the LMS, email me
  immediately from your University email account with a screenshot or
  photo showing the problem.


[lms]: http://www.lms.uwa.edu.au/

### Assignment 1 {#asst-1}

Assignment 1, worth {{ site.data.globals.a1marks }}%
of the unit's marks, has been released and is due at 11:59 pm
on Sunday 25th April.

The assignment spec is available
[**here**]({{ "/workshops/assignment1.pdf" | relative_url }}){: class="hi-pri" :} (PDF),
and starting code for the assignment is available at this
Git repository: <https://github.com/cits4407/assignment1>.

Submission is via the CITS4407 Git marking server -- see
[here](https://github.com/cits4407/assignment1#submission)
for the procedure, and
see below for tips on using the backup submission
procedure, [cssubmit](#cssubmit-tips).

**UPDATE**{: class="hi-pri" :}: the assignment has been marked,
and your mark should be available in [**csmarks**][csmarks]{: class="hi-pri" :}
together with a PDF report providing a breakdown of your mark and
feedback from markers.
Sample solutions are available
[**here**][asst1-sample-solutions]{: class="hi-pri" :} (.zip file). If
you have any queries regarding your mark, please email the unit
coordinator.

[csmarks]: https://secure.csse.uwa.edu.au/run/csmarks
[asst1-sample-solutions]: {{ "workshops/assignment1-sample-solutions.zip" | relative_url }}

### Assignment 2 {#asst-2}

An assignment worth {{ site.data.globals.a2marks }}%
of the unit's marks will be due in {{ site.data.globals.a2date }},
at 23:59pm on Sunday 23 May.

The assignment is in a private repository -- to view it,
you need to "accept" the following invitation link to
GitHub classrooms: <https://classroom.github.com/a/JCoB7Quc>.


### Exam ({{ site.data.globals.exammarks }}%) {#exam}

There will be a 2-hour exam in the June examination period.

A **past CITS4407 exam from 2019**{: class="hi-pri" :} is available which may be useful for
revision purposes. To access it:

- Google "onesearch UWA" and click on the first link
- You're now at the website for Onesearch, UWA's web interface to library search resources
- Click "Sign into Onesearch" (at the top right of the screen), and log in using your Pheme credentials
- Type "CITS4407 2019" into the search bar
- Click on the result
	 
(Alternatively - if you just google "UWA past exam papers", it takes you
to a page which gives the same information as I have above.) Note that
the exam is copyright; you are granted a license to use it for personal
study, but may not distribute, re-publish or upload it elsewhere.
 
The 2019 exam is the only previous CITS4407 exam set by me. Exams from
other years are a less good guide to what you can expect in this year's
exam.

**Other details**{: class="hi-pri" :} about this year's exam:

- It will have 4 questions with a total value of 60 marks
- The time allowed for completion is 2 hours
- You are permitted to bring one A4 page of notes into the exam; the
  notes must be hand written, not photocopied or printed, and may be
  written on both sides of one A4 page. The page can not be folded or
  have any attachments.

When **writing Bash code**{: class="hi-pri" :} in the exam:

- If you can’t recall the exact command-line arguments or flags needed
  to produce a particular effect, you may instead add comments stating
  what you're trying to achieve, and what you *can* recall about the
  arguments or flags.
- If you like, you can structure your answer with headings, and some
  discussion of each block of code before you write it out.
- Although we allow a fair bit of latitude when it comes to getting all
  the arguments and flags for a command correct, we *do* expect you to
  know how Bash control flow structures (`if` statements and loops)
  work, how to construct pipelines and perform redirection, and
  what different commands do.

### Tips for using cssubmit {#cssubmit-tips}

-   Make sure you submit in the correct format (specified
    for each assessment).
-   Make sure you have agreed to the submission conditions
    and confirmed this is original work
-   Make sure you ***print***{: class="hi-pri" :} off the confirmation
    page as a record afterwards
-   The end result should look something like this
    (click for a larger image); make sure it says 1 file was
    submitted and validated successfully.<br><br>
    [<img src="{{ "/workshops/successful-submission.svg" | relative_url }}" width="160%" height="160%">]({{ "/workshops/successful-submission.svg" | relative_url }})

<!--
  vim: tw=72
-->
