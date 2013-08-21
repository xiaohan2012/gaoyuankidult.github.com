---
layout: post
title: "Weighted Graph Compression for Multi agent Robot Systems"
description: ""
category: 
tags: []
---
{% include JB/setup %}
Hannu Toivonen and his partners introduced their researches in the paper

“Compression of Weighted Graphs”. Motivated by graph problems which contain

large amount of vertices, the authors formalize problems of weighted graph 

mathematically and then propose several algorithms to deal with graph compression. 

According to the paper, the compression algorithms of weighted graph have been 

widely used in the social analysis and biological analysis. By considering the 

properties of the compression algorithms of weighted graphs, I would like to suggest 

that these algorithms have a possibility of being applied in multi-agent systems in 

robotics, because these algorithms can enable multi-agent systems to be power-saving, 

system-wide efficient and applicable on today’s robot devices.

This feature of reducing the vertices of a weighted graph contributes to 

reducing computational power under certain robot path-planning environments, for 

example, when robots want to mainly use its power to process a large image.

Normally, the path-planning algorithms require building a rapidly exploring random 

tree which contains a randomized graph. For precise path-planning algorithms, nodes 

are connected with weighted graph in which a large set of vertices is included.

Although this huge amount of vertices may lead to a precise and smooth planning 

result, actually sometimes it may also cause the algorithms to use out of all the 
computational resources. By providing a stable algorithm of compressing weighted 
graph, the path-planning algorithms can reduce total amount of its vertices. This 
ability can enable the searching process in path-planning algorithms to focus on 

