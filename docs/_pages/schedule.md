---
title: "Schedule"
tags: ['toppage']
layout: page
---

**Lecture slides**{: class="hi-pri" :} and 
**lab/workshop sheets**{: class="hi-pri" :} can be downloaded
from the [Resources page]({{ "/resources/" | relative_url }}).
The order or delivery date of
lectures on this page may change during the semester.

**Recordings**{: class="hi-pri" :} of the lectures will be
available through UWA's [LMS][lms]{: target="_blank" :} (Learning
Management System).

[lms]: http://www.lms.uwa.edu.au/

The schedule below gives <span>**recommended readings**</span>{:
class="hi-pri" :} for each topic: either chapters from the recommended
texts, or extracts.  Your understanding of the lecture and workshop
material will be greatly enhanced if you work through these readings
<span>*prior*</span>{: class="hi-pri" :} to attending.

References to "*Shotts*" are references to chapters in
[William E. Shotts, Jr, *The Linux Command Line: A Complete
Introduction*][shotts] (see the [**Resources**][shotts] page for where
to get it).

[shotts]: {{ "/resources#textbook" | relative_url }}

<!-- chews up footer, but oh well -->
<div class="expanded">

<table class="csse-table" >
<colgroup>
<col style="width: 10%;">
<col style="width: 15%">
<col style="width: 15%">
<col style="width: 45%">
<col style="width: 15%">
</colgroup>
<tbody>
<tr>
<th>
  Week
</th>
<th>
 Lecture
</th>
<th>
 Lab/workshop
</th>
<th>
  Reading
</th>
<th>
 Assessment
</th>
</tr>
{%- for week in site.data.schedule.weeks -%}
  {% capture idx %}{{ forloop.index }}{% endcapture %}
  {% assign oddrow = idx | modulo: 2  %}
  <tr
  {% if oddrow == 1 %}
      class="odd-row"
  {% else %}
      class="even-row"
  {% endif %}
  >
  <td style="text-align: center;">
   <strong>{{ week.weekNum        }}</strong>
   <br/>
   {{ week.date                   }}
  </td>
  <td>{{ week.lecture       | markdownify }}</td>
  <td>{{ week.workshop      | markdownify }}</td>
  <td>{{ week.reading       | markdownify }}</td>
  <td>{{ week.assessment    | markdownify }}</td>
  </tr>
{%- endfor -%}
</tbody>
</table>

<p>&nbsp;</p>

</div>
<!-- end expanded -->

