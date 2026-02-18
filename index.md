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
    <h1 class="page-title">Advanced PCB Engineering (APE) – Spring 2026</h1>
    <p class="meta-line"><strong>Instructor:</strong> Aidan Rickert &nbsp;&nbsp; <strong>Lecture:</strong> 8-10PM Tu, Cory 125</p>
  </div>
  <img class="hero-logo" src="{{ '/assets/images/ape.png' | relative_url }}" alt="APE logo">
</div>
<!-- {:.no_toc} -->

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

<table id="timeline" style="line-height: normal;">
    <tbody><tr>
      <th style="width: 5%;">Week</th>
      <th style="width: 35%;">Topic</th> 
      <th style="width: 15%;">Helpful Links</th>
      <th style="width: 15%;">Lab</th>
      <th style="width: 15%;">Lab Checkoff Due</th>
      <th style="width: 15%;">Project Checkpoint</th>
    </tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>1</strong> <br> 
        1/27
    </td>
    
    <td style="text-align: left;">
        <strong>Intro to Altium</strong><br><br>
        Intro to the class, logistics, and overview of Altium. 
    </td>
    
    <td>
        <ul>
        	<li><a href="https://docs.google.com/presentation/d/1Er_3XXvGT4f94rDUYZfg1uGY670_WDn37x3HIVv7Zvs/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 1: Introduction</a>
            </li> 
        </ul>
    </td>
    
    <td class="lab">
 
            <a href="https://docs.google.com/document/d/1NXnYE1iO9Q7JT91IQWTQs7Ivh06eUPHDaINq1pjokg8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 1: Intro to Altium Schematics</a><br><br>
            <a href="https://docs.google.com/document/d/1n7WUi9RVcNrMyvJe42HEMZrT90SFxaEiMp7O50SOR0A/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Keybind Cheatsheet</a>

    </td>
	<td>
    </td>
    <td>
    </td>
    
</tr>                                      <!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>2</strong> <br> 
        2/3
    </td>
    <td style="text-align: left;">
        <strong>PCB Parasitics and Noise
</strong><br><br>
        PCB parasitics, trace and via sizing, EMI, ground planes, crosstalk, reflections, switching noise
    </td>
    <td>
        <ul>
            <li>
        <a href="https://docs.google.com/presentation/d/1LNV7R2GZhx0jwOsVoQm0Pc4N4TguUehJyQuLJv14D3Q/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 2: Parasitics and Noise</a> </li>
        </ul>
    </td>
    <td class="lab"> 
        <ul>
            <li>
        <a href="https://docs.google.com/document/d/1oKC2nURpbNFjjGx27X9cDpz_3pp5BdDK9qowyWSTWg8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 2: Introduction to Altium Layout</a> </li>
        </ul>
    </td>
    	
    <td>
        Lab 1: Intro to Altium Schematics
    </td>
    <td>
        
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>3</strong> <br> 
        2/10
    </td>
    <td style="text-align: left;">
               <strong>Intro to Analog Design
</strong><br><br>
        Passive and active filters, selecting op-amps based on their characterisitcs, voltage references, charge pumps
    </td>
    	
    <td>
        <ul>
            <li>
                <a href="https://docs.google.com/presentation/d/1GYEfiXVO_arjcQqJh56IxN-oNgZTE3PVS1cfQrrAd6M/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 3: Intro to Analog Design</a> 
            </li>
        </ul>
    </td>
    <td class="lab">
        <a href="https://docs.google.com/document/d/1nbIc_AhKubVGqOqluoBLX2Qj4CzxwDuMh-qYmmRvfmo/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 3: Simulating Analog Filters</a>
    </td>
    <td>
        Lab 2: Introduction to Altium Layout
    </td>
    <td>
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>4</strong> <br> 
        2/17
    </td>
    <td style="text-align: left;">
        <strong>Analog/Digital Interface and Intro to Power
</strong><br><br>
        Understanding key principles to develop systems designed to accomodate high power draws. 
        
    </td>
    <td>
        <ul>
            <li>
                <a href="https://docs.google.com/presentation/d/12ekAYLrE_DmCJJt6cWYQLPsWxLjAHLNMdJkkK65xbVg/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lecture 4: Advanced Schmatics High Power Design</a>
            </li>
        </ul>
    </td>
    <td class="lab">
        <a href="https://docs.google.com/document/d/1gLWDgBC8-80OGgjKct5CEF4iM2tprr0tHp0PA6IL-hA/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Lab 4: Power Electronics</a>
    </td>
    <td>
        Lab 3 checkoff due 2/17
    </td>
    <td>
        <ul>
            <li>
                <a href="https://docs.google.com/forms/d/e/1FAIpQLSdqfbmsdPz6GaCUTS8EzZ5HZNTBo_bfcICP816pk1ucZN9aUQ/viewform?usp=sharing" target="_blank" rel="noopener noreferrer">Project Proposal Due</a>
            </li>
            <li>
                <a href="https://docs.google.com/document/d/14fG8E508X6ri6Ge5I8d6S_j9bk7W6Jn73CtZHWfm0BA/edit?usp=sharing" target="_blank" rel="noopener noreferrer">APE final proj spec v3</a>
            </li>
        </ul>
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>5</strong> <br> 
        2/24
    </td>
    <td style="text-align: left;">
        <strong> Advanced Schematic to Layout: High Power design and Thermal Management</strong><br><br>
        Designing layouts optimized for high-voltage and high-current applications. Develop understanding of thermal implications of high-power designs and best practices to mitigate them. 
    </td>
    <td>
         <ul>
            <li>
                <a href="https://docs.google.com/presentation/d/1k7tmrHcrFgW7kixzW11JC486pO7Q-0EGscT4Pxq_YdQ/edit?usp=sharing&amp;ref=ieee.berkeley.edu" target="_blank" rel="noopener noreferrer">Lecture 5 Slides</a>
             </li>
        </ul>
    </td>
    <td class="lab">
        Continue Power Regulator Circuitry Design and Simulation
    </td>
    <td>
    </td>
    <td>
