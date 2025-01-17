---
keywords: fastai
title: VOCAB!
nb_path: _notebooks/2022-08-30-Python_vocab.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-08-30-Python_vocab.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Variables">Variables<a class="anchor-link" href="#Variables"> </a></h1><p>A variable is created the moment you first assign a value to it.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="mi">5</span>
<span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;Ananya&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">y</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>5
Ananya
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Data-Types">Data Types<a class="anchor-link" href="#Data-Types"> </a></h1><p>Variables can store data of different types, and different types can do different things.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="mi">5</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">type</span><span class="p">(</span><span class="n">x</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class &#39;int&#39;&gt;
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Lists">Lists<a class="anchor-link" href="#Lists"> </a></h1><p>Lists are used to store multiple items in a single variable.
Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are Tuple, Set, and Dictionary, all with different qualities and usage.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">thislist</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;apple&quot;</span><span class="p">,</span> <span class="s2">&quot;banana&quot;</span><span class="p">,</span> <span class="s2">&quot;cherry&quot;</span><span class="p">]</span>
<span class="nb">print</span><span class="p">(</span><span class="n">thislist</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[&#39;apple&#39;, &#39;banana&#39;, &#39;cherry&#39;]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Dictionaries">Dictionaries<a class="anchor-link" href="#Dictionaries"> </a></h1><p>Dictionaries are Python's implementation of a data structure that is more generally known as an associative array. A dictionary consists of a collection of key-value pairs. Each key-value pair maps the key to its associated value</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Algorithms">Algorithms<a class="anchor-link" href="#Algorithms"> </a></h1><p>Python algorithms are a set of instructions that are executed to get the solution to a given problem. Since algorithms are not language-specific, they can be implemented in several programming languages. No standard rules guide the writing of algorithms</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">myfamily</span> <span class="o">=</span> <span class="p">{</span>
  <span class="s2">&quot;child1&quot;</span> <span class="p">:</span> <span class="p">{</span>
    <span class="s2">&quot;name&quot;</span> <span class="p">:</span> <span class="s2">&quot;Emil&quot;</span><span class="p">,</span>
    <span class="s2">&quot;year&quot;</span> <span class="p">:</span> <span class="mi">2004</span>
  <span class="p">},</span>
  <span class="s2">&quot;child2&quot;</span> <span class="p">:</span> <span class="p">{</span>
    <span class="s2">&quot;name&quot;</span> <span class="p">:</span> <span class="s2">&quot;Tobias&quot;</span><span class="p">,</span>
    <span class="s2">&quot;year&quot;</span> <span class="p">:</span> <span class="mi">2007</span>
  <span class="p">},</span>
  <span class="s2">&quot;child3&quot;</span> <span class="p">:</span> <span class="p">{</span>
    <span class="s2">&quot;name&quot;</span> <span class="p">:</span> <span class="s2">&quot;Linus&quot;</span><span class="p">,</span>
    <span class="s2">&quot;year&quot;</span> <span class="p">:</span> <span class="mi">2011</span>
  <span class="p">}</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Sequence">Sequence<a class="anchor-link" href="#Sequence"> </a></h1><p>In Python, sequence is the generic term for an ordered set. There are several types of sequences in Python, the following three are the most important. Lists are the most versatile sequence type.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Selection">Selection<a class="anchor-link" href="#Selection"> </a></h1><p>In Python, the selection statements are also known as decision making statements or branching statements. The selection statements are used to select a part of the program to be executed based on a condition.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Iteration">Iteration<a class="anchor-link" href="#Iteration"> </a></h1><p>Repetitive execution of the same block of code over and over is referred to as iteration. There are two types of iteration: Definite iteration, in which the number of repetitions is specified explicitly in advance.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Expressions">Expressions<a class="anchor-link" href="#Expressions"> </a></h1><p>In programming language terminology, an “expression” is a combination of values and functions that are combined and interpreted by the compiler to create a new value, as opposed to a “statement” which is just a standalone unit of execution and doesn't return anything.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Comparison-Operators">Comparison Operators<a class="anchor-link" href="#Comparison-Operators"> </a></h1><p>A comparison operator in python, also called python relational operator, compares the values of two operands and returns True or False based on whether the condition is met</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Booleans-Expressions-and-Selection">Booleans Expressions and Selection<a class="anchor-link" href="#Booleans-Expressions-and-Selection"> </a></h1><p>A boolean expression (or logical expression) evaluates to one of two states true or false. Python provides the boolean type that can be either set to False or True. Many functions and operations returns boolean objects. The not keyword can also be used to inverse a boolean type.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Charcters">Charcters<a class="anchor-link" href="#Charcters"> </a></h1><p>Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters. However, Python does not have a character data type, a single character is simply a string with a length of 1. Square brackets can be used to access elements of the string.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Strings">Strings<a class="anchor-link" href="#Strings"> </a></h1><p>Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters. However, Python does not have a character data type, a single character is simply a string with a length of 1. Square brackets can be used to access elements of the string.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">a</span> <span class="o">=</span> <span class="s2">&quot;&quot;&quot;HELLO HELLO</span>
<span class="s2">HELLOHELLO</span>
<span class="s2">HELLOHELLOHELLO</span>
<span class="s2">&quot;&quot;&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="n">a</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>HELLO HELLO
HELLOHELLO
HELLOHELLOHELLO

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">a</span> <span class="o">=</span> <span class="s2">&quot;Hello&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="n">a</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Length-Concatenation">Length Concatenation<a class="anchor-link" href="#Length-Concatenation"> </a></h1><p>Concatenation means joining strings together end-to-end to create a new string. To concatenate strings, we use the + operator. Keep in mind that when we work with numbers, + will be an operator for addition, but when used with strings it is a joining operator.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Boolean-Values">Boolean Values<a class="anchor-link" href="#Boolean-Values"> </a></h1><p>In programming you often need to know if an expression is True or False.
You can evaluate any expression in Python, and get one of two answers, True or False.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="mi">10</span> <span class="o">&gt;</span> <span class="mi">9</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="mi">10</span> <span class="o">==</span> <span class="mi">9</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="mi">10</span> <span class="o">&lt;</span> <span class="mi">9</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>True
False
False
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Python-Operators">Python Operators<a class="anchor-link" href="#Python-Operators"> </a></h1><p>Operators are used to perform operations on variables and values.
In the example below, we use the + operator to add together two values:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="mi">10</span> <span class="o">+</span> <span class="mi">5</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>15
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Tuple">Tuple<a class="anchor-link" href="#Tuple"> </a></h1><p>Tuples are used to store multiple items in a single variable.
Tuple is one of 4 built-in data types in Python used to store collections of data, the other 3 are List, Set, and Dictionary, all with different qualities and usage.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">thistuple</span> <span class="o">=</span> <span class="p">(</span><span class="s2">&quot;apple&quot;</span><span class="p">,</span> <span class="s2">&quot;banana&quot;</span><span class="p">,</span> <span class="s2">&quot;cherry&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">thistuple</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>(&#39;apple&#39;, &#39;banana&#39;, &#39;cherry&#39;)
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Python-Conditions-and-If-statements">Python Conditions and If statements<a class="anchor-link" href="#Python-Conditions-and-If-statements"> </a></h1><p>Python supports the usual logical conditions from mathematics:</p>
<ul>
<li>Equals: a == b</li>
<li>Not Equals: a != b</li>
<li>Less than: a &lt; b</li>
<li>Less than or equal to: a &lt;= b</li>
<li>Greater than: a &gt; b</li>
<li>Greater than or equal to: a &gt;= b</li>
<li>These conditions can be used in several ways, most commonly in "if statements" and loops.</li>
</ul>
<p>An "if statement" is written by using the if keyword.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">a</span> <span class="o">=</span> <span class="mi">33</span>
<span class="n">b</span> <span class="o">=</span> <span class="mi">200</span>
<span class="k">if</span> <span class="n">b</span> <span class="o">&gt;</span> <span class="n">a</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;b is greater than a/&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>b is greater than a/
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Python-Loops">Python Loops<a class="anchor-link" href="#Python-Loops"> </a></h1><p>Python has two primitive loop commands:
while loops
for loops</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">i</span> <span class="o">=</span> <span class="mi">1</span>
<span class="k">while</span> <span class="n">i</span> <span class="o">&lt;</span> <span class="mi">6</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
  <span class="n">i</span> <span class="o">+=</span> <span class="mi">1</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>1
2
3
4
5
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">i</span> <span class="o">=</span> <span class="mi">1</span>
<span class="k">while</span> <span class="n">i</span> <span class="o">&lt;</span> <span class="mi">6</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
  <span class="k">if</span> <span class="n">i</span> <span class="o">==</span> <span class="mi">3</span><span class="p">:</span>
    <span class="k">break</span>
  <span class="n">i</span> <span class="o">+=</span> <span class="mi">1</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>1
2
3
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Function">Function<a class="anchor-link" href="#Function"> </a></h1><p>A function is a block of code which only runs when it is called.
You can pass data, known as parameters, into a function.
A function can return data as a result.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">my_function</span><span class="p">():</span>
  <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Hello from a function&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Python-ascii()-Function">Python ascii() Function<a class="anchor-link" href="#Python-ascii()-Function"> </a></h1><p>The ascii() function returns a readable version of any object (Strings, Tuples, Lists, etc). The ascii() function will replace any non-ascii characters with escape characters: å will be replaced with \xe5</p>

</div>
</div>
</div>
</div>
 

