---
layout: splash
permalink: /
date:
header:
  overlay_color: "#5e616c"
  overlay_image: travelbanner.jpg
  cta_label: "<i class='fa fa-download'></i> Install Now"
  cta_url: "/docs/quick-start-guide/"
  caption:
excerpt: 'A flexible two-column Jekyll theme. Perfect for personal sites, blogs, and portfolios hosted on GitHub or your own server.<br /> <small>Currently at Version 3.2.10</small><br /><br /> {::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
feature_row:
  - image_path: mm-customizable-feature.png
    alt: "customizable"
    title: "Super Customizable"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/configuration/"
    btn_label: "Learn More"
  - image_path: mm-responsive-feature.png
    alt: "fully responsive"
    title: "Responsive Layouts"
    excerpt: "Built on HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_label: "Learn More"
  - image_path: mm-free-feature.png
    alt: "100% free"
    title: "100% Free"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it, whatever!"
    url: "/docs/license/"
    btn_label: "Learn More"
github:
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
intro:
  - excerpt: 'Get notified when I add new stuff &nbsp; [<i class="fa fa-twitter"></i> @mmistakes](https://twitter.com/mmistakes){: .btn .btn--twitter}'
gallery:
  - url: AdobeStock_52363215.jpeg
    image_path: AdobeStock_52363215.jpeg
    alt: "gallery image 1"
    title: "Tips Image 1"
  - url: Dollarphotoclub_103212682.jpg
    image_path: Dollarphotoclub_103212682.jpg
    alt: "gallery image 2"
    title: "Tips image 2"
  - url: Dollarphotoclub_62017074.jpg
    image_path: Dollarphotoclub_62017074.jpg
    alt: "gallery image 3"
    title: "Tips image 3"
  - url: Dollarphotoclub_69824143.jpg
    image_path: Dollarphotoclub_69824143.jpg
    alt: "gallery image 4"
    title: "Tips image 4"
---

{% include feature_row id="intro" type="center" %}

{% include base_path %}

{% include home_posts.html %}

{% include home_tips.html %}

{% include gallery %}


