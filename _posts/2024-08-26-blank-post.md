---
layout: distill
title: blank post
description: post template
date: 2024-10-12
disqus_comments: false # set to true to add commenting
citation: false # set to true for citing posts
pretty_table: true # for tables
featured: false

toc: # table of contents
  - name: Paragraphs
  - name: Code Blocks
  - name: Links
  - name: Lists
  - name: Quotes
  - name: Images
  - name: Math
  - name: Dropdowns
  - name: Tables
  - name: Media
  # if a section has subsections, you can add them as follows:
  # subsections:
  #   - name: Example Child Subsection 1
  #   - name: Example Child Subsection 2
---

## Paragraphs

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

## Code Blocks

Here's some code:
{% highlight javascript %}
int main() {
cout << "Hello, world!" << endl;
return 0;
}
{% endhighlight %}

---

## Links

Here's some text with a [link](https://umich.edu/) to the University of Michigan wesbite and [another link](https://www.wolverinesoft.org/about-wolverinesoft-studio) to the WolverineSoft Studio website.

---

## Lists

Here's a list:

- one
- two
- three
- four

And here's a checklist:

- [ ] Not done
- [x] Done
  - [ ] Not really
  - [x] ...but almost!

---

## Quotes

Here's a quote:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

---

## Images

Here are some images:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image-1.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image-2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image-1.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

---

## Math

Here's some math $$y = mx + b$$ inside a paragraph.

Here's some math in display mode:

$$
y = mx + b
$$

Here's how to do a bunch of math expressions:

- Vector: $$\langle x, y \rangle$$
- Sum: $$\sum_{i=1}^n c = cn$$
- Infinity symbol: $$\infty$$
- Squared: $$x^2$$
- Less than: $$\leq$$

---

## Dropdowns

Here's a dropdown box:

{% details Click here to know more %}
Additional details, where math $$y = mx + b$$ and code work.

{% highlight javascript %}
int main() {
cout << "Hello, world!" << endl;
return 0;
}
{% endhighlight %}

{% enddetails %}

---

## Tables

Here's a table:

| left aligned | center aligned | right aligned |
| :----------- | :------------: | ------------: |
| left 1       |    center 1    |       right 1 |
| left 2       |    center 2    |       right 2 |
| left 3       |    center 3    |       right 3 |

---

## Media

Here's a local video file and a local audio file:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/video.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include audio.liquid path="assets/audio/audio.mp3" controls=true %}
    </div>
</div>
<div class="caption">
    This is a caption.
</div>
