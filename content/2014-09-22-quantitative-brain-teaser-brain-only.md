Title: Quantitative Brain Teaser: Brain Only
Date: 2014-09-23 16:10
Author: Danny Hermes (noreply@blogger.com)
Tags: Brain Teaser, Combinatorics, Digit Counting, Interview Questions, Mathematics
Slug: quantitative-brain-teaser-brain-only

<p>
I've recently been working some atrophied mental muscles and came across
a brain teaser that was pretty nifty:   

> Find a <span>10-digit number</span>, where each digit represents the
> number of that ordinal number in the whole number. So, the <span>first
> digit represents the number of 0's</span> in the whole 10 digits. The
> second digit represents the number of 1's in the whole 10 digits. And
> so on. The first digit is not a 0.

* * * * *

#### Example

If we shortened from 10 digits to 4 digit, the number   

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.64444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span class="mord">2</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">2</span><span
> class="mord">0</span></span></span></span></span>

</div>

works since we have <span class="katex"><span class="katex-inner"><span
class="strut" style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">0</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">2</span></span></span></span>
and two 0's (in the second and fourth slots), <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">0</span></span></span></span>
since the number has no 1's, <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">2</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span
class="mord">2</span></span></span></span>since the number has two 2's
(in the first and third slots) and <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">3</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">0</span></span></span></span>
since the number has no 3's.

* * * * *

#### Shorthand Notation

In order to refer to each digit, for search we name them all:

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.69444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span
> class="reset-textstyle displaystyle textstyle uncramped"><span
> class="mord mathit">n</span><span class="mrel">=</span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">0</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mpunct">,</span><span class="mord"><span
> class="mord mathit">d</span><span class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">1</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">2</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">3</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mpunct">,</span><span class="mord"><span
> class="mord mathit">d</span><span class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">4</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">5</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">6</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mpunct">,</span><span class="mord"><span
> class="mord mathit">d</span><span class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">7</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">8</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">9</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord">.</span></span></span></span></span></span>

</div>

We can see this in the above example when we refer to the digits in the
four digit number

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.69444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span
> class="mord mathit">n</span><span class="mrel">=</span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">0</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mpunct">,</span><span class="mord"><span
> class="mord mathit">d</span><span class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">1</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">2</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord"><span class="mord mathit">d</span><span
> class="vlist"><span
> style="margin-right: 0.05em; margin-left: 0em;"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span><span
> class="reset-textstyle scriptstyle cramped"><span
> class="mord">3</span></span></span><span class="baseline-fix"><span
> class="fontsize-ensurer reset-size5 size5"><span
> style="font-size: 0em;">​</span></span>​</span></span></span><span
> class="mord">.</span></span></span></span></span>

</div>

* * * * *

#### A Practical Approach, Breaking Into Subproblems

Our search space is massive, and with only our wits, we need to quickly
find a way to focus on a small space of possibilities. Since the first
digit allows us to place a number of 0's we try to set it equal to
values starting from the largest. By doing this we only have a little
wiggle room to find the places which don't hold a zero.

* * * * *

#### First Case: <span class="katex"><span class="katex-inner"><span class="strut" style="height: 0.69444em;"></span><span class="strut bottom"></span><span class="base textstyle uncramped"><span class="mord"><span class="mord mathit">d</span><span class="vlist"><span style="margin-right: 0.05em; margin-left: 0em;"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span><span class="reset-textstyle scriptstyle cramped"><span class="mord">0</span></span></span><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span>​</span></span></span><span class="mrel">=</span><span class="mord">9</span></span></span></span>

In this case our only choice is

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.64444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span class="mord">9</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span
> class="mord">0</span></span></span></span></span>

</div>

since we must have nine 0's. However since we have one 9, <span
class="katex"><span class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">9</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">0</span></span></span></span>
should not occur.   
  
Thus we see <span>none of our choices are possible</span> when <span
class="katex"><span class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">0</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">9</span></span></span></span>.

* * * * *

#### Second Case: <span class="katex"><span class="katex-inner"><span class="strut" style="height: 0.69444em;"></span><span class="strut bottom"></span><span class="base textstyle uncramped"><span class="mord"><span class="mord mathit">d</span><span class="vlist"><span style="margin-right: 0.05em; margin-left: 0em;"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span><span class="reset-textstyle scriptstyle cramped"><span class="mord">0</span></span></span><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span>​</span></span></span><span class="mrel">=</span><span class="mord">8</span></span></span></span>

Here we must have eight 0's and <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">8</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">\></span><span class="mord">0</span></span></span></span>
so our possible solutions must look like

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.64444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span class="mord">8</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mbin">∗</span><span
> class="mord">0</span></span></span></span></span>

</div>

But this leaves us with <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">8</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span> as
our only choice since we can't place any more 8's. But now the presence
of a 1 in

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.64444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span class="mord">8</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">1</span><span
> class="mord">0</span></span></span></span></span>

