---
published: true
layout: post
categories: node express ejs TwitchAPI
img: twitch-analyzer.jpg
title: Twitch Analyzer
---
<a target="_blank"  href="https://twitch-analyzer.herokuapp.com/" class="btn btn-primary">Demo</a>
<a target="_blank"  href="https://github.com/pateldhruv1993/twitch-analyzer" class="btn btn-primary">GitHub Link</a>

<h1>What is this?</h1>
A website I made using node.js, express, ejs, Plotly.js, TwitchAPI and couple other smaller framework. The reason for me making this is that I wanted to learn node and express along with messing around with data.

I started with Node.js frameworks at first to collect data as its quite easy to get up and running with node. Once I had the data, I wanted to plot it so I thought might as well learn express and just plot the data on a local website. I also made an API end point so my local website can make requests to the server and constantly keep updating the data on a chart if I want it to.

Although I've implemented the most important things(especially backend features) that I wanted, there are still some smaller things I'd like to add so consider it WIP.

<h1>Images:</h1>
<ul>
<li>Steam Viewers Chart
<img width="100%" src="{{site.baseurl}}/images/twitch-analyzer-viewer-chart.gif">
</li>
<li>Chat Count Messages Chart
<img width="100%" src="{{site.baseurl}}/images/twitch-analyzer-chat-chart.gif">
</li>
</ul>
