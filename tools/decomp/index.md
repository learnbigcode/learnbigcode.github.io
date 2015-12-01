---
layout: page
title: "Decompilation and Deobfuscation Tools"
description: "Big Code Challenges"
tags: [learning, tools, decompilation, deobfuscation]
comments: false
share: false
---

Add your decompilation and deobfuscation tools by creating a pull request <a href="https://github.com/learnbigcode/learnbigcode.github.io/tree/master/tools/decomp">here</a>.

<div class="highlightitem">
<h2>JSNice</h2>
<a href="http://jsnice.org/">JSNice</a> is a statistical predictor of variable names and type annotations for JavaScript developed at ETH Zurich. The tool is useful to deminify JavaScript code.
JSNice works by framing the deobfuscation as structured prediction using <a href="https://en.wikipedia.org/wiki/Conditional_random_field">Conditional Random Fields</a>. A general framework extensible to other languages and similar problems is available at
<a href="http://nice2predict.org/">nice2predict.org</a>. Nice2Predict also includes visualization of the inference procedure.<br><br>

<a href="http://jsnice.org/">[jsnice.org]</a> <a href="http://nice2predict.org/">[nice2predict.org]</a> <a href="http://www.srl.inf.ethz.ch/papers/jsnice15.pdf">[paper @ POPL 2015]</a> <a href="http://www.srl.inf.ethz.ch">[developers' website]</a> <a href="https://github.com/eth-srl/Nice2Predict">[github]</a>
</div>
