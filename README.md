# Curriculum Vitae &mdash; szablon napisany w HTML i CSS

<p align="center">
  <img height="850" width="600" src="https://raw.githubusercontent.com/WojtekWernicki/contact-form/master/cv.png">
</p>

Prosty szablon CV stworzony z myślą o programistach. Zawiera sekcje o doświadczeniu zawodowym, edukacji, wykonanych projektach z klikalnymi linkami do repozytorium, znanych językach programowania, narzędziach i językach obcych.

## Instrukcja obsługi

0. Zainstaluj Node.js (https://nodejs.org/en/), gulp i gulp-cli: `npm install -g gulp gulp-cli`
1. Sklonuj repozytorium
2. W konsoli przejdź do folderu z szablonem i uruchom instalację pakietów npm: `npm install`
3. Wklej zdjęcie, którego użyjesz w swoim CV, do folderu `src/img`
4. Uruchom gulpa: `gulp`
5. Dokonaj niezbędnych zmian w HTML-u. Jeżeli chcesz zmienić kolor, możesz to zrobić w pliku [style.scss](src/scss/style.scss)
6. Używając Google Chrome, otwórz CV i wydrukuj je do PDF-a
7. Gratulacje, masz swoje CV!

## Inne

W stopce umieszczona jest już prawna formułka, dzięki której pracodawca może przetwarzać Twoje dane osobowe umieszczone w CV.

Do wykonania tego szablonu użyłem stworzonego przez siebie **startera [gulp-starter](https://github.com/WojtekWernicki/gulp-starter)**. Za pomysł dziękuję Andrzejowi Prusinowskiemu ([avris.it](https://avris.it)).