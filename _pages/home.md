---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---
<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}

#about-me {
    margin-bottom: 100px;
}
#schedule {
    margin-bottom: 100px;
    
}
#sponsors {
    margin-bottom: 100px;
#register {
    margin-bottom: 20px;
    margin-top: 20px;
}
</style>


<div class="container">
<div class="row" style="text-align: center;">
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" width="100%"/>
</div>
</div>
<br/>

<div style="text-align: center;">
<h2> It's Time to Build the Scientific Tech Stack </h2>
</div>
<div id="register" style="text-align: center;">
<a href="https://airtable.com/apptAi2tFe7I5lDvn/shrMx9j7mKJwnxd0" target="_blank"><button class="btn btn-success btn-lg">Register to SciOS!</button></a>
</div>

<div id="about-me">

  
  The Scientific Coordination Infrastructure and Operating Systems Workshops (SciOS) is a 4 day event bringing together open science deep infrastructure technicians and engineers to collaborate on shared solutions, standards, and paths forward for a technology-based scientific ecosystem that enables FAIR, collaborative, AI-enhanced, open science practices.

  SciOS is organized as a collaboration between [Protocol Labs](protocol.io), [DeSci Labs](desci.com), and the projects and organizations that take lead on tracks and workshops.
</div>


<div id=schedule>
<h2> Schedule </h2>
<h4> Day one, February 26th </h4>
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>FAIR data and Semantic Publishing </b></h4>
<a href="https://gofairfoundation.org" target="_blank"><button class="btn btn-success btn-sm">GoFAIR</button></a>
<a href="https://desci.com/" target="_blank"><button class="btn btn-success btn-sm">DeSci Labs</button></a>
<a href="https://csensemakers.com/" target="_blank"><button class="btn btn-success btn-sm">Common Sensemakers</button></a>

<b>Track Leads:  </b>
<i>Erik Schultes, GoFAIR foundation | Erik Van Winkle, DeSci Labs | Ronen Tamari, Common Sensemakers</i>

Description Coming soon. 

</div>
</div>
</div>

#### Day Two, Febrary 27th
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>DID and Permissions</b></h4>
<a href="https://www.holonym.id/" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a>

<b>Track Lead:</b>
<i>Shady el Damaty, Holonym</i>

Description coming soon. 
</div>
</div>
</div>
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Compute over Data</b></h4>
<a href="https://docs.bacalhau.org/" target="_blank"><button class="btn btn-success btn-sm">Bacalhau</button></a>

<b>Track Lead:</b>
<i>David Aronchick</i>

Description coming soon. 

</div>
</div>
</div>

#### Day Three, Febrary 28th
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Funding and Incentive Design</b></h4>
<a href="https://www.drips.network/" target="_blank"><button class="btn btn-success btn-sm">drips.network</button></a>
<a href="https://gridcoin.us/" target="_blank"><button class="btn btn-info btn-sm">gridcoin</button></a>

<b>Track Leads:  </b>
<i> Andrew, drips.network</i>

Coming soon. 
</div>
</div>
</div>
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Open State Data Networks</b></h4>
<a href="https://www.desci.com/" target="_blank"><button class="btn btn-success btn-sm">Coming soon</button></a>

<b>Track Leads:  </b>
<i> Coming Soon </i>

Coming soon. 
</div>
</div>
</div>

#### Day Four, Febrary 29th
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>AI in Open Science</b></h4>
<a href="https://decentralized.nevermined.io/" target="_blank"><button class="btn btn-success btn-sm">Nevermined</button></a>

<b>Track Leads:</b>
<i>Don Gossen, Nevermined | Levi, CoopHive </i>

Coming Soon
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Mapping the Ecosystem and Hack</b></h4>
<a href="https://numfocus.org/" target="_blank"><button class="btn btn-success btn-sm">NumFOCUS</button></a>
<a href="https://www.lateral.io/" target="_blank"><button class="btn btn-info btn-sm">Lateral</button></a>

<b>Track Leads:</b>
<i>Jon Starr, NumFOCUS | Martin, lateral.io</i>

Coming Soon
</div>
</div>
</div>

</div>

<div id=sponsors>
## Sponsors
<div class="jumbotron" style="background-color: whitesmoke;">
<div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
 {% for funder in site.data.funders %}<a href="{{ funder.url }}" target="_blank"><img src='{{ site.url }}{{ site.baseurl }}/images/{{ funder.image }}' style='max-height: 80px; max-width: 200px; margin: 1%'/></a>{% endfor %}
  </div>
 </div> 

<div id="register" style="text-align: center;">
<a href="2024SciOS_Funding.pdf" target="_blank"><button class="btn btn-success btn-lg">Fund this Initiative</button></a>
</div>
 <p>Sponsors help us to make this event great, including setting up the event, providing ongoing management of the work products that come out of the sessions and building</p>
</div>

  
