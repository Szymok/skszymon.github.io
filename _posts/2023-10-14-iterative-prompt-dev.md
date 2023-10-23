---
layout: post
title: Wstęp do Promptingu
date: 2023-10-03 03:21:12
description: 
tags: prompt, basics, prompting, chatgpt, llm
categories: paper
giscus_comments: true
featured: false
toc:
  sidebar: left
---
{% include figure.html path="assets/img/F7iibfCWwAAikHc.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    Obraz wygenerowany przy pomocy Midjourney
</div>

# Wstęp do promptingu
W tej lekcji przećwiczysz dwie zasady promptowania i związane z nimi taktyki, aby napisać skuteczne podpowiedzi dla dużych modeli językowych.

## Setup
#### Załaduj klucz API i odpowiednie biblioteki Pythona.

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/l2-guidelines.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/l2-guidelines.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
