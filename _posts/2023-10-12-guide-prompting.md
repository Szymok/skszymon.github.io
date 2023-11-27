---
layout: post
title: Wstęp do Promptingu
date: 2023-10-12 20:55:12
description: Jak, dlaczego i jakich używać taktyk pisania promptów
tags: prompt basics prompting chatgpt llm
categories: prompt-engineering
giscus_comments: true
featured: false
toc:
  sidebar: left
---
{% include figure.html path="assets/img/F7iibfCWwAAikHc.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    Obraz wygenerowany przy pomocy Midjourney
</div>

# Uczenie się Sztuki Promptingu: Jak Twój Blog Może Stać Się Akademią AI

W dobie cyfrowej rewolucji, gdzie algorytmy kształtują nasz świat w niezliczonych, niewidocznych sposobach, istnieje jedna umiejętność, która wyróżnia się jako klucz do efektywnego wykorzystania potencjału sztucznej inteligencji: *prompting*. Wprowadzając na swój blog serię lekcji poświęconych tej fascynującej dyscyplinie, chcę otworzyć Ci drzwi do świata, gdzie granice między ludzką kreatywnością a maszynową precyzją stają się coraz bardziej płynne.

W świecie, gdzie AI coraz bardziej przenika nasze codzienne życie, umiejętność efektywnego komunikowania się z maszynami jest nie tylko cenna, ale wręcz niezbędna. Chciałym stać się przewodnikiem w tej ekscytującej podróży. Te lekcje to nie tylko szansa na naukę, ale również okazja do otwarcia dyskusji, wymiany doświadczeń i wspólnego rozwoju.

Zapraszam Cię do wstąpienia w świat promptingu, gdzie każde pytanie staje się kluczem do nowej wiedzy, a każda odpowiedź otwiera nowe możliwości. Ta seria artykułów to nie tylko przewodnik, to twoja mapa na drodze do opanowania sztuki dialogu z AI. Razem odkryjemy, jak za pomocą prostych poleceń możemy kształtować, uczyć i współpracować z inteligentnymi systemami, odkrywając nowe horyzonty możliwości.

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


