## Black in Robotics Reading List

>_"U.S. history is racist, and the responsibility for fixing systemic racism within [an] institution lies with current members of the institution."_ -[Black in Engineering](https://blackinengineering.org/action-item-list/)

The diversity of [researchers in academia](https://www.pewresearch.org/fact-tank/2019/07/31/us-college-faculty-student-diversity/), and of Black faculty members in particular, is much lower than it should be and [has stalled](https://vanderbilt.app.box.com/s/qqehfi70bq5zmnptqvhqivpf9s6wlkzq). This site contains a reading list of work from Black researchers in robotics that will hopefully help in some small way to overcome the systemic dynamics that have led to this imbalance. There are two ways that this list may help: First, to [increase the visibility and citations](https://blackincomputing.org/action-item-list/) of these researchers by highlighting their research projects and advertising some of their interesting papers. Second, to provide academic [role models](https://www.insidehighered.com/advice/2016/05/25/why-its-important-identify-role-models-essay) for aspiring researchers and to [normalize Black scholarship](https://blackinengineering.org/action-item-list/). Whether browsing this list online, seeing a researcher on a panel, or reading one of their papers as a class assignment, it is important for all students to see diversity in academia.

**Who is this list for?** We started to build this list for our own labs and classes, in order to increase the number of Black scholars that we cite and discuss. We hope that it can also be useful for others in the community, especially:
* Undergraduate students looking for possible graduate school mentors.
* Paper authors looking for a citation on a given topic.
* Workshop or panel organizers looking for experts in the field.
* Instructors building a reading list for a class syllabus.
* Everyone in the community who would like to learn more about cutting edge research in different areas of robotics.

**Who is on this list?** The focus of this list is Black professors in the US researching robotics and related fields. While there are many groups that are underrepresented in academic robotics (including Indigenous/Native people, Latinx people, people with disabilities, and [women](https://us-women-in-robotics-research.github.io/)), there is a particularly long and persistent history of suppression of Black Americans in the US. Similarly, this list is focused on Black robotics faculty members, but there are also many great roboticists in industry, and many great academics outside of robotics (e.g. [computing](https://blackcomputeher.org/citeher-bibliography/), [AI](https://blackinai.github.io/), [neuro](https://www.blackinneuro.com/profiles)), who should also be celebrated. 

<hr>

{% assign items = site.people | sort: 'last_name' %}
{% for person in items %}
<div class="person">
  <img src="{{ person.image  }}">
  <div class="persondesc">
      <h2>{{ person.first_name }} {{ person.last_name }}</h2>
      <p><a href="{{ person.website }}">{{ person.title }}</a>, {{  person.school  }} </p>
      <p>{{ person.content | markdownify }}</p>
  </div>
</div>
{% endfor %}


<hr>

This list is maintained by [Prof. Aaron M. Johnson](http://www.andrew.cmu.edu/user/amj1/), [Prof. Henny Admoni](https://hennyadmoni.com/), and our students.
Updates, additions, and corrections welcome via pull request or [email](mailto:amj1+blackinrobotics@andrew.cmu.edu).
Sourcecode available on [GitHub](https://github.com/BlackInRobotics/BlackInRobotics.github.io). 

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
