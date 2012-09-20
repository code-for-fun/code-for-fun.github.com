---
layout: page
title: Hacklog
comments: off
tagline: Algorithms, Data structures, Operating System internals.
---
{% include JB/setup %}
In this blog, we will discuss all the basic algorithms and data structures. Also,
we will go through Operating System internals. We will start with cousera algorithms-I
course. Intermettently we will also go through MIT 6.828 - Operating Systems Engineering course.

## Algorithms - I

Part I focuses on elementary data structures, sorting, and searching. Topics include union-find, binary search, stacks, queues, bags, insertion sort, selection sort, shellsort, quicksort, 3-way quicksort, mergesort, heapsort, binary heaps, binary search trees, red-black trees, separate chaining and linear probing hash tables, Graham scan, and kd-trees.

## MIT 6.828 - Operating Systems Engineering

This course aims at understanding operating system by looking at code of JOS operating system as well as Xv6. It involves necessity to understand and code to write our own operating system.

# Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