<a href="http://berkie.ee/ape-fa25-proj-proposal" target="_blank" rel="noopener noreferrer">Project Proposal Due</a> 
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>6</strong> <br> 
        3/3
    </td>
    <td style="text-align: left; line-height: 30px;">
        <strong> Advanced Layout Digital Layout: and Via Management</strong><br><br>
        How to route high-speed signals, differential pairs, and implications of vias, board parasitics, and other physical factors on signal integrity. 
    </td>
    <td>
        <ul>
            <li>
                <a href="https://docs.google.com/presentation/d/1_ZCl7IMLuN0Ivs6biHY56lNsjGSdFlnlNlFaaMdNc_w/edit?usp=sharing&amp;ref=ieee.berkeley.edu" target="_blank" rel="noopener noreferrer">Slides</a>
            </li>
        </ul>
    </td>
    <td class="lab">
		Continue High Power Design and Thermal Management
    </td>
    <td>
        
    </td>
    <td>
        Proposal Review
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td style="border-right: 1px solid; text-align:center;">
        <strong>7</strong> <br> 
        3/10
    </td>
    <td style="text-align: left;">
        <strong>Advanced Layout + RF Design
 1</strong><br><br>
        Introduction to transmission line theory, differential pairs, impedance matching and other key topics.
    </td>
    <td>
        <ul>
            <li>
                <a href="https://docs.google.com/presentation/d/1wfB92NZHR5C4MOTNtGm4uC0snu0_gWOsi7coW5qw6wc/edit?usp=sharing&amp;ref=ieee.berkeley.edu" target="_blank" rel="noopener noreferrer">Slides</a> 
            </li>
        </ul>
    </td>
    <td class="lab">
    </td>
    <td>
        High Power Design and Thermal Management
    </td>
    <td>
        Project BOM &amp; Schematic Due [TBD]
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>8</strong> <br> 
        3/17
    </td>
    <td style="text-align: left;">
        <strong>Advanced Layout + RF Design 2</strong><br><br>
        Exploration of practical RF design. 
    </td>
    <td>
        <ul>
            <li>
                <a href="https://docs.google.com/presentation/d/1wfB92NZHR5C4MOTNtGm4uC0snu0_gWOsi7coW5qw6wc/edit?usp=sharing&amp;ref=ieee.berkeley.edu" target="_blank" rel="noopener noreferrer">Slides</a>
            </li>
        </ul>
    </td>
    <td class="lab">
    </td>
    <td>
    </td>
    <td>
        Project Work Session
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>9</strong> <br> 
        3/24
    </td>
    <td style="text-align: left;">
        <strong> Project Work Session
</strong> <br> <br>
    </td>
    
    <td>
        
    </td>
    <td class="lab">
Project Design Review in Class<br>
    </td>
    <td>
    </td>
    <td>
        <b>Layout Due 11/4</b>
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>10</strong> <br> 
        3/31
    </td>
    <td style="text-align: left;">
        <strong>Design Reviews</strong><br><br>
            In class review of APE student projects
        <br><br>
        
    </td>
    <td>
    </td>
    <td class="lab">
    </td>
    <td>
    </td>
    <td>
        <strong>FINAL PCB files due [11/4] (Tuesday)</strong>
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td style="border-right: 1px solid; text-align:center;">
        <strong>11</strong> <br> 
        4/7
    </td>
    <td style="text-align: left;">
        <strong>TBD</strong><br><br>
        <br><br>
        
    </td>
    <td>
    </td>
    <td class="lab">
                
    </td>
    <td>
    </td>
    <td>
        
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>12</strong> <br> 
        4/14
    </td>
    <td style="text-align: left;">
        <strong>TBD</strong><br><br>
         Exploring other advanced design topics, such as maybe Altium AutoRoute, Ethernet, RS485, PCB Antenna Design, DDR Memory, Flex PCB Design, and kW Power Designs
        <br><br>
        
    </td>
    <td>
    </td>
    <td class="lab">
    </td>
    <td>
    </td>
    <td>
        Project Assembly
    </td>
</tr><!--kg-card-end: html--><!--kg-card-begin: html--><tr>
    <td class="week">
        <strong>13</strong> <br> 
        4/21
    </td>
    <td style="text-align: left;">
        <strong>Project Presentations</strong>
    </td>
    <td>
    </td>
    <td class="lab">
    </td>
    <td>
    </td>
    <td>
    </td>
</tr><!--kg-card-end: html--></tbody></table>
