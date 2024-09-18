---
layout: post
title: Standardy danych. Czym są i dlaczego są ważne? Analiza
date: 2024-09-18 23:30:21
description: Ale czym są te standardy danych? Dlaczego są ważne? Jakie są ich korzyści?
tags: data-governance data-standards iso-standards 
categories: data-governance
giscus_comments: true
featured: false
toc:
  sidebar: left
---

# Standardy danych: Czym są i dlaczego są ważne? Analiza

Wielką przyjemnością wprowadzamy analizę dotyczącą standardów danych i ich znaczenia w praktyce. Niniejszy artykuł jest częścią naszych wysiłków na rzecz formułowania regionalnych standardów dla danych oraz procesów z nimi związanych, w tym przepisów prawa.

## Cel standardów danych

Celem inicjatywy TransparenCEE jest wzmocnienie sektora technologii obywatelskiej w Europie Środkowej i Wschodniej. Budujemy fundamenty dla współpracy, częściowo poprzez proponowanie standardów danych, które będą stosowane w projektach wspólnych. Współpraca między różnymi absurdami przekłada się na lepszą jakość i efektywność wymiany informacji.

## Czym są standardy danych?

Wyobraź sobie pracę magisterską, którą musisz napisać na studiach. Składa się ona z tytułu, streszczenia, samego tekstu pracy i bibliografii. Jest napisane w ramach Twojego programu studiów i weryfikowane przez innych. Należy więc wskazać uniwersytet, wydział, promotora oraz recenzenta. Powinny być również dostępne logi audytowe: data stworzenia, data ostatniej modyfikacji, data zaakceptowania przez recenzenta (oraz jego/opinii) i data zaakceptowania przez promotora.

Przypuśćmy, że chcesz stworzyć narzędzie do przeglądania prac magisterskich na dowolny temat. Musisz zgromadzić znaczną liczbę takich prac i wprowadzić je do komputera, co wymaga przekształcenia ich w jedną rekord danych. Planowanie, jak ten rekord danych będzie wyglądał, nazywamy modelowaniem.

**Modelowanie** polega na przekształceniu rzeczywistych przykładów w rekordy danych. Można pominąć nieistotne szczegóły (jak na przykład, czy opublikowałeś pracę w wersji miękkiej, czy twardej), ale kluczowe jest jednak określenie wymagań. Niezbędna jest współpraca interesariuszy w tej fazie, gdyż różne konteksty muszą być zrozumiane.

## Od modelowania do reprezentacji i interoperacyjności

Tworzenie standardów danych polega na interoperacyjności: zdolności do wymiany standaryzowanych danych między systemami należącymi do różnych podmiotów. Aby to się udało, może być konieczne **reprezentowanie** danych, które wiąże się z podejmowaniem decyzji, jakie formaty plików użyć oraz jak formatować daty.

### Przykłady reprezentacji danych

Oto kilka przykładów tego samego kontentu reprezentowanego w popularnych formatach:

**JSON** (preferowany w rozwiązaniach skryptowych)
```json
{
  "author": {"given_name": "Krzysztof", "family_name": "Madejski"},
  "title": "Standardy danych: Czym są i dlaczego są ważne?",
  "date_of_final_accept": "2016-01-29"
}
```

**CSV** (można otworzyć w arkuszu kalkulacyjnym, ale nie obsługuje zagnieżdżonych obiektów)
```
author_given_name, author_family_name, title, date_of_final_accept
Krzysztof, Madejski, Standardy danych: Czym są i dlaczego są ważne?, 2016-01-29
```

**XML** (preferowany przez większe instytucje)
```xml
<thesis>
  <author>
    <given_name>Krzysztof</given_name>
    <family_name>Madejski</family_name>
  </author>
  <title>Standardy danych: Czym są i dlaczego są ważne?</title>
  <date_of_final_accept>2016-01-29</date_of_final_accept>
</thesis>
```

Te pliki mogą być następnie przetwarzane przez komputery.

## Standaryzacja standardów

Co by się stało, gdybym stworzył i ogłosił standard taki jak "Madejski Thesis Standard 1.0"? Prawdopodobnie nikt by nie zwrócił na to uwagi. Siła standardu polega na tym, że jest używany przez wielu interesariuszy. Jeśli nie jest powszechnie stosowany, to w rzeczywistości nie jest standardem.

### Kluczowe elementy standardów

Kolejnym kluczowym elementem standardów jest ich otwartość. Nie istnieje jedna definicja tego, co stanowi otwarty standard. Istnieje wiele definicji, które podkreślają różne aspekty otwartości, w tym otwartość specyfikacji czy procesu jej tworzenia.

Z sugestywną definicją, pochodzącą od World Wide Web Consortium (W3C), zalecamy uwzględnienie następujących wymagań:
- **Przejrzystość**: proces powinien być publiczny, a decyzje dokumentowane.
- **Relewancja**: nowa standaryzacja powinna wynikać z analizy potrzeb rynkowych.
- **Otwartość**: każdy może brać udział w tworzeniu standardów.
- **Bezstronność i konsensus**: proces decyzyjny powinien być sprawiedliwy.
- **Dostępność**: darmowy dostęp do tekstów standardów.
- **Utrzymanie**: ciągły proces testowania i aktualizacji.

Zaangażowanie społeczeństwa obywatelskiego w standardy (działania, korzystanie z nich, a także udział w ich tworzeniu) powinno iść w parze z zapewnieniem, że społeczności mają głos w tych standardach.

## Jak otworzyć dane?

Otwarcie danych jest procesem kosztownym. Kiedy robimy to w dobrej wierze, pamiętajmy, aby oprócz stworzenia narzędzia do przetwarzania danych również udostępnić same dane.

### Opcje udostępniania danych

1. **Eksport danych**: Można wyeksportować dane i publikować je w formie pliku. Każdy może je pobrać. W przypadku, gdy dane się zmieniają, warto zorganizować automatyczne okresowe eksporto (co miesiąc lub codziennie).

2. **API**: Interfejs Programowania Aplikacji (API) jest bardziej złożoną opcją, umożliwiającą innym programom komputerowym dostęp do danych.

**Wskazówka**: API również powinny być standaryzowane, tak jak dane, które udostępniają.

## Analizowane aspekty

W ramach tego projektu będziemy analizować i rekomendować standardy danych, które będą stosowane w obszarze technologii dla przejrzystości. Każdy standard zostanie przedstawiony w kontekście zastosowań, narzędzi open source, zasięgu jego stosowania oraz wyzwań dotyczących modelowania danych.

### Zakończenie

Standardy danych nie tylko poprawiają jakość informacji, ale także umożliwiają efektywną współpracę między różnymi podmiotami. Zrozumienie ich znaczenia jest kluczowe dla budowania lepszego etosu współpracy w obszarze technologii obywatelskiej oraz na rzecz przejrzystości danych.