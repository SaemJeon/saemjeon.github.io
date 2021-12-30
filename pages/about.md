---
layout: page
title: About
permalink: /about/
weight: 1 
---

{% include elements/button.html link="https://github.com/SaemJeon/resume/blob/master/resume.pdf" text="Resume" style="outline-secondary" size="sm" %}


# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am passionate about learning new skills. I have experience in software engineering as well as hardware. I am a senior at Drexel University and enrolled in BS/MS program. I am double majoring in Electrical and Computer Engineering for my undergrad degree and studying Computer Science for my Masters. I have interned at Amazon Web Services (AWS), Bentley Systems, and iPipeline. I will be joining Robinhood as a Backend Engineer upon my graduation from Drexel. 


## Education
#### Drexel University (Expected Graduation: June 2022)
- M.S. in Computer Science
- B.S. in Electrical and Computer Engineering
- Minor in Business Administration
- GPA: 4.0 (Dean's List)


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

## Work Experience
<div class="row">
{% include about/timeline.html %}
</div>