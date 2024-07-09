---
layout: post
title: AWS a linie lotnicze, jak to działa? 
date: 2023-06-25 08:42:12
description: Krótkie przedstawienie usług AWS, które pomagają w przypadku problemów na lotnisku.
tags: analiza-danych aws amazon s3 lambda airport lotnisko technologia machine-learning
categories: article
giscus_comments: true
toc:
  sidebar: left
---

## Wstęp
Choć to historia mogłaby wydawać się jak scena z filmu, jest to tylko wymyślony scenariusz, stworzony na potrzeby tego artykułu. Celem tego opisu jest zilustrowanie, jak łatwo można przegapić lot, gdy nie jesteśmy świadomi konsekwencji niezauważenia upływu czasu na lotnisku.*

Grupa przyjaciół przybyła na Lotnisko Chopina w Warszawie z dużym wyprzedzeniem przed planowanym odlotem. Byli podekscytowani zbliżającą się podróżą do Nowego Jorku - mieli spędzić tam dwa tygodnie, zwiedzając miasto i ciesząc się amerykańskim stylem życia. Po odprawie bagażu, kontroli bezpieczeństwa i przepustkach imigracyjnych, zdecydowali się na krótki odpoczynek w jednej z restauracji lotniska. 

Czas mijał niezauważenie, kiedy rozmawiali, jedli i śmiali się, nieświadomi tego, że ich samolot miał odlecieć za niecałą godzinę. Gdy w końcu spojrzeli na zegarek, zrozumieli, że nie mają już czasu na luzie dotrzeć do bramki. Zgromadzili swoje rzeczy i w pośpiechu ruszyli w kierunku bramki. 

Linie lotnicze rozpoczęły procedurę wejścia na pokład na godzinę przed planowanym odlotem, a ta zakończyła się w ciągu 30 minut. Jednak grupa przyjaciół była nadal nieobecna. Mimo wielokrotnych ogłoszeń, aby zgromadzili się przy bramce, nie było żadnej reakcji. Pracownik linii lotniczych, nie mogąc ich znaleźć, poinformował o tym swoich przełożonych. Bramka została zamknięta, a samolot wystartował 10 minut przed planowanym odlotem.

Grupa przyjaciół dotarła do bramki 5 minut przed planowanym odlotem. Z przerażeniem zobaczyli, że bramka jest już zamknięta, a samolot zaczyna się oddalać. Zrozumieli, że przegapili swój lot. Byli załamani, że ich długo planowane wakacje zostały nagle zrujnowane. 

Podszedł do nich pracownik lotniska i wyjaśnił, że powinni byli być przy bramce co najmniej 30 minut przed odlotem. Z ciężkim sercem zarezerwowali nocleg w hotelu lotniskowym, zdecydowani na złapanie następnego lotu do Nowego Jorku. 

Tak jak w wielu przypadkach, przegapienie lotu przez tę grupę przyjaciół to kolejny przykład na to, jak łatwo można przecenić czas potrzebny na dotarcie do bramki, zwłaszcza jeżeli przemawiają do nas różnego rodzaju rozproszenia.

***
## Wyzwania związane z bookowaniem lotów

Nie jest rzadkością, że pasażerowie spóźniają się na swój lot, nawet po otrzymaniu karty pokładowej, jak mogliśmy zobaczyć w powyższej anegdocie. Istnieje kilka powodów, dlaczego tak się dzieje.
<ul>

<li> Niedoszacowanie wymaganego czasu: Pasażerowie mogą nie zdawać sobie sprawy, ile czasu potrzebują, aby dotrzeć do bramki, zwłaszcza jeśli nie znają lotniska lub mają do pokonania duże odległości. Mogą również niedoszacować czasu potrzebnego na kontrole bezpieczeństwa i inne procedury.</li>

<li> Opóźnienia lotów: Nawet jeśli została wydana karta pokładowa, loty mogą być opóźnione z różnych powodów, takich jak pogoda, problemy techniczne lub zator ruchu lotniczego. Pasażerowie mogą nie zdawać sobie sprawy, że ich lot został opóźniony i przegapić czas wejścia na pokład.</li>

<li> Wolne wejście na pokład: Proces wejścia na pokład może potrwać długo, zwłaszcza jeśli pasażerowie nie stosują się do instrukcji linii lotniczych. To może prowadzić do opóźnień, utraty połączeń i innych problemów.</li>

