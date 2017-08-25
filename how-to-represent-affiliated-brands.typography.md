---
layout: default
title: Typography
prevPage: /how_to_represent_affiliated_brands/colors/
nextPage: /how_to_represent_affiliated_brands/photography/
permalink: /how_to_represent_affiliated_brands/typography/
category: how_to_represent_affiliated_brands
subcategory: resources
order: 4.3
---

# Typography - Option 1

WRIʼs typography takes advantage of attractive, clean fonts that are readily available to
our staff and partners.

Our predominant font is the Acumin family.

<div class="columns-text">
	<div class="col font-01">
		<strong class="ttl-line">Acumin Pro</strong>
		<p>ABCDEFGHIJKLM NOPQRSTUVWXYZ abcdefghijklm nopqrstuvwxyz 1234567890</p>
	</div>
	<div class="col font-02">
		<strong class="ttl-line">Acumin Pro Condensed</strong>
		<p>ABCDEFGHIJKLM NOPQRSTUVWXYZ abcdefghijklm nopqrstuvwxyz 1234567890</p>
	</div>
</div>

If you seek a serif font we use Georgia font

<div class="columns-text">
	<div class="col font-03">
		<strong class="ttl-line">Georgia</strong>
		<p>ABCDEFGHIJKLM NOPQRSTUVWXYZ abcdefghijklm nopqrstuvwxyz 1234567890</p>
	</div>
</div>

# Typekit

The Acumin Pro Condensed family is available free through Adobe Typekit with a Creative
Cloud account. If not, we provide files for download at brand.wri.org.

# Use of type

These are the most common type uses in the website. Use the hierarchy laid out below to
compose easy-to-read content pages.

<div class="content">
	<h1>H1 - Main title or claim for a particular page </h1>
	<h2>H2 - Category or sub-section</h2>
	<h3>H3 - Each item of a given category</h3>
	<div class="block-520">
		Description - Description of an element, style not meant to be used in long-read content. To improve readability, it’s strongly advised to keep the width of a description paragraph narrower than 520px.
	</div>
	<p>
		<span class="btn-lbl">Button Label</span>
	</p>
	<div class="min-txt">
		<strong>MENU ITEM / CHART LEGEND</strong>
		<p>Chart values &nbsp; 2010 &nbsp; 2011 &nbsp; 2012</p>
	</div>
	<div class="big-txt">
		<p>Body. This style is meant to be used in long-read content, <a>links style</a>. To improve readability, it’s strongly advised to keep the width of paragraphs narrower than 700px. Protecting these rights, especially for the most marginalized and vulnerable, is the first step to promoting equity and fairness in sustainable development. Without essential rights, information exchange between governments and the public is stifled and decisions that harm communities and the environment cannot be challenged or remedied.</p>
	</div>
</div>

>Quote text. Try not to make this too long, maybe three lines top, if not, what kind of quote is that? And also, try to keep the paragraph narrower than 600px if possible :)
>
> <cite><strong>Quote Author</strong> Quote author position  </cite>


```css
body {
    -webkit-font-smoothing: antialiased;
    font-family: AcuminPro, Arial, "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: #4A4A4A;
}

h1 {
    font-size: 30px;
    font-weight: 300;
    line-height: 1.2;
}

h2 {
    font-family: 'AcuminProCond';
    font-size: 23px;
    font-weight: 700;
    line-height: 1.1;
}

h3 {
    font-size: 22px;
    font-weight: 400;
    line-height: 1.1;
}

.description {
    font-size: 16px;
    line-height: 1.625;
}

.btn-lbl {
    text-align: center;
    display: inline-block;
    vertical-align: top;
    font-size: 14px;
    border: 1px solid #4a4a4a;
    border-radius: 3px;
    min-width: 170px;
    font-weight: 700;
    padding: 13px 20px 13px
}

.legend {
    font-weight: 400;
    font-size: 13px;
    text-transform: uppercase;
}

.chart-value {
    font-size: 12px;
    line-height: 1.2;
}

p {
    font-size: 18px;
    line-height: 1.77;
    font-weight: 300;
}

blockquote {
    font-size: 22px;
    line-height: 1.45;
    font-weight: 300;
    letter-spacing: -1px;
    padding: 20px 0 44px 15%;
}

blockquote cite {
    text-align: right;
    font-size: 16px;
}

blockquote cite strong {
    display: block;
    font-weight: 700;
}
```

# Examples

<span class="examples-block size-02">
	<span class="post-examples">
		![image description]({{ site.baseurl }}/images/image34.jpg)
		<a href="https://zpl.io/Zd6ilD" class="button" target="_blank" rel="noreferrer noopener">Open in zeplin</a>
	</span>
	<span class="post-examples">
		![image description]({{ site.baseurl }}/images/image35.jpg)
		<a href="https://zpl.io/1TkWME" class="button" target="_blank" rel="noreferrer noopener">Open in zeplin</a>
	</span>
</span>
