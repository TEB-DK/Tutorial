
<h1 align="center">:cat: GitHub wprowadzenie :octopus:</h1>
Poradnik przedstawia krok po kroku podstawowe użytkowanie serwisu GitHub. Dzięki któremu społeczeństwo programistyczne ma miejsce do komunikacji między sobą, a także przechowywania projektów czy dokumentacji. My będziemy korzystać z wylistowanych tematów do zajęć, więc podstawowa umiejętność obsługi tego serwisu jest _obowiązkowa_.
<div style="background-color:#5522d6; border-radius: 5px; height: 2px;">
⠀
</div>


## :pencil: Rejestracja

- Po przejściu na stronę [GitHub](https://github.com/)

- Należy kliknąć ``Sign up``
- W polu ``Enter your email`` wprowadzamy swój adres email i klikamy ``Continue``.

  ![Enter your email](https://user-images.githubusercontent.com/33155636/218325075-301a43c1-f310-4fc0-a45e-4ee2ad8c21fe.png)

-  Po wprowadzeniu emaila, który nie jest już w użytku wprowadzamy hasło i klikamy ``Continue``.

    - Pamiętajcie aby hasło zawierało standardy bezpiecznego hasła (duże i małe litery, znaki specjalne, cyfry oraz aby długość hasła przekraczała 8 znaków)

    ![Create a password](https://user-images.githubusercontent.com/33155636/218329500-423c7ddf-d1f7-4fcf-a819-7020970ba7aa.png)

- Kolejnym polem jest wybór swojej nazwy użytkownika.

    ![Enter a nickname](https://user-images.githubusercontent.com/33155636/218329780-03bfe832-ab9c-4867-ab87-f2b5d5a9c2a9.png)

- Na sam koniec dostaniemy pytanie odnośnie dokonywanych zmian czy ogłoszeń, które mają być wysyłane na nasz email.
    - Wprowadzamy ``y`` jeśli się zgadzamy lub ``n`` jeśli nie. Jest to często stosowany format wyboru w aplikacjach konsolowych (taki mały detal).

    ![Would you](https://user-images.githubusercontent.com/33155636/218329924-49c51ccb-26de-4002-807e-7011eb417852.png)

- Po pomyślnej weryfikacji, że nie jesteśmy robotem należy kliknąć ``Create account`` i zweryfikować swoje konto za pomocą kodu wysłanego na email.

    ![Verification](https://user-images.githubusercontent.com/33155636/218330200-1a6d10eb-b19b-4f49-bfb2-cf652abc5284.png)

## :book: Repozytorium

 ### :new: Tworzenie repozytorium

-  Rozwijamy liste nawigacyjną klikając w ikonke swojego avatara i wybieramy ``Your repositories``.

    ![Nav list](https://user-images.githubusercontent.com/33155636/218331266-e9d7d38c-45f7-4779-bebc-698fe1c405db.png)

- Klikamy zielony przycisk ``New``

    ![Your repositories](https://user-images.githubusercontent.com/33155636/218331258-060ddd9f-1e4f-4fa2-a734-3920b257506a.png)

- Wprowadzamy nazwę repozytorium i wybieramy zakres widoczności (publiczny lub prywatny)
    - Repozytorium to miejsce przeznaczone dla konkretnego projektu, można je sobie przyrównać do folderu na pulpicie w którym jest zapisany konkretny projekt.
    - Prywatne repozytorium będzie widoczne tylko dla nas i dla osób którym udostępnimy dostęp, natomiast publiczne będzie widniało na naszym profilu i każdy będzie mógł przejrzeć pliki projektu.

    ![Repository name and visibilty](https://user-images.githubusercontent.com/33155636/218331621-14e8891f-c57c-4467-a190-bbf02c42aee9.png)

- Następnie możemy wybrać szczegóły odnośnie repozytorium. Zdecydować czy ma posiadać domyślny plik README, dodać plik .gitignore, który ignoruje pewne foldery zbędne przy przesyłaniu projektu (np. node_modules), a także wybrać licencje na jakiej tworzymy dany projekt. Po wybraniu tych opcji klikamy ``Create repository``.

    ![Repository details](https://user-images.githubusercontent.com/33155636/218331748-e9d5168b-fbc3-4732-ba47-8d28baa8c417.png)

- Gdy wszystko już wyklikamy to powinno nas przenieść na stronę repozytorium. Wszystkie repozytoria będą widoczne w ``Your repositories`` w menu rozwijanym w prawym górnym rogu.

    ![Repository look](https://user-images.githubusercontent.com/33155636/218332031-9af30155-05c6-4dd5-b142-de38c6f7341f.png)


 ### :olive: Rozgałęzienia
 > Rozgałęzienia (branche) są wykorzystywane do podzielenia go na konkretne funkcjonalności wykonywane modułowo przez różnych programistów działających na jednym branchu. Możemy traktować rozgałęzienia niczym "pod repozytoria", które mogą ale nie muszą być zależne od siebie.

 - Na stronie repozytorium wybieramy menu rozwijane w sekcji ``Code`` na którym aktualnie jesteśmy rozgałęzieniu (w tym przypadku to ``main``).

    ![Branch](https://user-images.githubusercontent.com/33155636/218333921-c50fb10e-e43e-4715-a591-90373dc22235.png)

 - Po klikneciu na to menu możemy wyszukać rozgałęzienie lub je utworzyć, a także jeśli już istnieje kliknąć w nazwę tego rozgałęzienia i przełączyć się na nie.
 
    ![Branch menu](https://user-images.githubusercontent.com/33155636/218334232-fc81712b-9f1b-4894-9d61-d76f44fb52ac.png)

 - Po wpisaniu nazwy rozgałęzienia powinno zostać wyszukane w repozytorium, jeśli nie istnieje to możemy za pomocą kliknięcia na ``Create branch: [nazwa_rozgałęzienia] from '[nazwa_rozgałęzienia_aktualnego]'``

    ![Create or find branch](https://user-images.githubusercontent.com/33155636/218334303-5daec4e1-1c2d-4998-a271-183c7dd18eed.png)

 - Następnie zostanie ono utworzone, oraz zostaniemy przełączeni domyślnie na nie.

    - W tym momencie projekt jest rozgałęziony pomiędzy dwoma niezależnymi branchami ``main`` (główny) oraz ``new`` (utworzony z głównego). Mogą funkcjonować oddzielnie, jednak idea ich istnienia opiera o finalnym złączeniu ponownie w branchu ``main``.

    ![New branch](https://user-images.githubusercontent.com/33155636/218334462-c1261c55-f74d-4933-b0d5-15d0b6cfd467.png)



 ### :rocket: Publikowanie projektu
 > Prosze się upewnić, że wszelkie potrzebne pliki do utworzenia strony są zawarte w repozytorium.

 - W nawigacji repozytorium projektu wybieramy ``Settings``.

    ![Settings](https://user-images.githubusercontent.com/33155636/218333018-46bd7c97-32da-4435-84cd-7dbcc6c2a6c3.png)
 - Z menu bocznego wybieramy ``Pages`` w sekcji ``Code and automation``.

    ![Pages](https://user-images.githubusercontent.com/33155636/218332786-0640d377-f35d-44cd-b6fa-15be9a5c6220.png)

 - Pod ``Build and deployment`` wybieramy ``Deploy from a branch``, a następnie pod ``Branch`` wybieramy z której gałęzi i folderu chcemy utworzyć naszą stronę i klikamy ``Save``.

    ![obraz](https://user-images.githubusercontent.com/33155636/218333128-de5dc11a-d0cd-429b-bd73-d0a8a09abaab.png)

 - Po tym kroku strona zostanie odświeżona i nasz projekt zacznie być budowany, po chwili możemy odświeżyć stronę ponownie i zobaczyć projekt który pojawił się.

    - Adres strony będzie domyślnie w formacie ``https://[nazwa_użytkownika].github.io/[nazwa_repozytorium]/``

    ![Deployed page](https://user-images.githubusercontent.com/33155636/218333420-d3e1f3ce-9437-4cb1-bb90-574301205483.png)

## :hash: Markdown
> Markdown jest to rozszerzenie polegające na HTML'u, jednak bardzo uproszczone na potrzeby tworzenia prostych plików dokumentacji/opisów. Rozszerzenie które obsługuje syntaktykę markdown to ``.md``.

> Więc tak, jeśli ktoś chce może napisać kod ``html`` w pliku ``.md`` i również zadziała.

> Zalecane jest zainstalowanie rozszerzenia obsługującego Markdown dla ``VSC`` w celu wygodnej pracy na projekcie [``Markdown All in One``](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one).
 
 ### :writing_hand: Podstawowa syntaktyka

 #### Nagłówki
  ```markdown
    # to to samo co <h1></h1>
    ## to to samo co <h2></h2>
    ### to to samo co <h3></h3>
    #### to to samo co <h4></h4>
    ...itd.
  ```
  # to to samo co ``<h1></h1>``
  ## to to samo co ``<h2></h2>``
  ### to to samo co ``<h3></h3>``
  #### to to samo co ``<h4></h4>``

  #### Akcent
  ```markdown
    *tekst* oznacza podkreślenie
    **tekst** oznacza pogrubienie
    **_tekst_** oznacza pogrubienie i podkreślenie
  ```
  *tekst* oznacza podkreślenie

  **tekst** oznacza pogrubienie

  **_tekst_** oznacza pogrubienie i podkreślenie

  #### Listowanie
  ```markdown
    1. Uporządkowana pozycja pierwsza
    2. Uporządkowana pozycja druga
      * Nieuporządkowana pozycja 
    4. Uporządkowana pozycja trzecia zapisana jako "4."

    - [ ] Pole zaznaczenia jako pozycja (puste).
    - [x] Pole zaznaczenia jako pozycja (zaznaczone).
  ```
  1. Uporządkowana pozycja pierwsza
  2. Uporządkowana pozycja druga
     * Nieuporządkowana pozycja
  4. Uporządkowana pozycja trzecia zapisana jako "4."

  - [ ] Pole zaznaczenia jako pozycja
  - [x] Pole zaznaczenia jako pozycja (zaznaczone).

  #### Linki
  ```markdown
    [Przykładowy tekst linku](https://google.com/)
    [Przykładowy tekst linku z opisem](https://google.com/ "Przykładowy tytuł")

  ```
  [Przykładowy tekst linku](https://google.com/)<br>
  [Przykładowy tekst linku z opisem](https://google.com/ "Link do google :-)")

  #### Obrazki
  ```markdown
    
    ![Przykładowy obrazek](https://user-images.githubusercontent.com/33155636/218336855-f5e1ece3-fe13-4cf0-933e-75f1e24de619.png)

    ![Przykładowy obrazek z tytułem](https://user-images.githubusercontent.com/33155636/218336855-f5e1ece3-fe13-4cf0-933e-75f1e24de619.png "Kremówka")
  ```
  ![Przykładowy obrazek](https://user-images.githubusercontent.com/33155636/218336855-f5e1ece3-fe13-4cf0-933e-75f1e24de619.png)
  ![Przykładowy obrazek z tytułem](https://user-images.githubusercontent.com/33155636/218336855-f5e1ece3-fe13-4cf0-933e-75f1e24de619.png "Kremówka")

  ##### Hosting obrazków
  > Aby sprawnie wstawiać obrazki na za pomocą zawsze dostępnego hostingu możemy wykorzystać sposób z zakładą ``issue`` w repozytorium.
  > ![obraz](https://user-images.githubusercontent.com/33155636/218337321-e8736eff-0e4f-4dee-bd44-dec0372a48b2.png)
  > Klikamy ``New issue``
  > ![obraz](https://user-images.githubusercontent.com/33155636/218337368-58c74830-4e53-4441-99ef-131d79647b0d.png)
  > W polu tekstowym z placeholderem ``Leave a comment`` wklejamy (``CTRL + V``) lub przenosimy z pulpitu obrazek i czekamy aż GitHub wygeneruje link hostowany na ich serwisie.
  ![obraz](https://user-images.githubusercontent.com/33155636/218337456-7fc1859e-fba6-43fd-866a-d91432835b58.png)

  > Pozostaje skopiować wygenerowany link i wkleić w plik ``.md``. Po ukończeniu tworzenia dokumentacji / opisu możemy zamknąć zakładkę ``issue``, a nasze obrazki będą wciąż dostępne.

  #### Wstawianie kodu
  ```markdown
    ```python
        def funkcja(a,b):
            return a*b
    ```
    lub
    ```
        jakiś tekst bez kolorowania kodu
    ```
  ```
  ```python
    def funkcja(a,b):
        return a*b
  ```
  lub
  ```
    jakiś tekst bez kolorowania kodu
  ```

 #### Odnośniki do materiałów ze szczegółami

 [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables)

 [GitHub documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

<div style="background-color:#5522d6; border-radius: 5px; height: 2px;"></div>

## :gear: Zadania do wykonania
  ### :star: Zadanie 1
  - [ ] Wykonaj prostą stronę zawierającą podstawowe informacje o sobie, wraz z przykładowym obrazkiem oraz arkuszem stylów do każdego z elementów strony.
  - [ ] Utwórz dokumentację o swojej stronie używając pliku ``README.md``, w którym uwzględnisz takie znaczniki jak:
    
    - nagłówek,
    - link,
    - obrazek (np. kodu html w VSC),
    - znacznik kodu (```) wraz z odpowiednim kolorowaniem syntaktyki,
    - [emoji](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

  ### :star: Zadanie 2
  - [ ] Stwórz repozytorium dla swojego projektu według schematu nazwy: ``[Imie i nazwisko]_[Klasa]_WiAI``.
  - [ ] Dołącz pliki z lokalnego folderu projektu swojego komputera do utworzonego repozytorium.
  - [ ] Opublikuj swój projekt za pomocą GitHuba.


