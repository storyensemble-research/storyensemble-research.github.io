---
layout: default
---

## Abstract

Designers use storytelling — and storyboards in particular — to rapidly explore and communicate persona-problem-solution spaces. However, time constraints often limit the ability to ideate broadly and to get timely user feedback for iteration. To gather a comprehensive list of challenges, we conducted a formative study with 15 participants—including UX practitioners, students, and instructors. We identified various needs, including supporting iteration and ideation at any design phase. Based on the findings, we developed StoryEnsemble, a system that integrates generative AI within a node-link interface to enable fluid, iterative workflows and generates storyboards that illustrate the user's choices for personas, problems, and solutions. A user study with 10 participants from similarly diverse backgrounds demonstrates that StoryEnsemble enables rapid exploration and flexible iteration. This work advances our understanding of how AI can support dynamic, flexible, and creative workflows, and highlights the opportunities and challenges of infusing AI into traditional design processes.

---

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/qSh0tE8D-lE?si=mQeA7gFYyAAb9jNV&amp;start=11&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<h2 style="text-align:center">Quick Questions</h2>

<h3>Q. What is it?</h3>

<span class="highlight">StoryEnsemble</span> is an interactive system designed to help users <i>rapidly</i> <strong>explore</strong> and <i>flexibly</i> <strong>iterate</strong> on personas, problem statements, solutions, and storyboards. 

<h3>Q. Do we have to use AI?</h3>

<strong>No</strong>. You can use it only when needed or not at all entirely. 

- You can add your own ideas. Even create storyboards youself.
- For example, you can upload a photo of your sketches to create a storyboard.

---

<!-- <h2>Table of Contents</h2>
<ol>
  <li>Basic</li>
  <ol>
    <li><a href="#components">Basic Components</a></li>
    <li><a href="#components">Node: Content Structure & Features</a></li>
  </ol>
  <li>Advanced</li>
  <ol>
    <li><a href="#propagation">Propagation Mechanisms</a></li>
  </ol>
  <li>Workflow Examples</li>
</ol> -->


<!-- <h2>Table of Contents</h2>
<ol>
  <li>Basic Components</li>
  <li>Node: Content Structure & Features</li>
  <li>Workflow Examples</li>
</ol> -->


<h2 id="components">1. Basic Components</h2>

<div style="text-align:-webkit-center">
  <div class="img-container" style="width: 60%">
    <img src="/assets/img/storyensemble/ideo-design-thinking.png"/>
  </div>
</div>
StoryEnsemble offers four types of nodes, each corresponding to a stage of the design thinking process: (1) persona [Empathize]; (2) problem [Define]; (3) solution [Ideate]; and (4) storyboard [Prototype].

<p>
   
</p>

<div style="text-align:-webkit-center">
  <div class="img-container" style="width: 60%; text-align: -webkit-center;">
    <img src="/assets/img/storyensemble/four-nodes.png"/>
  </div>
</div>
The system offers nodes for different ideas: (C) persona nodes, (D) problem nodes, (E) solution nodes, and (F) a storyboard node. (G) Edges map the relationships and dependencies between different ideas, showing how ideas exert influence on dependent ideas throughout the system.

<div style="text-align:-webkit-center">
  <div class="img-container">
    <img src="/assets/img/storyensemble/start-brainstorming.png"  style="border: 1px solid"/>
  </div>
</div>

'Start brainstorming' button on the upper left corner generated chains of ideas shown above. Alternatively, you can click on the 'Add empty node' button to add individual empty nodes. 

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/DRFfpwX5uhQ?si=ReXgCWtw8-pyoV87&amp;start=11&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


---
<h2 id="node">2. Node: Content Structure & Features</h2>

<h3 id="node">2-1. Persona, Problem, and Solution Nodes </h3>

The three nodes---Persona, Problem, and Solution Nodes---are similar in its structure, but they differ in the types of attributes. For example, the persona node helps users define target users through attributes like name, location, needs, and challenges, as shown below.

<div style="text-align:-webkit-center">
  <div class="img-container" style="width:50%; text-align:center">
    <img src="/assets/img/storyensemble/persona-node.png"/>
  </div>
</div>
Persona node: An (A) illustrative image, (B) name and (C) attributes which represent a persona. Each node has (D) a toolbar for editing and creating related nodes.

<div style="text-align:-webkit-center">
  <div class="img-container" style="width:70%; text-align:center">
    <img src="/assets/img/storyensemble/manual.png"/>  
  </div>
</div>
By clicking the "Edit manually" button in the toolbar, users can manually edit the contents of a node using an interface with text fields, as shown in the above figure, with a similar interface applied across all node types.  

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/nDgmP08xUNA?si=2M8aDpFQGpNPBouN&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

These attributes can be filled in manually ("Edit manually") or generated using AI to assist with brainstorming user profiles.

<h3 id="node">2-2. Storyboard Node </h3>

