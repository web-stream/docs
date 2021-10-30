# docs.webstream.dev


<details>
    <summary>Edit docs</summary>
    <ul>
        <li><a href="https://docs.webstream.dev/#/">docs.webstream.dev</a></li>
        <li><a href="https://github.com/web-stream/docs/edit/main/README.md">edit docs</a></li>
        <li>Clone link: https://github.com/web-stream/docs.git</li>
    </ul>
</details>

<details>
    <summary>Docs languages</summary>
    <ul>
        <li><a href="">PL</a></li>
        <li><a href="">EN</a></li>
        <li><a href="">DE</a></li>
    </ul>
</details>

## Dokumentacja PL

---
### Czym jest modularyzacja

hipermodularyzacja
modularyzacja

### Wstęp

---
WebStream jest to javascript-owa biblioteka pozwalająca na renderowanie modułów w czasie rzeczywistym bez ich wczesniejszej kompilacji. Biblioteka pozwala developerom na tworzenie aplikacji frontendowych w "natywnych" językach przeglądarkowych (HTML, CSS, JS).

### Historia

---
Aby omówić, możliwości tej biblioteki należy, najpierw zrozumieć istniejące technologie, choć w formie podstawowej.

+ Początkowo ludzie tworzyli wyłącznie statyczne strony internetowe, w których treść była wpisana na stale w kod naszej strony.

+ Kolejnym krokiem rozwoju stron internetowych było umożliwienie renderowania stron internetowych po stronie serwera (generowanie pliku HTML dynamicznie przy pomocy potrzebnych danych)

+ Obecnie tworząc strony internetowe, rozdziela się je na frontend oraz backend (skupimy się na frontend, ponieważ, to jego dotyczy nasza biblioteka). Frontend istniejący obecnie tworzony jest głównie przez JavaScript a właściwie frameworki takie jak vue, react czy angular. Frameworki te pozwalają na tworzenie aplikacji, które po późniejszym kompilowaniu są gotowe do użycia na stronie.

+ Webstream oferuje całkowicie nowe podejście do tworzenia frontendu. Webstream pozwala stworzyć modularną stronę internetowa która, może pobierać moduły, biblioteki, oraz części pomniejszych modułów bądź zaciągać dane z zewnętrznego api, a to wszystko wykonuje się asynchronicznie w czasie rzeczywistym. Dodatkowym atutem Webstream jest to, iż niepotrzebne moduły nie są pobierane. W przeciwieństwie do większych fremeworkow nasza biblioteka nie pobiera od razu całego kodu, a jedynie kod niezbędny pozwala to ograniczyć zużycie ramu przeglądarek użytkowników. Nasze rozwiazanie pozwala na rozbijanie frontendu na pomniejsze serwery, ale także na pomniejsze moduły które w przeciwieństwie do wielu istniejących rozwiązań nie Maszą być postawione na osobnym serwerze a jedynie są dynamicznie pobierane. 


### Zastosowanie

---
Nasza biblioteka sprawdzi się bardzo dobrze podczas prototypownia aplikacji, ale także w aplikacji, która posiada dobrze zbudowany system cashowania. Dzięki wykorzystaniu cashowania oraz naszej biblioteki możemy znacznie przyspieszyć proces działania aplikacji, a także znacznie zmniejszyć wagę aplikacji otrzymywanej przez odbiorcę poprzez załadowanie jedynie niezbędnych elementów strony ktore są w użytku, oraz doładowanie kolejnych modolow, gdy tylko będą potrzebne bez konieczności odsiwrzania strony. 

Dzięki dynamicznemu pobieraniu modułów jesteśmy w stanie doładować do naszej aplikacji moduł po wyrenderowaniu strony, dzięki temu jesteśmy w stanie dynamicznie wczytać reklamy na stronę bądź aplikacje a ponadto przy użyciu paru innych bibliotek jesteśmy w stanie, przechwycić reklamę od reklamodawcy, a następnie wygenerować ja w naszej stronie pod naszą domeną pozwala nam to ominąć wszelkie rozszerzenia blokujące reklamy.

### Instalacja

---

Jak narazie dodanie naszej biblioteki jest mozliwe tylko po zaimportowaniu [kodu do pliku HTML](https://get.jloads.com/jloads.min.js).

Przyklad implementacji:

    <script src="https://get.jloads.com/jloads.min.js"></script>

Alternatywą jest pobranie kodu i zaimportowanie go z naszego dysku:

    <script src="ścierzka_do_pliku"></script>

W przyszlosci dodamy nasza biblioteke na npm.