---
layout: lesson
root: .
lastupdated: April 16, 2015
contributors: ["Greg Wilson", "Ethan White", "Jens van der Linden", "Raniere Silva", "Meg Stanton", "Amy Brown", "Doug Latornell"]
maintainers: []
domain: Domain Name
topic: Topic
software: Shell
dataurl:
status: Teaching
---

<!-- USING THIS LESSON TEMPLATE -->
<!-- Lesson specific information is taken from the YAML header at the top of the page -->

<!-- THE LESSON INFORMATION -->

<!-- Get the information from _data/info.yml -->

#Data Carpentry {{ page.topic }} for {{ page.domain }}

Data Carpentry's aim is to teach researchers basic concepts, skills,
and tools for working with data so that they can get more done in less
time, and with less pain. The lessons below were designed for those interested 
in working with {{page.domain %}} data in {{page.topic %}}. 


**Content Contributors: {{page.contributors | join: ', ' %}}**


**Lesson Maintainers: {{page.maintainers | join: ', ' %}}**

<br> 


####Lesson status: {{ page.status }} 
<!--
  [Information on Lesson Status Categories]()
-->

<!-- ###### INDEX OF LESSONS ON THIS TOPIC ###### -->

## Lessons:

1. [Introducing the Shell](00-intro.html)
2. [Files and Directories](01-filedir.html)
3. [Creating Things](02-create.html)
4. [Pipes and Filters](03-pipefilter.html)
5. [Loops](04-loop.html)
6. [Shell Scripts](05-script.html)
7. [Finding Things](06-find.html)


## Data

Data files for the workshop are available here: ({{page.dataurl %}})[{{page.dataurl %}}]


<br>

<h2>Requirements</h2>

<p>
Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to insure the proper setup of tools for an efficient workflow.
<em>These lessons assume no prior knowledge of the skills or tools</em>, but working 
through this lesson requires working copies of the software described below.
To most effectively use these materials, please make sure to install everything 
<em>before</em> working through this lesson.
</p>



{% if page.software == "Python" %}
{% include pythonSetup.html %}
{% elsif page.software == "Spreadsheets" %}
{% include spreadsheetSetup.html %}
{% elsif page.software == "R" %}
{% include rSetup.html %}
{% elsif page.software == "Shell" || page.software == "shell" %}
{% include shellSetup.html %}
{% else %}
{% include anySetup.html %}
{% endif %}

<p><strong>Twitter</strong>: @datacarpentry