# NeumorphicCSS
An all-in-one neumorphism css stylesheet.<br>
Is pretty simple to use!<br>
<br>
First, to get started you have to include the stylesheet to your HTML file.<br>
You can do this by copying the contents of <a href="neumorphic.css">neumorphic.css</a> to your website, or by adding this script which automatically adds it to your website.<br>
```html
<script>
fetch("https://raw.githubusercontent.com/ZXMushroom63/NeumorphicCSS/main/neumorphic.css").then((x)=>{x.blob().then((y)=>{y.text().then((z)=>{var s=document.createElement("style");s.innerHTML=z;document.head.appendChild(s);});});});
</script>
```
<br>
<br>
Now that the stylesheet is included, you have to make a container for the elements.<br>
<code>&lt;div class=&quot;neu container&quot;&gt;...&lt;/div&gt;</code><br>
<br>
Optionally, if your whole website will be using this, set the class of your <code>&lt;html&gt;</code> tag to "neu"<br><br>
Then, mix and match with a variety of elements! Put them in the container.<br>
<table>
<tr>
<th>Feature</th>
<th>HTML</th>
</tr>
<tr>
<td>A panel</td>
<td>
<code>
&lt;div class=&quot;neu panel&quot;&gt;
</code>
</td>
</tr>
<tr>
<td>An inset panel</td>
<td>
<code>
&lt;div class=&quot;neu insetPanel&quot;&gt;
</code>
</td>
</tr>
<tr>
<td>A button</td>
<td>
<code>
&lt;button class=&quot;neu&quot;&gt;...&lt;/button&gt;
</code>
</td>
</tr>
<tr>
<td>Most input elements</td>
<td>
<code>
&lt;input type=&quot;...&quot; class=&quot;neu&quot;&gt;
</code>
</td>
</tr>
<tr>
<td>Switches</td>
<td>
<code>
&lt;input type=&quot;checkbox&quot; class=&quot;neu switch&quot;&gt;
</code>
</td>
</tr>
<tr>
<td>Textareas</td>
<td>
<code>
&lt;textarea class=&quot;neu&quot;&gt;...&lt;/textarea&gt;
</code>
</td>
</tr>
<tr>
<td>Concave elements</td>
<td>
<code>
&lt;* class=&quot;neu concave&quot;&gt;...&lt;/*&gt;
</code>
</td>
</tr>
<tr>
<td>Convex elements</td>
<td>
<code>
&lt;* class=&quot;neu convex&quot;&gt;...&lt;/*&gt;
</code>
</td>
</tr>
<tr>
<td>Tables</td>
<td>
<code>
&lt;table class=&quot;neu&quot;&gt;...&lt;/table&gt;
</code>
</td>
</tr>
<tr>
<td>Corners</td>
<td>
<code>
&lt;* class=&quot;neu squareCorners&quot;&gt;...&lt;/*&gt;
</code><br>OR<br>
  <code>
&lt;* class=&quot;neu roundCorners&quot;&gt;...&lt;/*&gt;
</code>
</td>
</tr>
<tr>
<td>Inset & Outset Forcing</td>
<td>
<code>
&lt;* class=&quot;neu outset&quot;&gt;...&lt;/*&gt;
</code><br>OR<br>
<code>
&lt;* class=&quot;neu inset&quot;&gt;...&lt;/*&gt;
</code>
</td>
</tr>
<tr>
<td>Selects</td>
<td>
<code>
&lt;select class=&quot;neu&quot;&gt;...&lt;/select&gt;
</code>
</td>
</tr>
<tr>
<td>Small or Circular Buttons</td>
<td>
<code>
&lt;button class=&quot;neu smallButton&quot;&gt;...&lt;/button&gt;
</code><br>OR<br>
<code>
&lt;button class=&quot;neu smallButton circle&quot;&gt;...&lt;/button&gt;
</code>
</td>
</tr>
<tr>
<td>Corner Roundness</td>
<td>
<code>
&lt;* class=&quot;neu smallButton&quot;&gt;...&lt;/*&gt;
</code><br>OR<br>
<code>
&lt;* class=&quot;neu smallButton circle&quot;&gt;...&lt;/*&gt;
</code>
</td>
</tr>
</table>
