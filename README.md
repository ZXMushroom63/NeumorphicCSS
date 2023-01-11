# NeumorphicCSS
An all-in-one neumorphism css stylesheet.<br>
Is pretty simple to use!<br>
<br>
First, to get started you have to include the stylesheet to your HTML file.<br>
You can do this by copying the contents of <a href="neumorphic.css">neumorphic.css</a> to your website, or some other method.
<br>
<br>
Now that the stylesheet is included, you have to make a container for the elements.<br>
<code>&lt;div class=&quot;neu container&quot;&gt;...&lt;/div&gt;</code><br>
<br>
Optionally, if your whole website will be using this, set the class of your <code>&lt;html&gt;</code> tag to "neu"<br><br>
Then, mix and match with a variety of elements! Put them in the container.<br>
<table>
<tr>
<th>Element</th>
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
</table>
