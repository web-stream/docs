![logo webstream](https://logo.webstream.dev/3/cover.png)

<img alt="open collective badge" src="https://opencollective.com/webstream/tiers/backer/badge.svg?label=backer&color=brightgreen" />
<img alt="open collective badge" src="https://opencollective.com/webstream/tiers/sponsor/badge.svg?label=sponsor&color=brightgreen" />
<object type="image/svg+xml" data="https://opencollective.com/webstream/tiers/backer.svg?avatarHeight=36&width=600"></object>

---

# [docs.webstream.dev](https://docs.webstream.dev/#/)

+ [www.webstream.dev](https://www.webstream.dev/#/)
+ [roadmap.webstream.dev](https://roadmap.webstream.dev/#/)
+ [other.webstream.dev](https://other.webstream.dev/#/)
+ [other.webstream.dev](https://other.webstream.dev/#/)
+ [modules.webstream.dev](https://modules.webstream.dev/#/)

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
WebStream jest to javascript-owa biblioteka pozwalająca na renderowanie modułów w czasie rzeczywistym bez ich wczesniejszej kompilacji. Biblioteka pozwala developerom na tworzenie aplikacji frontendowych w "natywnych" językach przeglądarkowych (HTML, CSS, JS). Nasza biblioteka oferuje calkiem nowe podejscie do mikrofrontendu!

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

Alternatywą jest [pobranie kodu](https://get.jloads.com/jloads.min.js) i zaimportowanie go z naszego dysku:

    <script src="ścieżka_do_pliku"></script>

W przyszlosci dodamy nasza biblioteke na npm.



## How WebStream work's?

Load any media on website without reload page, now stream each website without reload.
Over modularity each website can talk to another without barrier...
Web Stream a continuous improving by a flowing stream.

Kod źródłowy

+ [src.webstream.dev](https://src.webstream.dev/#/)
+ [demo.webstream.dev](https://demo.webstream.dev)


## [Web Stream](https://www.webstream.dev/)

Streaming application/interface directly on frontend, without building backend side is part of [wapka ecosystem](https://docs.wapka.pl/) to build Application
based on PaaS infrastructure as Aplication Platform as a Service or (APaaS) Function as a Service (FaaS)

WebStream is a rapid prototyping, playing and learning environment for web development.
Extends the JavaScripts language with Stream Thinking and libraries for building asyncron, decentralized, modular applications.
Web Stream a continuous improving by a flowing stream;

Czym jest Webstream?

Web Stream Dev jest modularnym standardem ładowania mediów, umożliwiającym implementację streamowania poprzez protokół HTTP dla aplikacji oraz stron internetowych w przeglądarce oraz dedykowanych platformach.

+ [About Webstream Modules ...](https://modules.webstream.dev)
+ [What is Hyper Modularity ?](https://www.hypermodularity.com/)


Supported media

Ładowanie mediów tekstowych, kodu aplikacji, filmów, głosu, itp.

+ html
+ js
+ json
+ css

```js
var mime = {
	'html': 'text/html',
	'json': 'application/json',
	'js': 'application/javascript',
	'css': 'text/css'
};
```

and others:
+ txt
+ markdown
+ mp3
+ wav
+ php
+ python

Learn More About Web Stream Dev

+ [about.webstream.dev](https://about.webstream.dev/)




## Why WebStream?

A Modular architecture can bring all sorts of benefits to the sites and to project workflows.
Some of the key benefits are:

### Security

The WebStream provide tested reusable parts and systems from the hosting infrastructure resulting in fewer servers and systems to harden against attack.

Serving pages and assets as pre-generated files allows read-only hosting reducing attack vectors even further.
Meanwhile dynamic tools and services can be provided by vendors with teams dedicated to securing their specific systems and providing high levels of service.

### Scale

Popular architectures deal with heavy traffic loads by adding logic to cache popular views and resources.
The WebStream provides this by default.
When sites can be served entirely from a CDN there is no complex logic or workflow to determine what assets can be cached and when.

With WebStream sites everything can be cached in a content delivery network. With simpler deployments, built-in redundancy and incredible load capacity.

### Performance

Page loading speeds have an impact on user experience and conversion. WebStream sites remove the need to generate page views on a server at request time by instead generating pages ahead of time during a build.

With all the pages are already available on a CDN close to the user and ready to serve, very high performance is possible without introducing expensive or complex infrastructure.

### Maintainability

When hosting complexity is reduced, so are maintenance tasks. A pre-generated site, being served directly from a simple host or directly from a CDN does not need a team of experts to "keep the lights on".

The work was done during the build, so now the generated site is stable and can be hosted without servers which might require patching, updating and maintain.


### Portability

WebStream sites are pre-generated. That means that you can host them from a wide variety of hosting services and have greater ability to move them to your preferred host. Any simple static hosting solution should be able to serve a WebStream site.

no more locked infrastructure and code.


### Developer Experience

WebStream sites can be built with a wide variety of tools.
They do not depend on the proprietary technologies or exotic and little known frameworks.
Instead, they build on widely available tools and conventions.
As a result, it's not hard to find enthusiastic and talented developers who have the right skills to build with the WebStream.






# [FAQ.webstream.dev](https://faq.webstream.dev/)

# history
Powstanie

pierwsze kroki:

+ [jLoads](https://www.jloads.com/)
+ [Web Stream Dev](https://www.webstream.dev/)


Projekt obecnie nazywa się WebStream, jest zbiorem kilku modularnych funkcji, pozwalających na wykorzystanie potencjału jaki leży w protokole http
i naturalnej predyspozycji jezyka JavaScript do prototypowania.


## jLoads

Biblioteka jLoads była jednym z pierwszym implementacji podejścia modułowego w sofwtare developmencie, miała za zadanie załadowanie wszystkich potrzebnych mediów na stronę www.


w związku z rozwojem bilbioteki i modularyzacją samej biblioteki potrzebny był wspólny mianownik do połączenia narzędzi tworzących ekosystem do streamowania interface-ów aplikacji webowej.


Po wykonaniu prototypu jLoads udało się określić strukturę biblioteki w kontekście użycia, czyli zmodularyzować.

Wydzieliłem nawet biblioteki do ładowania, definicji JSON oraz do Ładowania i routowania mediów

+ [About our modules](https://modules.webstream.dev)
+ [microfrontend.org](https://microfrontend/org)



## Alternatywne rozwiązania

+ [other.webstream.dev](https://other.webstream.dev/#/)





## Background

We live in a multi-device, multi-channel world.

The rapid adoption of microservices architectures is extending and replacing the large monolithic applications.

Interface for application streaming for deep [AI personalisation](https://www.aipersonalisation.com/#/).
Now you can provide any applications with different versions that you might want to run in user space.
This greatly simplified the layout of the content available in WebStream and offered the flexibility to adopt polyglot persistence.



The following solutions are game changers:

### jbodys - content preapration
Jbodys help to build, deploy digital content faster with better user experiences and more options for advertisement than we know today.
jBodys help to build, deploy digital content faster with better user experiences and more options for advertisement than we know today.


### jloads - JS loader
load any media on frontend side
load asynch assets on webpage with dependencies

### jruns - JS runnner
load any media on backend side and handle any requests from jloads



## SaaS solutions

content orchestration for content management and delivery


### apiContext.com

It's an acces gateway to your private cloud/marketplace of apps, UI, content:
+ context marketplace

Content management API, to create and manage your content
backend side to provide the content on your website



### Contextool.com

Staging publications and to manage existing modules, preview, creating draft and publish
Works with public and private marketplaces

use existing infrastructure to create project with SDK, JS libraries
+ jLoads.com
+ jbodys.com

delivering applications, interfaces, content directly on your frontend side
+ publish/deliver content to your webside.
+ synced over http streaming data.




### Contextrack.com

analytics for published content over Contentool.com
+ [Matomo Analytics - The Google Analytics alternative that protects your data](https://matomo.org/)


### ContextAct.com

create rules to load your media with jRoutes.com


### UserContext.com

AI personalisation fcontextock.or generatiing content with advertisement, acces over APIcontext.com
+ [The Measure of Moments: Receptivity - CONTXTFUL](https://www.contxtful.com/en)



### ContextStyle.com

any media are dynamiclly converted, resized, cropped, compressed.
Works for images, markdown files, movies, audiofiles, ...


### contextSpot.com

Marketplace for
+ blog owners, influencers can sale place for advertisement


### contextStock.com

+ buy assets and use on own projects
+ buy advertismeent spot, decentralised stock, estimation of adv





---

# (Web) Stream of Solutions


why should we use webstream?

Because we can improve our stack to manage them locally without complicated not local controlled environment


## Browser and multi framework limitations

Gdy korzystamy z własnej implementacji frontend <-> mikroserwisy możemy napotkać niektóre z tych problemów:

+ wiele wersji tej samej biblioteki ładujących się z losową kolejnością i nadpisujących się,
+ style z jednej aplikacji nadpisywały drugą,
+ brak prostego sposobu na dodanie kolejnej aplikacji utworzonej w innym frameworku,
+ problemy z routingiem,
+ brak lazy loading.


## Cloud Stack Problem

I warned people many years ago to not base their entire stack on a single cloud provider.
They didn't listen, made fun of me, and I actually nodded for some time - it's more efficient, right?

What could go wrong.


Because it's limiting.

You base your entire system around proprietary software/services, and then you're stuck - you can't migrate anywhere else,
without re-writing huge chunks of your code.

The code that happened to be yours, is still dependent on cloud solutions, so it goes to waste as well - you end up doubling hours spent on achieving the same outcome, if you decide it's time to move.

And that's the best case scenario, if you're unlucky, you're getting kicked out like @Parler was with 72hr notice.
That's the rational explanation. I also don't trust Amazon, Google or Microsoft. tldr; out of principles.

---


## Solutions

Streaming media

+ Use a declarative model to render HTML on the server over WebSockets with optional LongPolling fallback
+ Smart templating and change tracking - after connected, LiveView sends only what changed to the client, skipping the template markup and reducing the payload

Stay Live

+ Live form validation with file upload support
+ Live navigation to enrich links and redirects to only load the minimum amount of content as users navigate between pages

Testing solutions

+ A latency simulator so you can emulate how slow clients will interact with your application
+ Testing tools that allow you to write a confident test suite without the complexity of running a whole browser alongside your tests

Events

+ A rich integration API with the client with `web-click`, `web-focus`, `web-blur`, `web-submit`, etc. `web-hook` is included for the cases where you have to write JavaScript

Web Components
+ Code reuse via components, which break templates, state, and event handling into reusable bits, which is essential in large applications



Dokumentacja

+ [docs.webstream.dev](https://docs.webstream.dev)
+ [tutorial.webstream.dev](https://tutorial.webstream.dev)





## A WebStream API

+ [API Platform: Getting Started With API Platform: Create Your API and Your WebStream Site](https://api-platform.com/docs/distribution/)

+ a [Helm](https://helm.sh/) chart to deploy the API in any [Kubernetes](https://api-platform.com/docs/deployment/kubernetes/) cluster


To create a fully featured API, an admin interface and a Progressive Web App using WebStream all you need is to design **the stream data model of our application**

API Platform uses these model classes to expose and document a web API having a bunch of built-in features:

+ creating, retrieving, updating and deleting (CRUD) resources
+ data validation
+ pagination
+ filtering
+ sorting
+ hypermedia/[HATEOAS](https://en.wikipedia.org/wiki/HATEOAS) and content negotiation support ([JSON-LD](https://json-ld.org) and [Hydra](https://www.hydra-cg.com/), [JSON:API](https://jsonapi.org/), [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-08)
+ [GraphQL support](https://api-platform.com/docs/core/graphql/)
+ Nice UI and machine-readable documentations ([Swagger UI/OpenAPI](https://swagger.io), [GraphiQL](https://github.com/graphql/graphiql)...)
+ authentication ([Basic HTTP](https://en.wikipedia.org/wiki/Basic_access_authentication), cookies as well as [JWT](https://jwt.io/) and [OAuth](https://oauth.net/) through extensions)
+ [CORS headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
+ security checks and headers (tested against [OWASP recommendations](https://www.owasp.org/index.php/REST_Security_Cheat_Sheet))
+ [invalidation-based HTTP caching](https://api-platform.com/docs/core/performance/)
+ and basically everything needed to build modern APIs.

One more thing, before we start: as the API Platform distribution includes [the Symfony framework](https://symfony.com), it is compatible with most [Symfony bundles](https://flex.symfony.com) (plugins) and benefits from [the numerous extensions points](https://api-platform.com/docs/core/extending/) provided by this rock-solid foundation (events, Dependency Injection Container...). Adding features like custom or service-oriented API endpoints, JWT or OAuth authentication, HTTP caching, mail sending or asynchronous jobs to your APIs is straightforward.



## For contributors

+ [start.webstream.dev](https://start.webstream.dev/#/)
+ [tools.webstream.dev](https://tools.webstream.dev/#/)
+ [task.webstream.dev](https://task.webstream.dev)
+ [stack.webstream.dev](https://stack.webstream.dev/#/)





## Project Status

⚠️ WebStream is still an early beta, missing features and bugs are to be expected! If you can stomach it,
then WebStream-built sites are production ready and several production websites built with WebStream already exist in the wild.
We will update this note once we get closer to a stable, v1.0 release.


Check status:
+ [roadmap.webstream.dev](https://roadmap.webstream.dev)




---

## About Tom Sapletta

+ [Contact on linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Tom Sapletta Blog - Embedded System Software & Hardware Developer](https://tom.sapletta.com/)
+ [Softreck Company - Leadership Through Software Development](https://softreck.com/)


## Substantively supported by:

+ [SaaS is King .com](https://www.saasisking.com/)
+ [hyper Modularity .com](https://www.hypermodularity.com/)


## Sponsored by:

+ [Softreck - Leadership Through Software Development](https://softreck.com/), Leadership through software development


---
+ [edit](https://github.com/web-stream/docs/edit/main/README.md)
+ [web-stream/docs: Documentation on github](https://github.com/web-stream/docs)
```
https://github.com/web-stream/docs.git
```