<li> Problemy z bezpieczeństwem: Pasażerowie mogą mieć problemy z bezpieczeństwem, takie jak niemożność zabrania określonych przedmiotów na pokładzie lub konieczność dodatkowej kontroli. To może powodować opóźnienia.</li>

<li> Problemy komunikacyjne: Linie lotnicze mogą nie dostarczać jasnych instrukcji ani nieefektywnie komunikować się z pasażerami podczas procesu wejścia na pokład. Nagłe zmiany bramek mogą prowadzić do zamieszania i opóźnień.</li>
</ul>

Interesujące jest, że w ostatnich latach lotniska na całym świecie wprowadzają nowoczesne technologie, takie jak sztuczna inteligencja, chmura obliczeniowa i uczenie maszynowe, aby zapobiec sytuacjom, w których pasażerowie przegapiają swoje loty. Dzięki wykorzystaniu zaawansowanych algorytmów i analizie danych, te technologie mogą pomóc w zoptymalizowaniu procesów lotniskowych i minimalizacji opóźnień.

Przykładem jest wykorzystanie sztucznej inteligencji do prognozowania czasu potrzebnego na przejście przez kontrolę bezpieczeństwa. Za pomocą analizy danych historycznych, algorytmy mogą przewidzieć, jak długo zajmie pasażerom przejście przez kontrolę i ustalić optymalne czasy przybycia na lotnisko.

Chmura obliczeniowa jest również wykorzystywana do przechowywania i przetwarzania ogromnych ilości danych związanych z lotniskami. Dzięki temu, informacje o lotach, pasażerach, bagażach i innych czynnikach mogą być łatwo dostępne i szybko przetwarzane, co pozwala na lepsze zarządzanie operacjami lotniska.

Uczenie maszynowe również odgrywa istotną rolę w zapobieganiu przegapieniu lotów. Algorytmy uczą się na podstawie danych historycznych i aktualnych, identyfikują wzorce i czynniki ryzyka, które mogą prowadzić do opóźnień lub przegapienia lotu. Dzięki temu, systemy mogą ostrzegać personel lotniska i pasażerów o potencjalnych problemach i proponować działania zaradcze.

To fascynujące, jak nowoczesne technologie mogą pomóc w poprawie doświadczenia podróżowania lotniczego i minimalizacji ryzyka przegapienia lotu. Warto śledzić rozwój tych rozwiązań i być na bieżąco z innowacjami w branży lotnictwa.

***

## Możliwości jakie daje AI i ML

Sztuczna inteligencja i uczenie maszynowe mogą pomóc w rozwiązaniu większości z powyższych problemów. Wykorzystajmy tę samą anegdotę, aby zobaczyć jak.

Podróżująca grupa przyjaciół z niecierpliwością czekała na wizytę u swojej rodziny w Ameryce przez wiele miesięcy. Przybyła na lotnisko w Dubaju na cztery godziny przed swoim lotem, odprawiła bagaż i przeszła przez kontrole imigracyjne i bezpieczeństwa. Ponieważ miała kilka godzin do wylotu, postanowiła zrobić trochę zakupów i zjeść coś. Jednak straciła poczucie czasu i nie wiedziała, że powinna dotrzeć do bramki na 30 minut przed planowanym odlotem samolotu.

Na szczęście lotnisko miało system bookingu oparty na AI, który gwarantował bezproblemowe bookowanie wszystkich pasażerów. System ten wykorzystywał Internet rzeczy (IoT) i uczenie maszynowe do śledzenia ruchów pasażerów na lotnisku i szacowania ich czasu przybycia do bramki.

Kiedy system przewidział, że przyjaciele mogą się spóźnić, natychmiast zaalarmował pracowników bramki i personel linii lotniczych, aby ich zlokalizować. System ten wykorzystywał technologię rozpoznawania twarzy i inne technologie śledzenia, aby precyzyjnie zlokalizować ich miejsce na lotnisku, a w ciągu kilku minut pracownik lotniska był w stanie ich znaleźć i odprowadzić do bramki.

Spóźnieni mogli bezproblemowo wejść na pokład swojego lotu, a także cieszyć się zrobionymi zakupami - wszystko to dzięki bezproblemowemu i efektywnemu procesowi bookingu, który umożliwiły AI, IoT i uczenie maszynowe.

