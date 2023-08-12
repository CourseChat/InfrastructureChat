---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.

currWeekNumber: 8
---

# Civil Engineering and Generative AI Language Models

{: .mb-2 }
UC Berkeley, Summer 2023
{: .mb-0 .fs-6 .text-grey-dk-000 }



<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }
> Welcome to [Week 8](#week-{{page.currWeekNumber}})!


<a name="schedule"></a>
## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}