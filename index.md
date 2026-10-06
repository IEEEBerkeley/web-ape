---
layout: fullwidth
title: Advanced PCB Engineering (APE)
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Berkeley IEEE APE
---

<div class="hero-header">
  <div class="hero-text">
    <h1 class="page-title">Advanced PCB Engineering (APE) – Fall 2026</h1>
    <p class="meta-line"><strong>Instructor:</strong> Aidan Rickert &nbsp;&nbsp; <strong>Lecture:</strong> 8-10PM Tu, Cory 125</p>
  </div>
  <img class="hero-logo" src="{{ '/assets/images/ape.png' | relative_url }}" alt="APE logo">
</div>

{%- if site.under_construction -%}
<p class="warning">
This site is under construction. All dates and policies are tentative until this message goes away.
</p>
{%- endif -%}

{%- if site.waitlist_warning -%}
<p class="warning">
If you're currently on the waitlist, or have any other course-related logistics questions, please take a look at our <a href="{{ site.baseurl }}/policies/">Course Policies</a> prior to contacting course staff.
</p>
{%- endif -%}

{%- if site.outdated -%}
<p class="warning">
This website contains materials from a past semester. Information, assignments, and announcements may no longer be relevant. Please refer to the <a href="https://template.cs161.org">current semester's site</a> for up-to-date content.
</p>
{%- endif -%}

