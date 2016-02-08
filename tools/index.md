---
layout: page
title: "Tools"
description: "Big Code Challenges"
tags: [learning, tools, big code]
comments: false
share: false
---

Add your program analysis tools by creating a pull request <a href="https://github.com/learnbigcode/learnbigcode.github.io/tree/master/tools">here</a>.

<div class="highlightitem">
<h2>JSNice</h2>
<a href="http://jsnice.org/">JSNice</a> is a statistical predictor of variable names and type annotations for JavaScript developed at ETH Zurich. The tool learns a probabilistic type inference procedure for JavaScript.<br>

The learning, the type inference and the variable name reconstruction are framed as structured prediction using <a href="https://en.wikipedia.org/wiki/Conditional_random_field">Conditional Random Fields</a>. A general framework extensible to other languages and similar problems is available at
<a href="http://nice2predict.org/">nice2predict.org</a>. Nice2Predict also includes visualization of the inference procedure.<br><br>

<a href="http://jsnice.org/">[jsnice.org]</a> <a href="http://nice2predict.org/">[nice2predict.org]</a> <a href="http://www.srl.inf.ethz.ch/papers/jsnice15.pdf">[paper @ POPL 2015]</a> <a href="http://www.srl.inf.ethz.ch">[developers' website]</a> <a href="https://github.com/eth-srl/Nice2Predict">[github]</a>
<br><span class="tags">Tags: #staticanalysis #deobfuscation</span>
</div>

<div class="highlightitem">
<h2>SLANG</h2>

SLANG is a code completion tool for Java that is intended to complete APIs. A tool trained on Android applications is available and evaluated on predicting what next Android API should be written in a program.<br><br>

<a href="https://drive.google.com/file/d/0B0wMwmX05Ri7a056TllETHFEelU/view?usp=sharing">[SLANG tool]</a> <a href="http://www.srl.inf.ethz.ch/papers/pldi14-statistical.pdf">[paper]</a> <a href="http://www.srl.inf.ethz.ch/">[author website 1]</a> <a href="http://www.cs.technion.ac.il/~yahave/">[author website 2]</a>
<br><span class="tags">Tags: #staticanalysis #codecompletion</span>
</div>

<div class="highlightitem">
<h2>codemining-*</h2>

codemining-* is a suite of Java-based tools for tokenizing, parsing Java code. 
The repository also contains code to analyze Git-based repositories.

<ul>
<li> <a href="https://github.com/mast-group/codemining-core">codeminining-core</a> contains code for tokenizing Java, JavaScript, Python, C and C++ in the JVM.</li>

<li> <a href="https://github.com/mast-group/codemining-treelm">codemining-treelm</a> contains Java AST parsing and tree-level language models.</li>

<li> <a href="https://github.com/mast-group/commitmining-tools">commitmining-tools</a> contains tools for traversing a Git repository, its history and possibly its files.</li>
</ul>
<br/><span class="tags">Tags: #codeanalysis</span>
</div>

<div class="highlightitem">
<h2>TASSAL: Tree-based Autofolding Software Summarization ALgorithm</h2>
TASSAL is a tool for the automatic summarization of source code using autofolding. Autofolding automatically creates a summary of a source code file by folding non-essential code and comment blocks. 

<br/><a href="https://github.com/mast-group/tassal">[GitHub Repository]</a> <a href="https://code-summarizer.herokuapp.com/">[demo]</a>
<br/><span class="tags">Tags: #summarization</span>
</div>


<div class="highlightitem">
<h2>Naturalize</h2>
Naturalize is a tool that learns and suggest coding conventions (such as variable names) to improve the stylistic consistency of your codebase.

<br/><a href="https://github.com/mast-group/naturalize">[GitHub Repository]</a> <a href="http://groups.inf.ed.ac.uk/naturalize/">[Project page]</a>
<br/><span class="tags">Tags: #codingconventions</span>
</div>

<div class="highlightitem">
<h2>Esty</h2>
Esty is a tool aimed at estimating the types of objects in stripped binaries developed at the Technion Israel. 
The tool uses a combination of static analysis and machine learning to learn usage patterns of objects instances of different types and predict the most likely types of objects for which the type is unknown.
The leraning and prediction use <a href="https://en.wikipedia.org/wiki/Language_model">Statistical Language Models</a> based on the <a href="https://en.wikipedia.org/wiki/Prediction_by_partial_matching">Prediction by Partial Match</a> algorithm.
The tool eventually determines the most likely targets for virtual function calls using the most likely types of the relevant objects, thus statically filling the gaps in the call graphs of stripped binaries.
<br><br>

<a href="http://omerkatz.cswp.cs.technion.ac.il/wp-content/uploads/sites/28/2016/01/p313-katz.pdf">[paper @ POPL 2016]</a> <a href="http://omerkatz.cswp.cs.technion.ac.il">[developer/author website]</a>
<br><span class="tags">Tags: #staticanalysis #binaryanalysis #reverseengineering #estimatingtypes</span>
</div>

If you have a tool you would like to list here, head to <a href="https://github.com/learnbigcode/learnbigcode.github.io/tree/master/tools">the github page</a> and create a pull request with your suggestion.