Fakty są takie, że technologia AI i uczenie maszynowe stają się coraz bardziej niezbędne w świecie lotnictwa. Możemy oczekiwać, że tego typu systemy staną się coraz bardziej powszechne w przyszłości, zapewniając lepszą organizację i wygodę dla pasażerów. Ciekawe jest to, jak technologia może przekształcić prozaiczne zadania, takie jak czekanie na lot, w bardziej przyjemne i bezstresowe doświadczenia. W przyszłości możemy spodziewać się jeszcze więcej innowacyjnych rozwiązań z wykorzystaniem AI, IoT i uczenia maszynowego w branży lotniczej. 

***

## AWS: AI, ML, analiza danych i IoT w branży lotniczej

Opisane powyżej bezproblemowe bookowanie na lot można łatwo zrealizować, wykorzystując usługi AWS Cloud. Dostępnych jest wiele urządzeń IoT, które mogą śledzić ruchy pasażera czy personelu lotniczego za pomocą geofencingu i BLE (Bluetooth o niskim zużyciu energii). 

Na przykład, beacony mogą pokryć obszar od 5m do 2,5km. Wysyłają one sygnały do urządzeń, takich jak telefony komórkowe, które są mapowane z ich lokalizacją. Te informacje są przechowywane w AWS RDS, co pomaga w detekcji lokalizacji pasażera. Można także wykorzystać kamery do śledzenia ruchów.

AWS oferuje szereg usług AI, ML, analizy danych i IoT (Internet rzeczy), które można wykorzystać do budowania inteligentnych i opartych na danych aplikacji. 

Do stworzenia bezproblemowego rozwiązania bookowania na lot można wykorzystać następujące usługi:

<ul>
<li> Amazon SageMaker: To kompleksowo zarządzana usługa, która dostarcza deweloperom i naukowcom narzędzi do budowania, trenowania i wdrażania modeli uczenia maszynowego na dużą skalę.</li>

<li> Amazon Rekognition: Usługa analizy obrazów i wideo oparta na głębokim uczeniu, która może wykrywać obiekty, twarze i tekst na obrazach i wideo.</li>

<li> Amazon Comprehend: Usługa przetwarzania języka naturalnego, która może analizować tekst i wydobywać z niego informacje takie jak sentyment, jednostki i kluczowe frazy.</li>

<li> Amazon Polly: Usługa text-to-speech, która może przekształcać tekst w realistyczne mowy w wielu językach i głosach.</li>

<li> Amazon Translate: Usługa tłumaczenia maszynowego oparta na sieciach neuronowych, która może tłumaczyć tekst między językami z dużą precyzją.</li>

<li> Amazon Transcribe: Usługa automatycznego rozpoznawania mowy, która może transkrybować pliki audio i wideo na tekst.</li>

<li> Amazon Forecast: Kompleksowo zarządzana usługa prognozowania, która wykorzystuje uczenie maszynowe do dostarczania wysoce precyzyjnych prognoz.</li>

<li> Amazon Personalize: Usługa, która zapewnia rekomendacje w czasie rzeczywistym dotyczące treści, produktów i usług, wykorzystując algorytmy uczenia maszynowego.</li>
</ul>

***

## Amazon SageMaker - budowanie, trenowanie i wdrażanie modeli uczenia maszynowego

Amazon SageMaker to potężna platforma uczenia maszynowego z standardowym interfejsem, która dostarcza kompletny zestaw narzędzi i usług do szybkiego budowania, trenowania i wdrażania modeli uczenia maszynowego na dużą skalę. SageMaker wykorzystuje kontenery do opakowania ulubionych algorytmów i frameworków, w tym wbudowanych algorytmów takich jak XGBoost, DeepAR i FM, a także frameworków takich jak PyTorch, SKLearn i TensorFlow.

Niektóre z kluczowych usług dostarczanych przez Amazon SageMaker to:
<ul>

<li>Etykietowanie danych: Ground Truth w SageMakerze to w pełni zarządzana usługa etykietowania danych, która ułatwia etykietowanie zestawów danych za pomocą anotatorów ludzkich lub wbudowanych modeli uczenia maszynowego.</li>

