---
layout: page
title: "Libraries for Tools"
description: "Big Code Challenges"
tags: [learning, tools, big code]
comments: false
share: false
---

This is a list of useful libraries for developing new "Big Code" tools.

Add your library by creating a pull request <a href="https://github.com/learnbigcode/learnbigcode.github.io/tree/master/tools/libs">here</a>.

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
<h2>bigcode-tools</h2>

bigcode-tools is a suite of tools to fetch, parse and process source code.
It also contains utility to generate vector embeddings from source code.
It currently supports Python 2 and 3, Java and JavaScript.
The tools are designed to be compatible with <a href="http://www.srl.inf.ethz.ch/py150.php">py150</a> and <a href="http://www.srl.inf.ethz.ch/js150.php">js150</a> datasets.


<ul>
<li><a href="https://github.com/tuvistavie/bigcode-tools">bigcode-tools main repository</a></li>
<li><a href="https://github.com/tuvistavie/bigcode-tools/blob/master/doc/tutorial.md">bigcode-tools tutorial</a></li>
</ul>
<br/><span class="tags">Tags: #codeanalysis #embeddings</span>
</div>
