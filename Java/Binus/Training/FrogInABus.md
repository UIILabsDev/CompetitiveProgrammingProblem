<center>
<h3>ACM-ICPC Indonesia National Contest 2015</h3>
<h2>Practice Problem A</h2>
<h1>Frog in a Bus</h1>
Time Limit: 2 seconds
</center>
<br/>

<img src="pa.gif" width="400" height="259" align="right">

<p>In the Kingdom of Frog, a far far away country, the citizens use busses to travel between places. Unlike any city in Indonesia, busses in Kingdom of Frog are well organized, they only stop at shelters specified on their routes. There are several bus routes and each bus has a number (let's call it "bus-number") which can be seen from outside the bus. In each shelter, there is an information plate which contains a list of bus number, i.e. a list of busses which will stop at that particular shelter.</p>

<p>One day Marc -a brave frog knight- hopped on a bus at a shelter. But when he has been a board inside the bus, he just realized that he didn't check which bus he took at that moment. Being a brave knight, Marc has quite a high self-esteem. Therefore, he decided neither ask nor tell anyone in the bus about this matter. Instead, he tried to deduce which bus he took by observing which shelters are visited by that bus. From inside the bus, he could read the information plate of each shelter, thus he can learn the list of busses which will stop at that shelter.</p>

<p>Marc has more brawl than brain, so he needs your help. He will tell you the list of bus-number that he read from the information plate in each shelter, and you should deduce which bus he took.</p>

<p>If there is one unique bus-number which consistently appears at each bus stop, then it's Marc's bus number. Otherwise, there might be multiple possibilities (more than one of such bus), or inconsistency (none of such bus).</p>


<br>

<h3>Input</h3>
<p>The first line of input contains an integer T (1 &le; T &le; 100) the number of cases. Each case begins with an integer N (1 &le; N &le; 50) denoting the number of shelters in which the bus stop. The next N lines each begins with an integer M (1 &le; M &le; 10) denoting the number of bus-number written on the information plate in that particular shelter. M integers B<sub>i</sub> (1 &le; B<sub>i</sub> &le; 999) follows denoting the bus-number of busses which stop at that shelter (each number is unique to the shelter).
</p><h3>Output</h3>
<p>For each case, output in a line "<font face="Courier New">Case #X: Y</font>" where X is the case number, starting from 1, and Y is either:</p>
<li>The bus-number of bus which Marc took, i.e. unique possibility, or</li>
<li>"<font face="Courier New">NOT SURE</font>" (without quote) if there's not enough information, i.e. multiple possibilities, or</li>
<li>"<font face="Courier New">AM I LOST?</font>" (without quote) if there's a contradiction, i.e. no possibility.</li>
<br>

<br><table border="0" cellspacing="0" cellpadding="0" bgcolor="#000000">
<tbody><tr><td>
<table border="0" cellspacing="1" cellpadding="4" width="600">
<tbody><tr><th align="left" width="250" bgcolor="#FFFFFF">Sample Input</th><th align="left" width="250" bgcolor="#FFFFFF">Output for Sample Input</th></tr>
<tr valign="top"><td bgcolor="#FFFFFF"><pre>3
5
5 10 200 95 189 51
3 143 176 10
4 143 51 176 10
2 10 143
4 188 10 30 51
3
2 100 200
3 200 150 100
4 100 150 200 300
3
3 50 60 70
2 70 80
3 60 80 90
</pre>
</td><td bgcolor="#FFFFFF"><pre>Case #1: 10
Case #2: NOT SURE
Case #3: AM I LOST?
</pre>
</td></tr>
</tbody></table>
</td></tr>
</tbody></table>

<br>
<p><i>Explanation for the 2<sup>nd</sup> sample input.</i></p>
<p>He could be in bus 100 or 200.</p>
