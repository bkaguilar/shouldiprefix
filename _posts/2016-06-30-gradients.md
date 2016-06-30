---
title: gradients
url: gradients
prefixed: false
---

<article id="gradients" class="feature prefix-{{page.prefixed}}">
	<header class="feature__header">
		<h2>gradients</h2>
	</header>
	<p class="feature__description">
		Method of defining a linear or radial color gradient as a CSS image.
	</p>
<pre class="feature__code"><code>
.example {
  background:         linear-gradient(to bottom, #333 0%,#EEE 100%); /* Fx 10+, Op 11.6+, Ch 26+, IE 10 */
}
</code></pre>
	<footer class="feature__footer">
		<a href="http://caniuse.com/gradients">Browser support</a> 
		<a href="http://html5please.com/#gradients">Usage advice</a> 
		<a href="http://www.css3files.com/gradient">More info</a> 
		<a href="https://github.com/davidhund/shouldiprefix/blob/master/_posts/{{page.date | date: "%Y-%m-%d"}}-{{page.title}}.md">Edit this</a> 
		<span class="feature__prefix">{{page.prefixed}}</span>
	</footer>
</article>