<li>Budowanie modeli: SageMaker oferuje szereg wbudowanych algorytmów i frameworków do budowania, trenowania i wdrażania modeli uczenia maszynowego. Obsługuje także tworzenie niestandardowych algorytmów przy użyciu popularnych frameworków takich jak TensorFlow, MXNet i PyTorch.</li>

<li>Trenowanie modeli: SageMaker zapewnia skalowalne i rozproszone środowisko treningowe (z wykorzystaniem GPU i wielu instancji), które pomaga w trenowaniu efektywnych modeli uczenia maszynowego na dużych zbiorach danych.</li>

<li>Hostowanie modeli: SageMaker zapewnia w pełni zarządzane środowisko hostowania modeli, umożliwiające deweloperom wdrażanie modeli uczenia maszynowego jako interfejsy API z automatycznym skalowaniem, monitorowaniem i możliwością debugowania.</li>

<li>Tuning modeli: Amazon SageMaker oferuje usługę automatycznego strojenia modeli, która umożliwia naukowcom danych optymalizację hiperparametrów i poprawę dokładności modelu bez konieczności ingerencji manualnej.</li>

<li>Wnioskowanie w czasie rzeczywistym: SageMaker zapewnia w pełni zarządzaną, wysoko dostępną usługę wnioskowania w czasie rzeczywistym, która może skalować się, aby obsłużyć miliony żądań na sekundę.</li>

<li>Wnioskowanie wsadowe: Amazon SageMaker dostarcza w pełni zarządzaną usługę wnioskowania wsadowego, która może przetwarzać duże ilości danych i dostarczać predykcje w sposób kosztowo efektywny. Pełny workflow uczenia maszynowego: Amazon SageMaker zapewnia pełen workflow uczenia maszynowego, obejmujący przygotowanie danych, inżynierię cech, trening modelu, wdrażanie i monitorowanie.</li>

<li>Integracja z innymi usługami AWS: Amazon SageMaker integruje się z innymi usługami AWS, takimi jak S3, Lambda, Step Functions i CloudFormation, aby zapewnić spójne doświadczenie z uczeniem maszynowym. Dzięki usługom Amazon SageMaker lotniska mogą skutecznie budować, trenować i wdrażać modele uczenia maszynowego, a także obsługiwać wnioskowanie w czasie rzeczywistym i wsadowe. To zapewnia płynne i efektywne procesy związane z analizą danych i predykcją, co ma zastosowanie w liniach lotniczych.</li>
</ul>

***

## Rola usług AWS Rekognition, IoT Core i Greengrass

W oparciu o infrastrukturę IoT, beacony i kamery mogą być zainstalowane w całym terminalu lotniska w celu wykrywania ruchów pasażerów. AWS Greengrass może być wykorzystany do wdrażania funkcji AWS Lambda, które przechwytują obrazy z lokalnych kamer/czujników i wysyłają je do AWS Rekognition w celu analizy. Kamery mogą przechwytywać obrazy lub nagrania wideo w regularnych odstępach czasu (co 5/10 sekund) i wysyłać je do bramy AWS IoT.

Zdolność do rozpoznawania twarzy w usłudze AWS Rekognition może być wykorzystana do analizy obrazów lub nagrań wideo, wykrywania obecności poszczególnych pasażerów oraz śledzenia ich ruchów. Na podstawie wyników analizy można generować alerty i wysyłać powiadomienia, jeśli w określonym obszarze występuje duże zagęszczenie pasażerów lub zatory, lub jeśli pasażer porusza się w kierunku niewłaściwej bramki.

Wyniki analizy mogą być przesyłane z powrotem do AWS Greengrass w celu dalszej obróbki lub podjęcia działań, takich jak uruchamianie lokalnych alarmów lub wysyłanie powiadomień. Dzięki temu systemowi możliwe jest bieżące monitorowanie ruchu pasażerów w terminalu lotniska, identyfikowanie problematycznych obszarów lub sytuacji oraz podejmowanie odpowiednich działań w celu zapewnienia płynnego przebiegu procesu zaokrętowania.

***

## Tworzenie opartego na AI/ML rozwiązania do obsługi lotu


