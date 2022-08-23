# Lista Projektów OSMP by Cristoffs.

Pytaliście, to odpowiadam. Plany na przyszłość oraz raport z aktualnych projektów. W ramach większości z nich potrzebne są ręce i głowy do pomocy. Jeśli chcecie aktywnie wspomóc działania Stowarzyszenia, zapraszam do kontaktu. Często wystaczą chęci i trochę wolnego czasu, zawsze możesz liczyć na pomoc w zaresie zdobywnia nowej wiedzy i umięjetności.
Strona jest podsumowaniem planowanej działalności i będzie aktualizowna.

## Projekty w trakcie realizacji.

### Otwarta mapa AED na Świecie

Zachęceni sukcesem polskiej mapy dostępnej pod adresem aed.openstreetmap.org.pl pokusiliśmy się o rozszerzenie zasięgu działania projektu, tak by zwiększyć zaangażowanie społeczności w zakresie wprowadzania danych urządzeń AED do zasobów OpenStreetMap.

1. [x] Pozyskanie adresu opemaedmap.org, pod którym strona będzie funkcjonować.
2. [ ] Przepisanie mapy z udziałem technologi React i wdrożenie nowych funkcjonalności. (wer. Dev zrobiona dzięki! Taraś i Ancymon!)  [Link](https://aed.openstreetmap.org.pl/dev/#map=3.93/50.71/19.73)
      - Przygotowanie strony ze stastystykami w rozbiciu na kraje.
      - Umożliwenie pobierania danych dla poszczególnych krajów.
      - Przygotowanie modułu dzięki któremu będzie możliwe dodawanie zdjęć urządzeń
      - Ulepszenie i rozbudowanie formularza, który  pozwoli na dodawanie danych urządzeń z poziomu strony, bez koniecznosci znajomosci zasad edytownia.
3. [ ] Przetłumaczenie interfacu na inne języki.
4. [ ] Pozyskanie żródeł finansowania projektu ze szczególnym uwzglednieniem zasobów informatycznych.

> Potrzebujemy chętnych, którzy w ramach wolontariatu będą wspierać stowarzyszenie w tym zakresie z umiejętnościami w tworzeniu  projektów przy pomocy React JS.

> Potrzebujemy pomocy przy tłumaczeniu na inne języki niz angielski, szczególnie zaleźy nam na francuskim, niemieckim i hiszpańskim.

### Porządkowanie i aktualizacja adresów na terenie Polski, weryfikacja PRG

Projekt bardzo ambitny, na który składa się kilka związanych ze sobą działań. Począwszy od prostych działań w postaciu usuwania nieaktualnych oraz zduplikowanych adresów z bazy OSM, a kończąc na opracowaniu narzędzi pozwalających na automatyczne wykrywanie takich błędów i miejsc, w których nalezy dokonać aktualizacji.

1. W ramach projektu chcielibyśmy opracować narzędzie do automatycznego znajdownia problemów z adresami zarówno w przypadku OSM jak i PRG, funkcjonalność zakładana jest obecnie na poziomie:
      - [ ] Zgodność bazy PRG z rozporządzeniem w sprawie ewidencji miejscowości, ulic i adresów w tym:
            - [ ] Duplikaty pkt. adresowych
            - [ ] Stosowania niedopuszczonych duplikatów "a" oraz "A"
            - [ ] Obiekty bez nadanych adresów
            - [ ] Adresy bez kodów pocztowych
      - [ ] Weryfikacja poprawności bazy danych adresowych w OSM
      - [ ] Narzędzie do prowadzenia aktualizacji danych OSM w zakresie zmian adresownia w tym:
            - [ ] wprowadzenie ulic w miejscowościach
            - [ ] dodania nowych adresów
            - [ ] dodania kodów pocztowych do adresów i weryfikacja ich poprawności.
2. Obecnie funkcjonują także zadania utworzne na portalu [MapRoulette](https://maproulette.org/browse/projects/43149), w których można usunąć wykryte i zduplikowane punkty adresowe oznaczone tagiem *fixme*

> [Repo](https://github.com/cedaross/address_error_finder) projektu jest dostepne i zapraszam do udziału.
> Każdy może pomóc, rozwiązując zadania dostęne an [MapRoulette](https://maproulette.org/browse/projects/43149)
### (MAD - Making a difference) Mapowanie dla osób niepełnosprawnych.

Dane, które wprowadzamy do OpenStreetMap, są używane przez większośc producentów oprogramowania dla niepełnosprawych, wspierając ich mobilność oraz przyczyniając sie do likwidacji barier komunikacyjnych. Z tego powodu będę chciał budować tę świadomość wśród edytorów oraz przygotować specjalne materiały edukacyjne ułatwiające edytownie z uwzględnieniem danych istotnych dla osób niepełnosprawnych.

Obecnie w ramach projektu wspieramy inicjatywę [OSM Integrator](https://osmintegrator.eu), dzięki której jest możliwe integrowania danych OSM z danymi przewożników komunikacji miejskiej, co ma ogromne znaczenie dla osób niewidomych i ułatwia im poruszanie w przestrzeni publicznej. Projekt ogranicza się do przestrzeni aglomeracji katowickiej, natomiast mamy nadzieję na szybkie wdrożenie tego rozwiązania w innych miatstach w Polsce.

### Ankieta dla członków i kandydatów stowarzyszenia (Zobowiązanie po walnym zebrania Żywiec 2022)

Obecnie ankieta została przygotowana i skonsultowana z najbardziej aktywnymi członkami stowarzyszenia i zarządem. Jestem w tracie przygotowania pisma przewodniego i mam nadzieję, że pod koniec września po zatwierdzeniu na najblizszym zebraniu członków bedzie można ten projekt sfinalizować.

### Konferencja OSM 2023

Jest to zobowiązanie nałożone przez czlonków stowarzyszenia na zarząd na oststnim walnym zebraniu. Obecnie jesteśmy na etapie tworzenia wstępnych założeń oraz konsultownia terminu samego wydarzenia.

> Potrzebujemy chętnych do pomocy w oragnizacji tego wydarzenia. Warunkiem koniecznym jest mieszkanie na terenie Łodzi i dysponowanie wolnym czasem ze szczególnym uwzględnieniem termiów w czerwcu 2023 r.
Nieustający program tłumaczenia. Brawa należą się Konradowi, dzięki któremu możememy czytać po polsku nasz osmowy newsletter. Ciągle poszukujemy chętnych, którzy wspomogą jego pracę i pomogą w tłumaczeniu. Znasz angielski? Pomóż tłumaczyć! I już.

### Zapewnienie lepszego zaplecza technicznego dla osmmapa.pl
Staramy się pozyskać partnera, który zapewni lepszy serwer umożliwiający działanie mapy i podkładu w dłuzszym czasie.


## Projekty na wczesnym etapie planownia

### Mapowanie miejsc biwakowych

Włączenie do zasobów OSM danych dotyczących lokalizacji wyznaczonych miejsc biwakowych na terenie Lasów Państwowych dostępnych na ich stronach.

> Potrzebni chętni edytorzy potrafiący sprawnie edytować i tworzyć relacje.
### Przygotowanie autorskiego podkładu "Ratunkowego" do użycie w projekcie openaedmap.org

Przy pracy nad projektem openaedmap zrodził się pomysł utworzenia autorskiego podkładu uwzględniającego dane obiektów przydatnych w zastosowniach ratunkowych. Obecnie są tworzone założenia takiego podkładu i zbieranie chętnych do udziału w projekcie. 


## Projekty już zrealiowane (nawet częściowo).

1. Mapa AED w Polsce [wiki projektu](https://wiki.openstreetmap.org/wiki/Organised_Editing/Activities/AED_mapping_campaign_in_Poland)
2. Aktualizacja danych szkół na terenie Polski (Dane wprowadzane obecnie w projekcie mapowania dla Ukrainy) [wiki projektu](https://wiki.openstreetmap.org/wiki/Organised_Editing/Activities/Updating_and_mapping_schools_in_Poland)


## Projekty planowane, bez aktywnych działań.

### Program dodawania i aktualizownia POI - OSM for Bussines

Wykorzystanie technologii opracowanych w ramach projektów związanych z AED do umożliwenia dodawania i aktualizacji POI w określonych branżach. Obecnie ze względu na ograniczone zasoby poza założeniami roboczymi nie są w tym kierunku prowadzone żadne działąnia.

## Projekty obecnie wstrzymane

### Podręcznik JOSM
Ze względu na brak czasu projekt wstrzymany do października 2022 r.

### Aktualizacja strony [OSMP na wiki](https://wiki.openstreetmap.org/wiki/Stowarzyszenie_OpenStreetMap_Polska)
Ze względu na brak czasu projekt został wstrzymany.

### Oprogramowanie do importu i włączania danych zewnętrznych do OSM oraz aktualizacji (NieWnen)
Nie ma obecnie konieczności i parcia na utworzenie takiego projektu ze względu na niewielkie zainteresowanie podmiotów dysponującymi takimi danymi.

### Wprowadzanie danych oraz lokalizacji paczkomatów. [wiki projektu](https://wiki.openstreetmap.org/wiki/Organised_Editing/Activities/mapping_parcel_lockers_in_Poland)

Ze zwględu na brak wspólpracy ze strony największego operatora na rynku (InPost) i kontrowersji licencyjnych projekt został wstrzymany do odwołania.

## Luźna lista pomysłów

- aktualizacja kategorii dróg ze szczególną weryfikacja "track"
- Human Centered Map
- weryfikacja topologi obiektów oznaczony "source"="Bing"
- landuse w małych miejscowościach
- oprogramowanie do weryfikacji jakości danych
- watcher POI
- sprzątanie mega - landuse
- podręcznik / instrukcja / standard dla firm i instytucji chcących właczyć dane w zasoby OSM
- wiki - temat rzeka

## Zobowiązania nalożone przez członków OSMP na zarząd na walnym Źywiec 2022

1. Zorganizowanie ogólnopolskiej konferencji OSMP (w trakcie).
2. Stworzenie i rozesłanie ogólnopolskiej ankiety dotyczącej obszarów zaangazowania (w trakcie).
3. Wsparcie Syntexa w udziale w DWG.
4. Analiza konieczności podwyższenia składki członkowskiej. 
5. Zaciśnienie współpracy z uczelniami wyźszymi.
6. zwiekszenie rozpoznawalności OSMP i projektu OSM poprzez udział w wydarzeniach branżowych.

## Wolne wnioski po walnym Źywiec 2022

1. Powołanie Community Menagera do spraw wspólpracy ze społecznością.
2. Sformalizowaniu CRM do pracy w stowarzyszeniu.
3. Wsparcie członków w edycji granic administracyjnych w PL.
4. Przygotowanie szkoleń z podstaw Qgis.
5. Lepsza komunikacja zarządu z członkami.
6. Przygotowanie platformy szkoleniowej dla członków stowarzyszenia.
