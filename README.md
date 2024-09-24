My Index
https://torrenb.github.io/Game-Dev-11/public2/index.html




<h2 align=center> t1a10-loops</h2>  
<a href="">Good referance to Javascript Loops</a><br>

<h4> Example input output code</h4>
<pre>
  
</pre>

<h4> Example working code</h4>
Max loops: <input id="myNum01 value="4" ><br>
<input type=button value="Basic for loop with Decisions" onclick="{
document.getElementById('myDiv01').innerHTML = ''
let myTemp = ''
let myMax = parseInt(document.getElementById('myNum01').value)
for (let myLoop = 0; myLoop < Mymax; myLoop+++ ){
if (myLoop * 2 > myMax){
myTemp += ' cool '
}
myTemp += 'Loop number: ' + myLoop + '<br>
}
document.getElementById('myDiv01').innerhtml = myTemp
}">

<div id="myDiv01">...</div>
