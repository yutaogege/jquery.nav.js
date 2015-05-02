<h2>浏览器兼容</h2>
<table class="browsers">
<thead>
<tr>
<th><img title="IE" src="http://cdn.dowebok.com/global/ie.png" alt="IE"></th>
<th><img title="Chrome" src="http://cdn.dowebok.com/global/chrome.png" alt="Chrome"></th>
<th><img title="Firefox" src="http://cdn.dowebok.com/global/firefox.png" alt="Firefox"></th>
<th><img title="Opera" src="http://cdn.dowebok.com/global/opera.png" alt="Opera"></th>
<th><img title="Safari" src="http://cdn.dowebok.com/global/safari.png" alt="Safari"></th>
</tr>
</thead>
<tbody>
<tr>
<td>IE7+ ✔</td>
<td>Chrome ✔</td>
<td>Firefox ✔</td>
<td>Opera ✔</td>
<td>Safari ✔</td>
</tr>
</tbody>
</table>
<h2>使用方法</h2>
<h3>1、引入文件</h3>
<pre class="brush:xml">&lt;script src="js/jquery.min.js"&gt;&lt;/script&gt;
&lt;script src="js/jquery.nav.js"&gt;&lt;/script&gt;</pre>
<h3>2、HTML</h3>
<pre class="brush:xml">&lt;ul id="nav"&gt;
    &lt;li&gt;&lt;a href="#intro"&gt;简介&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href="#usage"&gt;使用&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href="#options"&gt;选项&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href="#examples"&gt;示例&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href="#recommend"&gt;推荐&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;

&lt;div class="wrap"&gt;
    &lt;div id="intro"&gt;&lt;/div&gt;
    &lt;div id="usage"&gt;&lt;/div&gt;
    &lt;div id="options"&gt;&lt;/div&gt;
    &lt;div id="examples"&gt;&lt;/div&gt;
    &lt;div id="recommend"&gt;&lt;/div&gt;
&lt;/div&gt;</pre>
<h3>3、JavaScript</h3>
<pre class="brush:js">$(function(){
&nbsp;&nbsp; &nbsp;$('#nav').onePageNav();
});</pre>
<h2>配置</h2>
<table class="table">
<thead>
<tr>
<th>属性/方法</th>
<th width="100px">类型</th>
<th>默认值</th>
<th>说明</th>
</tr>
</thead>
<tbody>
<tr>
<td>currentClass</td>
<td>字符串</td>
<td>‘current’</td>
<td>导航高亮的 class</td>
</tr>
<tr>
<td>changeHash</td>
<td>布尔值</td>
<td>false</td>
<td>URL 显示命名锚记</td>
</tr>
<tr>
<td>scrollSpeed</td>
<td>整数</td>
<td>750</td>
<td>动画持续时间，以毫秒为单位</td>
</tr>
<tr>
<td>scrollThreshold</td>
<td>整数/浮点数</td>
<td>0.5</td>
<td>下一个处于浏览器可视区域多少比例时导航切换</td>
</tr>
<tr>
<td>filter</td>
<td>字符串</td>
<td>”</td>
<td>过滤不要的项，如 filter: ‘:not(.external)’</td>
</tr>
<tr>
<td>easing</td>
<td>字符串</td>
<td>‘swing’</td>
<td>滚动动画方式</td>
</tr>
<tr>
<td>begin</td>
<td>函数</td>
<td></td>
<td>滚动前的回调函数</td>
</tr>
<tr>
<td>end</td>
<td>函数</td>
<td></td>
<td>滚动后的回调函数</td>
</tr>
<tr>
<td>scrollChange</td>
<td>函数</td>
<td></td>
<td>导航切换后的回调函数</td>
</tr>
</tbody>
</table>