</div>

can't coexist with <span class="katex"><span class="katex-inner"><span
class="strut" style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">0</span></span></span></span> so
we again see <span>none of our choices are possible</span> when <span
class="katex"><span class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">0</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">8</span></span></span></span>.

* * * * *

#### Third Case: <span class="katex"><span class="katex-inner"><span class="strut" style="height: 0.69444em;"></span><span class="strut bottom"></span><span class="base textstyle uncramped"><span class="mord"><span class="mord mathit">d</span><span class="vlist"><span style="margin-right: 0.05em; margin-left: 0em;"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span><span class="reset-textstyle scriptstyle cramped"><span class="mord">0</span></span></span><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span>​</span></span></span><span class="mrel">=</span><span class="mord">7</span></span></span></span>

Here we have seven 0's and know that <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">7</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span>.
It must be at least 1 since the first digit is a 7. It can't be 2
because the presence of another 7 would mean another digit (other than
0) would occur 7 times, which is impossible since there are only 10
total digits.   
  
Since we know <span class="katex"><span class="katex-inner"><span
class="strut" style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">7</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span>
our possible solutions must look like

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.64444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span class="mord">7</span><span
> class="mpunct">,</span><span class="mord">∗</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">1</span><span
> class="mord">0</span><span
> class="mord">0</span></span></span></span></span>

</div>

But again here we reach an impossible point. If we set <span
class="katex"><span class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span>
then that digit would contradict itself since it is the second
occurrence of 1. If <span class="katex"><span class="katex-inner"><span
class="strut" style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">2</span></span></span></span> it
would contradict <span class="katex"><span class="katex-inner"><span
class="strut" style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">2</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">0</span></span></span></span>
and so on for higher values. In addition, we have used all our digits,
so can't increase the value of <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span></span></span></span>
by placing more 1's in our number.   
  
Thus we see <span>none of our choices are possible</span> when <span
class="katex"><span class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">0</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">7</span></span></span></span>.

* * * * *

#### Fourth Case: <span class="katex"><span class="katex-inner"><span class="strut" style="height: 0.69444em;"></span><span class="strut bottom"></span><span class="base textstyle uncramped"><span class="mord"><span class="mord mathit">d</span><span class="vlist"><span style="margin-right: 0.05em; margin-left: 0em;"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span><span class="reset-textstyle scriptstyle cramped"><span class="mord">0</span></span></span><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size: 0em;">​</span></span>​</span></span></span><span class="mrel">=</span><span class="mord">6</span></span></span></span>

Here we have six 0's and must have <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">6</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span>
since (as above), two different digits can't occur six times among 10
digits.   
  
Also as before we can't have <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span>
but now have some extra freedom (an extra digit which doesn't have to be
0) so consider the case <span class="katex"><span
class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">1</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">2</span></span></span></span>.
This corresponds to an occurrence of the digit 2, hence we set <span
class="katex"><span class="katex-inner"><span class="strut"
style="height: 0.69444em;"></span><span
class="strut bottom"></span><span class="base textstyle uncramped"><span
class="mord"><span class="mord mathit">d</span><span class="vlist"><span
style="margin-right: 0.05em; margin-left: 0em;"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span><span
class="reset-textstyle scriptstyle cramped"><span
class="mord">2</span></span></span><span class="baseline-fix"><span
class="fontsize-ensurer reset-size5 size5"><span
style="font-size: 0em;">​</span></span>​</span></span></span><span
class="mrel">=</span><span class="mord">1</span></span></span></span>.   
  
Now we have 4 non-zero digits along with six 0's to place:

<div style="text-align: center;">

> <span style="font-size: x-large;"><span class="katex"><span
> class="katex-inner"><span class="strut"
> style="height: 0.64444em;"></span><span
> class="strut bottom"></span><span
> class="base textstyle uncramped"><span class="mord">6</span><span
> class="mpunct">,</span><span class="mord">2</span><span
> class="mord">1</span><span class="mord">0</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span class="mord">1</span><span
> class="mpunct">,</span><span class="mord">0</span><span
> class="mord">0</span><span
> class="mord">0</span></span></span></span></span>

</div>

Thus <span>we have found a number</span> which satisfies the criteria!
The zero digits in the 3, 4, 5, 7, 8, and 9 places correspond to the
absence of those digits. The non-zero digits in the 0, 1, 2, and 6
places also are the correct counts of each of those digits.   
  
As a math nerd, I was still curious to know how to find every possible
number that satisfies the criteria, but that task is too tedious to
handle with the brain alone (or at least to be worth reading about when
solved by hand). In my follow up to this, I'll show how a combination of
smarts and programming can perform an exhaustive search in under 10
seconds. [About Bossy
Lobster](https://profiles.google.com/114760865724135687241)

</p>