Nasze rozwiązanie wykorzystuje algorytm XGBoost do binarnej klasyfikacji, popularny wybór do przewidywania wystąpienia zdarzenia na podstawie zestawu cech wejściowych. Staramy się przewidzieć, czy pasażer, który odprawił bagaż i robi zakupy, dotrze do bramki wejściowej 30 minut przed planowym czasem odlotu lotu. Wbudowany algorytm XGBoost w SageMaker ułatwia trenowanie i wdrażanie potężnych modeli uczenia maszynowego. Dzięki niewielkiemu przygotowaniu danych i dostrojeniu hiperparametrów, budowanie modeli, które szybko dokonują dokładnych prognoz w różnych zadaniach, jest prostym procesem. SageMaker dostarcza Jupyter Notebook w chmurze, który jest łatwy w tworzeniu i używaniu. Oto kroki postępowania:

<ul>
<li>Przygotowanie danych: Nasze dane powinny być w formacie, z którym XGBoost może pracować. Zazwyczaj oznacza to plik CSV z kolumnami dla cech i kolumną docelową dla etykiety.</li>

<li>Przesyłanie danych: Musimy przesłać dane do kubełka S3, aby SageMaker mógł na niego uzyskać dostęp.</li>

<li>Tworzenie zadania trenującego: Możemy utworzyć zadanie trenujące, określając lokalizację danych treningowych w S3/Datalake oraz hiperparametry, których chcemy użyć dla algorytmu XGBoost. Można to zrobić za pośrednictwem konsoli SageMaker, pakietu SDK SageMaker lub AWS CLL.</li>

<li>Monitorowanie zadania trenującego: Po rozpoczęciu zadania trenującego możemy monitorować jego postęp za pośrednictwem konsoli SageMaker lub pakietu SDK.</li>

<li>Wdrażanie modelu: Po zakończeniu zadania trenującego możemy wdrożyć wytrenowany model jako punkt końcowy, który może być używany do wnioskowania.</li>

<li>Testowanie modelu: Możemy przetestować wdrożony model, wysyłając nowe dane i obserwując predykcje, które generuje.</li>

</ul>
### Dane wejściowe
Dane wejściowe dla naszego modelu składają się z zestawu cech dotyczących ruchu pasażera w obrębie lotniska, jego zachowania podczas zakupów i czasu przybycia na lotnisko. Te cechy są zbierane za pomocą urządzeń IoT, takich jak kamery, beacons i czujniki rozmieszczone w całym lotnisku.

Oto cechy wejściowe, które zostały użyte w naszym modelu:

<ul>
<li>Czas przybycia: Dane dotyczące czasu, o którym pasażer przybywa na lotnisko, są zbierane od pasażerów, którzy już dokonali odprawy online. Czujniki IoT przy wejściu na lotnisko zbierają te dane i przekazują je do magazynu danych. Dla pasażerów, którzy nie dokonali odprawy online, dane te są gromadzone na stanowisku odprawy lub w automacie, z którego otrzymuje się kartę pokładową.</li>

<li>Stan pasażera: Informuje, czy pasażer przeszedł kontrolę imigracyjną, kontrolę bezpieczeństwa, odprawę itp.</li>

<li>Czas trwania zakupów: To jest czas, jaki pasażerowie spędzają na zakupach po otrzymaniu karty pokładowej i po przejściu kontroli imigracyjnej/bezpieczeństwa.</li>

<li>Odległość od bramki: To jest odległość między strefą zakupów a bramką wejściową i jest obliczana za pomocą czujników IoT rozmieszczonych w całej strefie wolnocłowej.</li>

<li>Czas przybycia na bramkę: To jest czas, o którym pasażer dociera na bramkę wejściową.</li> 

<li>Czas przewidywania będzie stale aktualizowany w innym rejestrze, aż pasażer dotrze do bramki wejściowej. Ciągłe alertowanie wiadomości zostanie wysłane na telefon komórkowy/smartfon pasażera oraz do sprzedawcy znajdującego się w pobliżu pasażera. W odpowiednim czasie zostanie poproszona o pomoc sprzedawcy w celu poinformowania pasażera o konieczności przemieszczenia się w kierunku bramki, aby wejść na pokład samolotu. Na telewizorze również pojawi się informacja dla pasażera o konieczności przemieszczenia się w kierunku bramki. Pasażer zostanie również oznaczony na mediach społecznościowych i poproszony o przemieszczenie się w kierunku bramki. Wszystko to będzie działo się automatycznie dzięki różnym usługom AWS AI/ML, IoT i innym.</li>

