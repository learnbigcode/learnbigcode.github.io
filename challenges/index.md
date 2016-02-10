---
layout: page
title: "Challenges"
description: "Big Code Challenges"
tags: [learning, challenges, big code]
comments: false
share: false
---

Typically a challenge consists of a dataset and a task that should be performed and evaluated with a specific dataset. The goal of challenges is for the research community to define important problems on which multiple solutions should appear. Most challenges already include some system as a baseline and the goal is to produce a better working (e.g. more precise) system. Challenges should be self-contained -- it should take a few hours for a newcomer to implement a naive solution to a challenge.

Here is a list of proposed challenges:

<div class="highlightitem">
<h2>JavaScript code completion challenge</h2>

<p>A number of works in the recent years create statistical code completion systems. This challenge represent a difficult cases where JavaScript is a target language. Furthermore, the lack of static type information makes code completion a challenge with existing non-statistical techniques.</p>

<p>The goal is to create a tool that can predict JavaScript code. One task is for predicting APIs and object fields as in the classical code completion setting, but another task proposes to complete arbitrary program elements such as numeric and string constants.<br>
Dataset used: <a href="/datasets#javascript-asts">[JavaScript ASTs]</a><br>
More information: [coming]
</p>
</div>

<div class="highlightitem">
<h2>Determining targets of virtual function calls in stripped binariesc</h2>

<p>As most software today reaches most users in the form of stripped binaries, without any source code or debug symbols, the need to be able to understand the inner workings of software by analyzing and examining the binary becomes more prominent than ever before. The first step in understanding a piece of software is determining the control flow in the binary. This task becomes extremely difficult when virtual functions are used since all static knowledge pretaining to the target is lost.</p>

<p>The goal is to create a tool that can statically determine the targets of virtual function calls in stripped binaries. As the target can be directly deduced from the runtime type of the object used in the call, the basic task of the tool should be to determine the types of objects in the binary. Furthermore, since each object is possibly an instance of one of several types, a complete answer is not a single type for each object but a set of possible types for the object.<br>
Dataset used: <a href="/datasets#estimatingTypesDataset">[Estimating Types in Stripped Binaries Dataset]</a><br>
</p>
</div>

<div class="highlightitem">
<h2>Establishing similarity of code fragments</h2>

<p>Code similarity is a central challenge in many programming related applications, such as code search, automatic translation, and programming education.<p>

<p>There are many approaches for establishing code similarity and clone detection. 
However, most of these cannot capture similarity across programs using different APIs or algorithms, let alone programming languages.
Furthermore, in some cases, equivalence is not what we are looking for.</p> 

<p>The goal is to capture connections between code fragments, such as semantic similarity or relatedness, which are more relaxed notions than strict equivalence.<p>

<p>Dataset used: <a href="/datasets#like2dropsData">[Like2DropsData]</a></p>
<p>Crowd-sourcing system used to collect data: <a href="http://like2drops.com">[Like2Drops]</a><br></p>
</div>
