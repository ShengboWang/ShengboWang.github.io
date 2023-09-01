---
title: "Literature Review by Codes"
last_modified_at: 2023-08-20
permalink: /blog/literature-review-code
header:
  overlay_color: "#333"
# classes: wide
author_profile: false
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
toc_sticky: true
categories:
  - Techniques
tags:
  - coding
  - research tools
---

<!-- Simplify literature-review processes using python. -->

It always bothers me that a huge number of related papers show out when I search a few keywords in a web search engine such as the Google Scholar and IEEE. Among these engines, I found Semantic Scholar very helpful since it provides a free API for us to request directly by codes and save the outputs locally. At a first glance, it further complicates the reviewing processes. Let’s see how it can facilitate the entire processes.

### Prerequisites
Recently, I am preparing an overview subject to the design of control barrier function method towards different kinds of uncertainty. 

**Note:** I recommend collecting papers with selected keywords `after` rather than `during` a systematic investigation of research problems, to have a good taste for filtering high related/quality candidates.
{: .notice--warning}

### Collect raw data from requests
#### index with range

```python
print("Hello, world!")
for i in range(10):
    print(i)
```
#### operation with json format