<li>Planowany czas odlotu: To jest zaplanowany czas odlotu lotu pasażera.</li>

<li>Opóźnienie lotu: Wskazuje opóźnienie w zaplanowanym czasie odlotu lotu pasażera.</li>

<li>Wzorzec chodu: Jest to wzorzec chodu zarejestrowany za pomocą urządzenia noszonego przez pasażera lub smartfona. Jeśli nie jest dostępny, zostanie użyta wartość domyślna.</li>

<li>Bagaż podręczny: Te dane będą zbierane podczas odprawy, ale mogą być niejednoznaczne ze względu na dodawanie zakupów.</li>

<li>Zatłoczenie terminala: To jest miara zajętości terminala w chwili przybycia pasażera na lotnisko i na drodze do bramki. Na urządzeniu smartfona pasażera wyświetlany będzie również mapę cieplną.</li>
</ul>

### Przygotowanie danych

Przed przystąpieniem do trenowania modelu przeprowadziliśmy kilka kroków przygotowawczych, jak następuje:

<b>Czyszczenie:</b> Usuwanie nieprawidłowych lub brakujących danych.

<b>Przetwarzanie wstępne:</b> Skalowanie cech liczbowych, aby mieć tę samą skalę, i normalizacja danych w celu poprawy wydajności modelu.

<b>Inżynieria cech:</b> Tworzenie nowych cech na podstawie istniejących danych w celu poprawy dokładności modelu.

### Trenowanie i wdrożenie modelu

Po przygotowaniu danych użyliśmy wbudowanego algorytmu XGBoost w Amazon SageMaker do trenowania naszego modelu klasyfikacji binarnej. Następnie wdrożyliśmy wytrenowany model za pomocą usługi wdrożenia modelu SageMaker, która automatycznie skaluje model, aby obsłużyć duże ilości ruchu.

### Integracja z urządzeniami IoT

Następnie zintegrowaliśmy wdrożony model uczenia maszynowego z urządzeniami IoT, takimi jak kamery i czujniki, aby monitorować ruchy pasażerów i przewidywać ich czasy przybycia na bramkę.

<b>System alarmowy:</b> Do zbudowania systemu alarmowego użyliśmy usługi Amazon Simple Notification Service (SNS), aby powiadamiać agentów bramkowych i personel linii lotniczych, gdy pasażerom przewidywane jest spóźnienie.

<b>System śledzenia:</b> Do zbudowania systemu śledzenia użyliśmy rozpoznawania twarzy i innych technologii śledzenia, aby zlokalizować pasażerów, którzy mają przewidywane opóźnienie i eskortować ich do bramki.

W sumie ta implementacja analizy predykcyjnej za pomocą SageMaker może pomóc liniom lotniczym optymalizować proces wejścia na pokład, przewidując, którzy pasażerowie mogą być zagrożeni spóźnieniem i podejmując proaktywne kroki, aby zapewnić, że dotrą na czas do bramki.

## Podsumowanie

Usługi AWS oferują różnorodne narzędzia i rozwiązania, które mogą zrewolucjonizować sposób działania lotnisk, prowadząc do znaczących popraw w obszarach efektywności, doświadczenia pasażera, bezpieczeństwa i zrównoważonego rozwoju. AWS IoT może usprawniać zarządzanie przepływem pasażerów, podczas gdy usługi uczenia maszynowego, takie jak Amazon SageMaker, mogą pomóc w przewidywaniu potencjalnych usterek w sprzęcie lotniskowym. Amazon Rekognition umożliwia bezproblemową odprawę i zwiększa bezpieczeństwo, a śledzenie bagażu w czasie rzeczywistym dzięki AWS IoT poprawia doświadczenia pasażerów. Z usługami analitycznymi AWS, takimi jak Amazon Redshift i Amazon Quicksight, lotniska mogą analizować ogromne ilości danych i podejmować świadome decyzje. Bezpieczne połączenia zapewnia AWS Direct Connect, a planowanie zasobów lotniska staje się bardziej efektywne dzięki mocy obliczeniowej chmury AWS. Zrównoważony rozwój jest również na wyciągnięcie ręki, dzięki zobowiązaniu Amazon do osiągnięcia 100% odnawialnego zużycia energii dla swojej globalnej infrastruktury.