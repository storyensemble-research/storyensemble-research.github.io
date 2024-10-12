---
layout: default
---


Hello!

I wrote this document for the UIST'24 workshop attendees. 

<strong>Motivation</strong>. 
The system has many features, but we have limited time to go through them all during the workshop. I hope this document can answer any questions for those who want more explanations as they go through the prototyping session.

---

<h3 style="text-align:center">FAQs</h3>

<strong>Q. What is it?</strong>

<span class="highlight">StoryEnsemble</span> is an interactive system designed to help users <i>rapidly</i> <strong>explore</strong> and <i>flexibly</i> <strong>iterate</strong> on personas, problem statements, solutions, and storyboards.

<strong>Q. What does it do ?</strong>

<!-- <strong>Design Consideration: Manual vs AI-driven Workflow</strong><br> -->
You can use AI to generate ideas persona, problem statement, it is designed to allow designers to not use AI at all and still leverage the design thinking procss.

---

<h2>Table of Contents</h2>
<ol>
  <li>Basic</li>
  <ol>
    <li><a href="#components">UI & Components</a></li>
    <li><a href="#components">Node</a></li>
  </ol>
  <li>Advanced</li>
  <ol>
    <li><a href="#propagation">Propagation Mechanisms</a></li>
  </ol>
  <li>Workflow Examples</li>
  <ol>
    <li></li>
    <li></li>
  </ol>
</ol>


<h2 id="components">I. Basic Components: 4 Types of Nodes - Persona, Problem, Solution, and Storyboard</h2>

<p>
  StoryEnsemble offers four types of nodes, each corresponding to a stage of the design thinking process: (1) persona [Empathize]; (2) problem [Define]; (3) solution [Ideate]; and (4) storyboard [Prototype]. 
</p>

<p>
(A) includes buttons to generate chains of ideas (Start brainstorming) or add individual nodes (Add empty node). The system includes nodes for different ideas: (B) context node for grouping and labeling ideas, (C) persona nodes, (D) problem nodes, (E) solution nodes, and (F) a storyboard node. (G) Edges map the relationships and dependencies between different ideas, showing how ideas exert influence on dependent ideas throughout the system.
</p>

<div class="img-container">
  <img src="/assets/img/storyensemble/system.png"/>
</div>

---
<h2 id="node">2. Node (e.g., Persona)</h2>

The persona node helps users define target users through attributes like name, location, needs, and challenges. These can be filled in manually or generated using AI to assist with brainstorming user profiles.

<div class="img-container" style="width:70%; text-align:center">
  <img src="/assets/img/storyensemble/persona-node.png"/>
</div>
<p>
 Persona node: An (A) illustrative image, (B) name and (C) attributes which represent a persona. Each node has (D) a toolbar for editing and creating related nodes.
</p>




---

<h2 id="propagation">Propagation Mechanisms</h2>

### Forward Propagation

<p>
  Users can cascade changes from an earlier design stage to a later stage (e.g., persona to problem statement) by (A) connecting the nodes with an edge or updating a connected node (Zero-waste Zach, see Fig. \ref{fig:teaser}) and (B) refreshing the later artifact to generate (C) an updated artifact.
</p>

<div class="img-container" style="width:70%; text-align:center">
  <img src="/assets/img/storyensemble/forward-propagation.png"/>
</div>

### Backward Propagation

<p>
  Users can cascade changes from a later design stage to an earlier stage (e.g., extract problem statement from a solution). By (A) connecting a solution to a problem, (B) a notification is displayed to refresh the problem which (C) updates the problem according to the solution.
</p>

<div class="img-container" style="width:70%; text-align:center">
  <img src="/assets/img/storyensemble/backward-propagation.png"/>
</div>



{% if site.video %}

## Video Demo

See <span class="sys-name">StoryEnsemble</span> in action in this Video Demo.

<div class="video-wrapper">
  <iframe src="{{site.video}}&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% endif %}

{% if site.bibtex %}
------

## Bibtex

<pre>
@inproceedings{suh2023sensecape,
  author = {Suh, Sangho and Min, Bryan and Palani, Srishti and Xia, Haijun},
  title = {Sensecape: Enabling Multilevel Exploration and Sensemaking with Large Language Models},
  year = {2023},
  isbn = {9798400701320},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://dl.acm.org/doi/10.1145/3586183.3606756},
  doi = {10.1145/3586183.3606756},
  booktitle = {The 36th Annual ACM Symposium on User Interface Software and Technology},
  keywords = {Large Language Model, Multilevel Abstraction, Visualization},
  location = {San Francisco, CA, USA},
  series = {UIST '23}
}
</pre>

{% endif %}