Each storyboard includes (A) a title and multiple frames, where (B) each frame contains a specific type (e.g., Context, Problem, Solution, Resolution), an image, and a caption. Users can (C) open a panel to edit an existing frame or (D) add new frames to expand the narrative. (E) Settings allow users to customize the image style (e.g., digital-art, line-art, comic-book) and regenerate all storyboard images.
<div style="text-align:-webkit-center">
  <div class="img-container" style="width:100%; text-align:center">
    <img src="/assets/img/storyensemble/storyboard-node.png"/>
  </div>
</div>

A pop up panel appears when users click on the edit icon (see Fig. C in the above figure). Using the panel, users can edit a frame's type, description, and caption to regenerate the frame image or all images or remove the frame entirely. 
<div style="text-align:-webkit-center">
  <div class="img-container" style="width:40%; text-align:center">
    <img src="/assets/img/storyensemble/storyboard-edit.png"/>
  </div>
</div>
After users select 'Regenerate image,' the text in the description box is used as prompt to instruct what image gets generated for the frame.

See it in action.
<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/gUZwrPQrZHI?si=2pEjnL1Vw4_WvcDZ&amp;start=9&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---

<h2 id="propagation">Features</h2>

### Revise with AI


This feature allows users to update (A) idea content by providing (B) natural language prompts. (C) AI suggests instructions for iteration, and (D) revised content is automatically underlined for clarity.

<div style="text-align:-webkit-center">
  <div class="img-container" style="width:70%; text-align:center">
    <img src="/assets/img/storyensemble/revise.png"/>
  </div>
</div>

### Fill in Missing Values
This feature supports brainstorming. When you have missing values in any node, you can ask AI to fill in these values. 

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/iDw0wBoQrxw?si=4fvK8G3xoOdZlMVc&amp;start=18&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### Generate More
Users can build on (A) a selected idea by (B) entering their own suggestions or (C) utilizing AI-generated recommendations. The system then generates (D) additional ideas to explore further possibilities.

<div style="text-align:-webkit-center">
  <div class="img-container" style="width:70%; text-align:center">
    <img src="/assets/img/storyensemble/generate-more.png"/>
  </div>
</div>

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/iDw0wBoQrxw?si=33Y0ZQ82EENA_Jnh&amp;start=89&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### View Feedback

You can get AI-generated feedback on any node. 

See it in action.
<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/a577XkirrFQ?si=oEAk6404WaBGpVYm&amp;start=44&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### AI Suggestions
AI suggestions get generated in the revise tab of every node or when users try to generate more. 

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/iDw0wBoQrxw?si=33Y0ZQ82EENA_Jnh&amp;start=89&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### Forward Propagation
Users can cascade changes from an earlier design stage to a later stage (e.g., persona to problem statement) by (A) connecting the nodes with an edge or updating a connected node (Zero-waste Zach) and (B) refreshing the later artifact to generate (C) an updated artifact.

<div style="text-align:-webkit-center">
  <div class="img-container" style="width:60%; text-align:center">
    <img src="/assets/img/storyensemble/forward-propagation.png"/>
  </div>
</div>

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/iDw0wBoQrxw?si=zkPWRR_yF3hhsxxe&amp;start=140&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Backpropagation


Users can cascade changes from a <i>later</i> design stage to an <i>earlier</i> stage (e.g., extract problem statement from a solution). 

By (A) connecting a solution to a problem, (B) a notification is displayed to refresh the problem which (C) updates the problem according to the solution.

<div style="text-align:-webkit-center">
  <div class="img-container" style="width:60%; text-align:center">
    <img src="/assets/img/storyensemble/backward-propagation.png"/>
  </div>
</div>

See it in action below.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/iDw0wBoQrxw?si=AuUHBRPe90DjulIK&amp;start=57&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---
<h2>Extra Features</h2>

<h3>Download canvas & storyboard images</h3>
You can download canvas & storyboard iamges. We ask you to upload it in the assigne GDrive folder at the end of the prototype session.

See it in action.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/_vdU11FSbIo?si=mmBsoTYX_PDE2yg_" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


---
<h2>3. Workflow Examples</h2>

This simple workflow below shows uploading images to each frame and also being able to use AI to generate images and set their style.
<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/gUZwrPQrZHI?si=hL4eq9XU67WisDna&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

The relatively more complex workflow below shows a number of techniques.

- It shows using AI to fill in missing values. 
- It shows generating a storyboard from a solution node.
- It shows a backpropagation.
- It also shows more feature to generate more solutions and more personas. 
- It also shows connecting a node to another and propagate changes. 
<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/iDw0wBoQrxw?si=jkapov4PYZwxoixB&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

This workflow shows how you can steer solution ideas from a problem node and also steer the generation of images in a storyboard.
<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/Q2TumFHae2Y?si=2la1tJ5GN9z9MYvv&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

This workflow shows how you can brainstorm feature ideas with AI.
<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/73yv1CreIGI?si=ASOiDVz-ZhDqqqu0&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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