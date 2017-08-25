---
layout: default
title: Responsive grid
prevPage: /brand_architecture/footer/
nextPage: /brand_architecture/partners_page_template/
permalink: /brand_architecture/responsive_grid/
category: brand_architecture
subcategory: structure
order: 2.5
---

# Responsive grid

WRI project websites use a 12 column grid (six on smallest devices). This grid makes it easy to create elements with different widths and place them in the design in a structured and organized way.

These are some examples of possible configurations for contents of the 12 column grid

![image description]({{ site.baseurl }}/images/image14.png)

<div class="align-right margin-bottom">
	Desktop displays
</div>

![image description]({{ site.baseurl }}/images/image15.png)

<div class="align-right margin-bottom">
	Mobile devices
</div>

<p>Each column is composed by a variable width that changes with the display size and a 20-pixel gutter. There are three cases for a screen up to 1200 pixel-width, the maximum allowed. If the screen is wider than that, the content stays centered. If the screen is smaller than 720 pixels, the content adapts to a mobile device layout with an elastic columns grid.</p>

![image description]({{ site.baseurl }}/images/image16.png)

<div class="grid-table">
	<ul>
		<li>
			<div class="col">
				<strong class="ttl-line">Screen width</strong>
			</div>
			<div class="col">
				<strong class="ttl-line">Column width</strong>
			</div>
		</li>
		<li>
			<div class="col">> 1260 px </div>
			<div class="col">70 px (1080 px)</div>
		</li>
		<li>
			<div class="col">1260 - 960 px</div>
			<div class="col">60 px (960 px)</div>
		</li>
		<li>
			<div class="col">960 - 720 px</div>
			<div class="col">40 px (720 px)</div>
		</li>
		<li>
			<div class="col"><720</div>
			<div class="col">1/12</div>
		</li>
	</ul>
</div>

# Responsive design example


<div class="width-70"><strong class="ttl-line">Desktop</strong></div>

<span class="post-examples">
	<span class="lightbox" data-lightbox="{{ site.baseurl }}/images/image18-big.png">
		![image description]({{ site.baseurl }}/images/image18.jpg)
	</span>
</span>

<span class="examples-block width-01">
	<span class="post-examples">
		<strong class="ttl-line">Tablet</strong>
		<span class="lightbox" data-lightbox="{{ site.baseurl }}/images/image19-big.png">
			![image description]({{ site.baseurl }}/images/image19.jpg)
		</span>
	</span>
	<span class="post-examples">
		<strong class="ttl-line">Mobile</strong>
		<span class="wrap">
			<span class="lightbox" data-lightbox="{{ site.baseurl }}/images/image20-big.png">
				![image description]({{ site.baseurl }}/images/image20.jpg)
			</span>
			<span class="lightbox" data-lightbox="{{ site.baseurl }}/images/image21-big.png">
				![image description]({{ site.baseurl }}/images/image21.jpg)
			</span>
		</span>
	</span>
</span>
