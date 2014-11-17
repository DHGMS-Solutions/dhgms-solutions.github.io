---
title: Home
layout: default
---

<h1>DHGMS Solutions Documentation Root</h1>

<p>This is the home of documentation for our open source projects.</p>

<h2>Projects</h2>
<table>
<tr>
  <th>Project Name</th>
  <th>Development State</th>
</tr>
                {% for project in site.data.projects %}
                <tr>
                  <td>
                    <i class="fa fa-bookmark"><!-- --></i><a href="http://dhgms-solutions.github.io/{{ project.folder }}/" title="{{ project.title }}" lang="en" dir="ltr">
                        {{ project.name }}
                    </a>
                  </td>
                  <td>{{ project.devstate }}</td>
                </tr>
                {% endfor %}
</table>

<h2>General Information</h2>
<ul>
  <li><a href="devstates">Description of Project Development States</a></li>
  <li><a href="contibuting">Contributing to projects</a></li>
  <li><a href="devguidelines">General Development Guidelines</a></li>
</ul>
