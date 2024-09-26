---
layout: distill
title: blank post
description: post template
date: 2024-09-26
disqus_comments: false # make true to add commenting
featured: true

toc: # table of contents
  - name: Paragraph
    # if a section has subsections, you can add them as follows:
    # subsections:
    #   - name: Example Child Subsection 1
    #   - name: Example Child Subsection 2
  - name: Code
  - name: Links
  - name: Lists
  - name: Caption
  - name: Images
  - name: Math
  - name: Dropdowns
  - name: Mermaid
---

## Paragraph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

## Code

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

## Caption

Here's a caption:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

---

## Images

Here are some images:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image.png" class="img-fluid rounded z-depth-1" zoomable=true %}
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