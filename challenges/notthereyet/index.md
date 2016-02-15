---
layout: page
title: "Challenge candidates"
description: "Incomplete Big Code Challenges"
tags: [learning, challenges, big code, incomplete]
comments: false
share: false
---

Well defined challenges are <a href="/challenges">here</a>. The following list is not yet well defined. To add an item below, create a pull request <a href="https://github.com/learnbigcode/learnbigcode.github.io/tree/master/challenges/notthereyet">here</a>.

A list of proposed challenges that are still incomplete in their description, training or evaluation data:

<div class="highlightitem">
<h2>JavaScript code completion challenge</h2>

<p>A number of works in the recent years create statistical code completion systems. This challenge represent a difficult cases where JavaScript is a target language. Furthermore, the lack of static type information makes code completion a challenge with existing non-statistical techniques.</p>

<p>The goal is to create a tool that can predict JavaScript code. One task is for predicting APIs and object fields as in the classical code completion setting, but another task proposes to complete arbitrary program elements such as numeric and string constants.<br>
Dataset used: <a href="/datasets#javascript-asts">[JavaScript ASTs]</a><br>
More information: [coming]
</p>
</div>

<div class="highlightitem">
<h2>Determining targets of virtual function calls in stripped binaries</h2>

<p>As most software today reaches most users in the form of stripped binaries, without any source code or debug symbols, the need to be able to understand the inner workings of software by analyzing and examining the binary becomes more prominent than ever before. The first step in understanding a piece of software is determining the control flow in the binary. This task becomes extremely difficult when virtual functions are used since all static knowledge pretaining to the target is lost.</p>

<p>The goal is to create a tool that can statically determine the targets of virtual function calls in stripped binaries. As the target can be directly deduced from the runtime type of the object used in the call, the basic task of the tool should be to determine the types of objects in the binary. Furthermore, since each object is possibly an instance of one of several types, a complete answer is not a single type for each object but a set of possible types for the object.<br>
Dataset used: <a href="/datasets#estimatingTypesDataset">[Estimating Types in Stripped Binaries Dataset]</a><br>
</p>
</div>

<div class="highlightitem">
<h2>Establishing similarity of code fragments</h2>

<p>Code similarity is a central challenge in many programming related applications, such as code search, automatic translation, and programming education.</p>

<p>There are many approaches for establishing code similarity and clone detection. 
However, most of these cannot capture similarity across programs using different APIs or algorithms, let alone programming languages.
Furthermore, in some cases, equivalence is not what we are looking for.</p> 

<p>The goal is to capture connections between code fragments, such as semantic similarity or relatedness, which are more relaxed notions than strict equivalence.</p>

<p>Dataset used: <a href="/datasets#like2dropsData">[Like2DropsData]</a></p>
<p>Crowd-sourcing system used to collect data: <a href="http://like2drops.com">[Like2Drops]</a><br></p>
</div>


<div class="highlightitem" id="methodnaming">
<h2>Method Naming Challenge</h2>

<p>Developers pick the names of variables, classes and methods to reflect important aspects of their functionality.
Learning to name snippets of methods is an important and hard machine learning problem and is a first step
towards "understanding" what source code does from a machine learning lens.</p>

<h4>Challenge Description</h4>
<p>The goal of the challenge is to create a system that can predict the name of a method body, given solely its body.
No features external to the body (e.g. the method signature) are included.
We provide a training set that contains training pairs and a test set to perform evaluation.
The evaluation consists of computing the <a href="https://en.wikipedia.org/wiki/F1_score">F1 score</a> over the subtokens 
of the predicted method name, compared to the actual name.
Two baselines (tf-idf) and a convolutional attentional neural network are provided in the
related publication.</p>

<p>Dataset <a href="/datasets#methodnaming">[Method Naming Dataset]</a></p>
<p>Related publication: <a href="http://arxiv.org/abs/1602.03001">[ArXiV]</a></p>
</div>