<table id="timeline" style="line-height: normal; width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="width: 5%;">Week</th>
      <th style="width: 35%;">Topic</th> 
      <th style="width: 15%;">Helpful Links</th>
      <th style="width: 15%;">Lab</th>
      <th style="width: 15%;">Lab Checkoff Due</th>
      <th style="width: 15%;">Project Checkpoint</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="week"><strong>1</strong><br>9/8</td>
      <td style="text-align: left;">
        <strong>Intro to Altium</strong><br><br>
        Intro to the class, logistics, and overview of Altium.
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/1Er_3XXvGT4f94rDUYZfg1uGY670_WDn37x3HIVv7Zvs/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 1: Introduction</a></li> 
        </ul>
      </td>
      <td class="lab">
        <a href="https://docs.google.com/document/d/1NXnYE1iO9Q7JT91IQWTQs7Ivh06eUPHDaINq1pjokg8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 1: Intro to Altium Schematics</a><br><br>
        <a href="https://docs.google.com/document/d/1n7WUi9RVcNrMyvJe42HEMZrT90SFxaEiMp7O50SOR0A/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Keybind Cheatsheet</a>
      </td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td class="week"><strong>2</strong><br>9/15</td>
      <td style="text-align: left;">
        <strong>PCB Parasitics and Noise</strong><br><br>
        PCB parasitics, trace and via sizing, EMI, ground planes, crosstalk, reflections, switching noise
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/1LNV7R2GZhx0jwOsVoQm0Pc4N4TguUehJyQuLJv14D3Q/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 2: Parasitics and Noise</a></li>
        </ul>
      </td>
      <td class="lab"> 
        <ul>
          <li><a href="https://docs.google.com/document/d/1oKC2nURpbNFjjGx27X9cDpz_3pp5BdDK9qowyWSTWg8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 2: Introduction to Altium Layout</a></li>
        </ul>
      </td>
      <td>Lab 1: Intro to Altium Schematics</td>
      <td></td>
    </tr>
    <tr>
      <td class="week"><strong>3</strong><br>9/22</td>
      <td style="text-align: left;">
        <strong>Intro to Analog Design</strong><br><br>
        Passive and active filters, selecting op-amps based on their characteristics, voltage references, charge pumps
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/1GYEfiXVO_arjcQqJh56IxN-oNgZTE3PVS1cfQrrAd6M/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 3: Intro to Analog Design</a></li>
        </ul>
      </td>
      <td class="lab">
        <a href="https://docs.google.com/document/d/1nbIc_AhKubVGqOqluoBLX2Qj4CzxwDuMh-qYmmRvfmo/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 3: Simulating Analog Filters</a>
      </td>
      <td>Lab 2: Introduction to Altium Layout</td>
      <td></td>
    </tr>
    <tr>
      <td class="week"><strong>4</strong><br>9/29</td>
      <td style="text-align: left;">
        <strong>Analog/Digital Interface and Intro to Power</strong><br><br>
        Understanding key principles to develop systems designed to accommodate high power draws.
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/12ekAYLrE_DmCJJt6cWYQLPsWxLjAHLNMdJkkK65xbVg/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 4: Analog/Digital Interface and Intro to Power</a></li>
        </ul>
      </td>
      <td class="lab">No lab! Work on project proposals.</td>
      <td>Lab 3 checkoff due 9/29</td>
      <td>
        <ul>
          <li><a href="https://forms.gle/L7r93TCUTzggfT3e6" target="_blank" rel="noopener noreferrer">Project Proposal Due</a></li>
          <li><a href="https://docs.google.com/document/d/14fG8E508X6ri6Ge5I8d6S_j9bk7W6Jn73CtZHWfm0BA/edit?usp=sharing" target="_blank" rel="noopener noreferrer">APE final proj spec v3</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="week"><strong>5</strong><br>10/6</td>
      <td style="text-align: left;">
        <strong>Advanced Schematics, Digital Design, Data Buses and Protocols</strong><br><br>
        Advanced PCB Engineering lecture on advanced digital layout and via management.
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/16cDy7mopXpgBnwNMkBruPGN22-EBcpUTiJRQf0NGYwo/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 5: Advanced Schematics, Digital Design, Data Buses and Protocols</a></li>
        </ul>
      </td>
      <td class="lab">
        <a href="https://docs.google.com/document/d/1gLWDgBC8-80OGgjKct5CEF4iM2tprr0tHp0PA6IL-hA/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 4: Power Electronics</a>
      </td>
      <td></td>
      <td>Proposal Review</td>
    </tr>
    <tr>
      <td class="week"><strong>6</strong><br>10/13</td>
      <td style="text-align: left;">
        <strong>Advanced Digital Layout and Via Management</strong><br><br>
        How to route high-speed signals, differential pairs, and implications of vias, board parasitics, and other physical factors on signal integrity.
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/1_ZCl7IMLuN0Ivs6biHY56lNsjGSdFlnlNlFaaMdNc_w/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 6: Advanced Digital Layout and Via Management</a></li>
        </ul>
      </td>
      <td class="lab">
        <a href="/labs/lab5/" target="_blank" rel="noopener noreferrer">Lab 5: Digital Communication Protocols</a>
      </td>
      <td>Lab 4: Power Electronics DUE 10/13</td>
      <td></td>
    </tr>
    <tr>
      <td class="week"><strong>7</strong><br>10/20</td>
      <td style="text-align: left;">
        <strong>RF Circuits and Schematics 1</strong><br><br>
        Introduction to transmission line theory, differential pairs, impedance matching and other key topics.
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/15Bbm262jhK_l4-DY8lt9SnrdCSQd0dh-rHSWeHiYOhM/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 7: RF Circuits and Schematics</a></li>
        </ul>
      </td>
      <td class="lab"></td>
      <td></td>
      <td>Schematic Due</td>
    </tr>
    <tr>
      <td class="week"><strong>8</strong><br>10/27</td>
      <td style="text-align: left;">
        <strong>Advanced Layout RF Design</strong><br><br>
        Exploration of practical RF design.
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/1wfB92NZHR5C4MOTNtGm4uC0snu0_gWOsi7coW5qw6wc/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Advanced Layout RF Design</a></li>
        </ul>
      </td>
      <td class="lab"></td>
      <td></td>
      <td>Project Work Session</td>
    </tr>
    <tr>
      <td class="week"><strong>9</strong><br>11/3</td>
      <td style="text-align: left;">
        <strong>Project Work Session</strong><br><br>
      </td>
      <td></td>
      <td class="lab">Project Design Review in Class</td>
      <td></td>
      <td><b>Layout Due 11/3</b></td>
    </tr>
    <tr>
      <td class="week"><strong>10</strong><br>11/10</td>
      <td style="text-align: left;">
        <strong>Design Reviews</strong><br><br>
        In-class review of APE student projects<br><br>
      </td>
      <td></td>
      <td class="lab"></td>
      <td></td>
      <td><strong>FINAL PCB files due [11/10] (Tuesday)</strong></td>
    </tr>
    <tr>
      <td class="week"><strong>11</strong><br>11/17</td>
      <td style="text-align: left;">
        <strong>Advanced Mechanical Design Constraint and Weight-Based Design</strong><br><br>
      </td>
      <td>
        <ul>
          <li><a href="https://docs.google.com/presentation/d/1jQytY2FV7XKv-XxSfWle1sIAPW4L4BjP4bUtwZaFObs/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 11: Advanced Mechanical Design Constraint and Weight-Based Design</a></li>
        </ul>
      </td>
      <td class="lab"></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td class="week"><strong>12</strong><br>11/24</td>
      <td style="text-align: left;">
        <strong>TBD</strong><br><br>
        Exploring other advanced design topics, such as maybe Altium AutoRoute, Ethernet, RS485, PCB Antenna Design, DDR Memory, Flex PCB Design, and kW Power Designs<br><br>
      </td>
      <td></td>
      <td class="lab"></td>
      <td></td>
      <td>Project Assembly</td>
    </tr>
    <tr>
      <td class="week"><strong>13</strong><br>12/1</td>
      <td style="text-align: left;">
        <strong>Project Presentations</strong>
      </td>
      <td></td>
      <td class="lab"></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>