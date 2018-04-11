#### Simultaneous Contact, Gait and Motion Planning for Robust Multi-Legged Locomotion via Mixed-Integer Convex Optimization

Bernardo Aceituno, Carlos Mastalli, Hongkai Dai, Michele Focchi, Andreea Radulescu, Darwin G. Caldwell,
Jose Cappelletto, Juan C. Grieco, Gerardo Fernandez-Lopez and Claudio Semini

---

<header>Simultaneous Contact, Gait and Motion Optimization</header>

<article>
  <img src="/assets/img/slides/gait17ral/overview.png" style="width: 70%;"/>
  <ul>
	  <li> 
      <p class="fragment highlight-current-blue"
         data-fragment-index="1"> Non-coplanar stability throught friction cone constraints</p>
    </li>
    <li>
	    <p class="fragment highlight-current-blue"
         data-fragment-index="2">The centroidal dynamics describes the system's evolution</p>
    </li>
    <li>
    	<p class="fragment highlight-current-blue"
         data-fragment-index="3">Integer variables models the contacts and gait transitions</p>
    </li>
    <li>
    	<p class="fragment highlight-current-blue"
         data-fragment-index="4">Approximate the robot's joint torque limits</p>
    </li>
  </ul>
</article>

---

<header>Centroidal Dynamic Model</header>

<aside style="float:left;
    max-width: 400px;
    text-align: left;
    margin: 0;
    padding: 0em 0em">
  <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
  <img src="/assets/img/slides/gait17ral/centroidal_dynamics.png" alt="HyQ centroidal dynamics">
</aside>

<article style="margin-left: 400px;
  max-width: 520px;
  text-align: left;
    border-left: 1px solid gray;
    padding: 1em 0.5em;
    overflow: hidden;">
We represent the time evolution of the system using a centroidal dynamics model

  <h3>London</h3>
  $$
\begin{equation}
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
\end{equation} $$
  <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
  <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
</article>

---

#### Challenges of Rough Terrain Locomotion


<div style="width:100%;"> 
Header
<div style="float:left; width:20%;">
Left  Column
<br />
some text goes here
<br />
</div>
<div style="float:right; width:80%; ">
  <iframe class="embed-responsive-item" allowfullscreen="allowfullscreen"
    width="420" height="237"
    src="https://youtube.com/embed/KI9x1GZWRwE"
    style="float: right; "
    marginwidth="10">
  </iframe>
</div>

---

#### Challenges of Rough Terrain Locomotion

<table style="width: 100%;" cellpadding="20">
<tbody>
<tr>
<td style="width: 26.0368%;">Left Column</td>
<td style="width: 70.9632%;">
  <iframe class="embed-responsive-item" allowfullscreen="allowfullscreen"
    width="420" height="237"
    src="https://youtube.com/embed/KI9x1GZWRwE"
    style="float: right; "
    marginwidth="10">
  </iframe>
</td>
</tr>
</tbody>
</table>
<!-- DivTable.com -->
<p>&nbsp;</p>

---


<div class="container">

<header>
  <h4>Challenges of Rough Terrain Locomotion</h4>
</header>
  
<aside style="float:left;
    max-width: 60px;
    margin: 0;
    padding: 1em">
  <ul style="list-style-type: none;
    padding: 0;">
    <li><a href="">London</a></li>
    <li><a href="">Paris</a></li>
    <li><a href="">Tokyo</a></li>
  </ul>
</aside>

<article style="margin-left: 300px;
    border-left: 1px solid gray;
    padding: 1em;
    overflow: hidden;">
  <h3>London</h3>
  $$
\begin{equation}
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
\end{equation} $$
  <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
  <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
</article>

<footer style="padding: 1em;
    font-size: 50%;
    clear: left;
    text-align: center">Copyright &copy; W3Schools.com</footer>

</div>

---

## Welcome
Welcome to the jekyll-reveal.js example presentation.


| [![](https://i.imgur.com/BT7fRCU.gif)](https://www.youtube.com/watch?v=ENHvCGrnr2g&t=2s) | [![](https://i.imgur.com/4kKhryj.gif)](https://www.youtube.com/watch?v=KI9x1GZWRwE)
|:-------------------------:|:-------------------------:|
| [![](https://i.imgur.com/yXTtxUK.gif)](https://www.youtube.com/watch?v=ArV2yh7KSfE) | [![](https://i.imgur.com/RKe3sNo.gif)](https://www.youtube.com/watch?v=KI9x1GZWRwE)
|||

---

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/KI9x1GZWRwE/0.jpg)](http://www.youtube.com/watch?v=KI9x1GZWRwE)

---

$$
\begin{equation}
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
\end{equation} $$

---

$$
\begin{eqnarray} 
y &=& x^4 + 4      \nonumber \\\
  &=& (x^2+2)^2 -4x^2 \nonumber \\\
  &\le&(x^2+2)^2    \nonumber
\end{eqnarray} 
$$

---
$$
\begin{align}
(a+b)^2 &= (a+b)(a+b)\\\
&= a^2 + ab + ba + b^2\\\
&= a^2 + 2ab + b^2\frac{1}{\theta}
\end{align}
$$


$$E(h(\mathbf{X})) \approx \frac{1}{N} \sum_{i=1}^N h(\mathbf{X}_i)$$

---

<div style="font-size: 33%;">
$$
\begin{pmatrix}
   1 & 2 \\\
   3 & 4
\end{pmatrix}
$$
</div>


---

# Title
## Sub-title

Here is some content...
