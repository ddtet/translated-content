---
title: CharacterData.remove()
slug: Web/API/CharacterData/remove
tags:
  - API
  - CharacterData
  - DOM
  - メソッド
browser-compat: api.CharacterData.remove
translation_of: Web/API/CharacterData/remove
---
<div>{{APIRef("DOM")}}</div>

<p><code><strong>CharacterData.remove()</strong></code> メソッドは、テキストを削除します。</p>

<h2 id="Syntax">構文</h2>

<pre class="brush: js">remove()</pre>

<h2 id="Example">例</h2>

<h3 id="Using_remove"><code>remove()</code> の使用</h3>

<pre class="brush: html">
&lt;p id="myText"&gt;Some text&lt;/p&gt;
</pre>

<pre class="brush: js">let text = document.getElementById('myText').firstChild;
text.remove(); // テキストを削除
</pre>

<pre class="brush: html">
&lt;p id="myText"&gt;&lt;/p&gt;
</pre>

<h2 id="Specifications">仕様書</h2>

{{Specifications}}

<h2 id="Browser_compatibility">ブラウザーの互換性</h2>

<p>{{Compat}}</p>

<h2 id="See_also">関連情報</h2>

<ul>
  <li>{{domxref("Element.remove()")}}</li>
</ul>