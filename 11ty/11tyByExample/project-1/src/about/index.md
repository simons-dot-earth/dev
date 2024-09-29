---
layout: "layouts/base.html"
title: "About Us"
bannerContent: "This is a litte paragraph about the company."
pageId: "about"
---

## The page content can go here

It can use any markdown, since we're in a markdown page. Like [an
anchor](https://packtpub.com) or **bold text**.

* Or an unordered list
* With some items

1. Or an ordered list
1. With some items (no need to have different numbers in a
Markdown ordered list)

<section class="triptych">
  {% for triptych in triptychs %}
    {% include "includes/card.html", headline: triptych.headline, content: triptych.content %}
  {% endfor %}
</section>
