# docs.webstream.dev

[docs.webstream.dev](https://docs.webstream.dev/#/)

+ PL
+ EN
+ DE


## Dokumentacja PL

### Czym jest modularyzacja

hipermodularyzacja
modularyzacja


### Jak jest zaimplementowana w WebStream


---
+ [edit](https://github.com/web-stream/docs/edit/main/README.md)

```
https://github.com/web-stream/docs.git
```

Biblioteka web stream jest biblioteka służąca do tworzenia aplikacji głównie prototypowych. Biblioteka ta oferuje możliwość tworzenia frontendowych aplikacji przy pomocy modułów, które w przeciwieństwie do aplikacji pisanych w bibliotekach takich jak vue, react czy angular nie są kompilowane.
Co to oznacza ?
Oznacza to, że, nasza aplikacja korzysta w pełni z najbardziej podstawowych technologii przeglądarek, co pozwala na tworzenie wydajnych aplikacji.
Jak to działa na przykładzie vue:
Tworząc, jakakolwiek aplikacje w vue, musimy stworzyc aplikacje do ktorej, bedziemy dolaczac nasze modoly z rozszerzeniem vue. Aby uruchomić gotowy projekt, napisany w vue musi on zostać "zbudowany" (skompilowany) na języki natywne (najbardziej podstawowe) takie jak js, css, html. Takie budowanie projektu zajmuje dana ilość czasu w zależności od wielkości projektu. Ponadto podczas fazy developowania przy każdorazowym uruchomianiu aplikacji aplikacja jest budowana od zera.
Biblioteka web stream wprowadza świeże spojrzenie na proces tworzenia takich aplikacji. i pozwala na developowanie aplikacji przy pomocy html -a, css oraz javascript dodatkowo zachowywać modułowość. Podstawo, do strony korzystające z web stream zaciągane sa jedynie zdeklarowane przez użytkownika moduły jednak gdy wykonywana jest akcja która, ma za zadanie "odsłonić" inny istniejący już moduł powoduje ona pobranie tego danego modułu z serwera.
Jak to przekłada się na wydajność?
Żyjemy w świecie gdzie, dostęp do szybkiego internetu jest znacznie bardziej powszechny niz, dostęp do zaawansowanych urządzeń elektronicznych. Webstream pozwala na ograniczenie zużycia mocy za równo przeglądarki, jak i urządzenia na którym, uruchamiamy naszą stronę poprzez nie pobieranie zbędnych modułów na stronę a jedynie "zaciąganie" ich z serwera w momencie, kiedy tylko będą nam potrzebne.