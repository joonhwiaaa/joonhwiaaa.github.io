---
layout: page
title: Physics
permalink: /physics/
---

## Publications

<div class="container">
<p style="text-align:center">
  <a href="https://scholar.google.com/citations?user=A15RZN4AAAAJ">Google Scholar</a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://inspirehep.net/authors/1926101">InspireHEP</a>
</p>
</div>

<br>

<div class="container">
{% for paper in site.data.papers %}
<div class="row">
  <div class="col-md-10" style="float:left"> {{ paper.title }} </div>
  <div class="col-md-2" style="text-align:right"> <a href="http://arxiv.org/abs/{{ paper.arxivnumber }}">arXiv:{{ paper.arxivnumber }}</a> </div>
</div>
{% endfor %}
</div>

<br>

## "Prehistory"

<div class="container">
{% for paper in site.data.papers-prehistory %}
<div class="row">
  <div class="col-md-10" style="float:left"> {{ paper.title }} </div>
  <div class="col-md-2" style="text-align:right"> <a href="http://arxiv.org/abs/{{ paper.arxivnumber }}">arXiv:{{ paper.arxivnumber }}</a> </div>
</div>
{% endfor %}
</div>

***

### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

***

## Table

<div class="table-container">
  <table>
    <tr><th>Header 1</th><th>Header 2</th><th>Header 3</th><th>Header 4</th><th>Header 5</th></tr>
    <tr><td>Row:1 Cell:1</td><td>Row:1 Cell:2</td><td>Row:1 Cell:3</td><td>Row:1 Cell:4</td><td>Row:1 Cell:5</td></tr>
    <tr><td>Row:2 Cell:1</td><td>Row:2 Cell:2</td><td>Row:2 Cell:3</td><td>Row:2 Cell:4</td><td>Row:2 Cell:5</td></tr>
    <tr><td>Row:3 Cell:1</td><td>Row:3 Cell:2</td><td>Row:3 Cell:3</td><td>Row:3 Cell:4</td><td>Row:3 Cell:5</td></tr>
    <tr><td>Row:4 Cell:1</td><td>Row:4 Cell:2</td><td>Row:4 Cell:3</td><td>Row:4 Cell:4</td><td>Row:4 Cell:5</td></tr>
    <tr><td>Row:5 Cell:1</td><td>Row:5 Cell:2</td><td>Row:5 Cell:3</td><td>Row:5 Cell:4</td><td>Row:5 Cell:5</td></tr>
    <tr><td>Row:6 Cell:1</td><td>Row:6 Cell:2</td><td>Row:6 Cell:3</td><td>Row:6 Cell:4</td><td>Row:6 Cell:5</td></tr>
  </table>
</div>

***

## Quotes

#### A quote looks like this:

> The longer I live, the more I realize that I am never wrong about anything, and that all the pains I have so humbly taken to verify my notions have only wasted my time!
>
> <cite>George Bernard Shaw</cite>

***



## Syntax Highlighter

{% highlight css %}
body {
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vw;
  background-color: #1c2021;
}

li {
  width: 200px;
  min-height: 250px;
  border: 1px solid #000;
  display: inline-block;
  vertical-align: top;
  margin: 5px;
}
{% endhighlight %}

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

## Images

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/09.jpg">
    <img src="/images/06.jpg">
    <img src="/images/03.jpg">
    <img src="/images/08.jpg">
    <img src="/images/05.jpg">
    <img src="/images/11.jpg">
  </div>
  <em>Gallery / <a href="https://unsplash.com/" target="_blank">Unsplash</a></em>
</div>

![Minimalism]({{site.baseurl}}/images/04.jpg)
*Photo by [Kimon Maritz](https://unsplash.com/photos/mQiZnKwGXW0) on [Unsplash](https://unsplash.com/)*

***

## Youtube Embed

<p><iframe src="https://www.youtube.com/embed/hRXd0MMsixI" frameborder="0" allowfullscreen></iframe></p>

***

## Vimeo Embed

<p><iframe src="https://player.vimeo.com/video/147264547?title=0&byline=0" width="640" height="360" frameborder="0" allowfullscreen></iframe></p>

***