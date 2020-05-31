## Zawartość dokumentacji
* [Główne informacje](#general)
* [Jak działa?](#how)
* [Dodatkowe funkcje](#function)
* [Zdjęcia](#pictures)
* [Użyte technologie](#tech)
* [Jak uruchomić](#setup)

## Główne informacje
Przedstawiony projekt służy do wyszukiwania zdjęć z bazy danych Pixabay przy użyciu jego API.

	
## Jak działa?
Jego działanie jest bardzo proste. Wpisjąc w wyszukiwarkę angielską frazę np. "Parrot" otrzymamy w domyśle 20 zdjęć psów które zostają zaczerpnięte ze zbioru zdjęć Pixabay. Zdjęcia wyszukiwane są na podstawie tagów.<br/>
Dodatkowo przy każdym zdjęciu wyświetlony jest autor danego zdjęcia, ilość wyświetleń, polubień, komentarzy, a także cały adres URL do strony macierzystej.

## Dodatkowe funkcje
Po wpisaniu frazy spoza bazy danych np. "fffff" program wypisuje brak wyników.
<br/>
Przy słabym łączy podczas ładowanie strony wyświetlana jest informacje o tym, że strona ładuje się.


## Zdjęcia

![Screenshot](Przykład.jpg)

## Użyte technologie

- Tailwind CSS

## Jak uruchomić
Aby uruchomić projekt, należy zainstalować go lokalnie przy użyciu npm:

```
$ npm install

$ npm start
```

