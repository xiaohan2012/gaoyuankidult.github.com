---
layout: post
title: "Latex Integration Test"
description: ""
category: 
tags: [Math]
---
{% include JB/setup %}
***This simple blog is intended to show what kind of $\LaTeX$ code you need to write to jekyll post.*** 

## Here is the code example that I wrote in the .md file.

<pre>
<code>
inv(\begin{bmatrix} 5 &amp; 8 &amp; 1 \\ &amp; 9 &amp; 2 \\ 4 &amp; 6 &amp; 3 \end{bmatrix})=inv(\left\{ 5,8,1,9,2,4,6,3\right\} )\\ inv(\begin{bmatrix} 5 &amp; 8 &amp; 1 \\ 4 &amp; 9 &amp; 2 \\ &amp; 6 &amp; 3 \end{bmatrix})=inv(\left\{ 5,8,1,4,9,2,6,3\right\} )
</code>
</pre>

## Here is the result.
<p>$$ inv(\begin{bmatrix} 5 &amp; 8 &amp; 1 \\ &amp; 9 &amp; 2 \\ 4 &amp; 6 &amp; 3 \end{bmatrix})=inv(\left\{ 5,8,1,9,2,4,6,3\right\} )\\ inv(\begin{bmatrix} 5 &amp; 8 &amp; 1 \\ 4 &amp; 9 &amp; 2 \\ &amp; 6 &amp; 3 \end{bmatrix})=inv(\left\{ 5,8,1,4,9,2,6,3\right\} ) $$</p>

## If your problem is that a single $ does not work. Probably you need to include following code into your to-be-included js file.
<pre>
<code>
&ltscript type="text/x-mathjax-config"&gt
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
&lt/script&gt
</code>
</pre>
