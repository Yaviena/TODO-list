# TODO-list

### Table of Contents
[O aplikacji TODO list](#intro)</br>
[Dostępne funkcjonalności](#funkcjonalnosci)</br>
[Przykłady użycia](#przyklady)</br>
[Podsumowanie](#podsumowanie)</br>

### O aplikacji TODO list <a name="intro"></a>
TODO list to program, który pozwala tworzyć tzw. listy TODO, czyli tworzy i zarządza listą rzeczy do zrobienia. Możliwości aplikacji:
- możliwość przechowywania danych w pliku,
- dane dostępne są również po zamknięciu aplikacji,
- zapisywanie danych w sposób dynamiczny, bez ingerencji użytkownika,
- po ponownym uruchomieniu aplikacji dane są dopisywane do istniejącego pliku - o ile takowy już się znajduje,
- po wykonaniu przez program pojedynczej akcji nie następuje jego zamknięcie,
- stale, na każdym etapie jest dostęp do wszystkich funkcji programu bez konieczności ponownego uruchomienia aplikacji.

### Dostępne funkcjonalności <a name="funkcjonalnosci"></a>
Aplikacja TODO zawiera następujące funkcje:
1. [Dodanie nowego zadania](#funkcjonalnosc1)
2. [Wyświetlanie wszystkich zadań w porządku od najstarszych](#funkcjonalnosc2)
3. [Wyświetlanie wszystkich zadań w porządku od ostatnio dodanych](#funkcjonalnosc3)
4. [Usunięcie jednego wybranego zadania](#funkcjonalnosc4)
5. [Usunięcie wszystkich zadań z listy](#funkcjonalnosc5)
6. [Zakończenie działania programu](#funkcjonalnosc6)
7. [Obsługa niewłaściwego wprowadzania znaków](#funkcjonalnosc7)

Wszystkie założenia zawarłam w menu, które ukazuje się na początku po uruchomieniu programu.</br>
Poniżej screen zaraz po uruchomieniu pliku wykonywalnego.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167600796-e6f49d47-0f78-4128-97ff-4dd0c077bba4.png" width="65%" />

### Funkcjonalność na przykładach <a name="przyklady"></a>
1. #### Dodanie nowego zadania <a name="funkcjonalnosc1"></a>
Do zaprezentowania funkcjonalności dodałam 6 zadań wybierając z menu opcję numer 3.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167602012-9aae1f36-301c-43b6-93a7-a5a83002b16a.png" width="65%" /></br></br>
W folderze z plikiem wykonywalnym zostaje automatycznie utworzony plik tekstowy.
Jeśli takowy już istnieje (z poprzedniego uruchomienia programu), dane zostają dopisywane.</br>
Poniżej zrzut z utworzonym plikiem.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167602048-2141b137-a1ca-485e-b8bf-4114b0d40080.png" width="65%" /></br></br>
Dodatkowo plik tekstowy z zapisanymi świeżo dodanymi zadaniami.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167602465-824ae2bd-5c12-4b4c-8c3f-3f9726f29e2a.png" width="65%" />

2. #### Wyświetlanie wszystkich zadań (od najstarszych) <a name="funkcjonalnosc2"></a>
Sortowanie dodanych zadań według kolejności od najstarszych do ostatnio dodanych.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167606324-ceb896ed-88b0-45f6-9118-babc1cc9ee31.png" width="65%" />

3. #### Wyświetlanie wszystkich zadań (od ostatnio dodanych) <a name="funkcjonalnosc3"></a>
Sortowanie dodanych zadań według kolejności od ostatnio dodanych do najstarszych.
Na poniższym zrzucie ekranu widać dodatkowo różnicę pomiędzy tym sortowaniem oraz poprzednim (od najstarszych).</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167606527-9b1a0895-5fa3-479f-88ab-ffa2bc930cd2.png" width="65%" />

4. #### Usunięcie jednego wybranego zadania <a name="funkcjonalnosc4"></a>
Korzystając z opcji numer 4 w menu, widzę wszystkie obecne zadania.
Program pyta, które z nich chcę usunąć. Usuwam zadanie o numerze 3.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167606949-e4143500-4cba-4712-9c5c-98af8241f5fc.png" width="65%" /></br></br>
Po tej operacji wyświetlam wszystkie taski aby sprawdzić, czy wskazane zadanie zostało usunięte.
Faktycznie, wybrane zadanie (o numerze 3) zostało usunięte z listy.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167607182-892d1f7b-0cdd-42ff-b7da-35037492a38e.png" width="65%" />

5. #### Usunięcie wszystkich zadań z listy <a name="funkcjonalnosc5"></a>
Opcja numer 5 w menu usuwa wszystkie utworzone i zapisywane na bieżąco do pliku zadania.
Widzimy również stosowny komunikat o tym, że lista z zadaniami jest pusta.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167607578-5bb4113c-6080-41ca-90ec-efda926a4c18.png" width="65%" /></br></br>
Operacja ta spowodowała także oczekiwaną zmianę w pliku tekstowym, mianowicie usunięcie z niego wszystkich zadań.
Sam plik pozostaje w folderze więc przy ponownych operacjach na liście nie będzie na nowo tworzony a jedynie dopisywane będą do niego kolejne zadania.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167607617-8897fafe-19a2-4542-abbf-73d8fed34552.png" width="65%" />

6. #### Zakończenie działania programu <a name="funkcjonalnosc6"></a>
Wybranie numeru 6 z menu powoduje wyświetlenie w konsoli komunikatu i wyjście z programu.
Zamknięcie okna konsoli wymaga naciśnięcie dowolnego klawisza.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167607810-e9655aa6-2da3-4344-9f24-238a984433f3.png" width="65%" />

7. #### Obsługa niewłaściwego wprowadzania znaków <a name="funkcjonalnosc7"></a>
Program jest odporny na wprowadzenie innych niż oczekiwane znaków z klawiatury.
Dowolna kombinacja powoduje wyświetlenie stosownego komunikatu i daje możliwość ponownego wprowadzenia znaku.</br></br>
<img src="https://user-images.githubusercontent.com/73761391/167607994-492b1d6e-6093-4d5d-99d7-f9f212bd8351.png" width="65%" />

### Podsumowanie <a name="podsumowanie"></a>
Zastosowanie programowania obiektowego w projekcie udowodniło niesamowitą łatwość w potencjalnej dalszej rozbudowie.
Wykorzystanie jego założeń bardzo ułatwi mi dalszą rozbudowę projektu o nowe funkcjonalności, jeśli zajdzie taka potrzeba w przyszłości.
Podział na klasy idealnie odwzorowuje opisywaną we wstępie przydatność - szczególnie w pracy zespołowej, kiedy członkowie zespołu mogą pracować równocześnie,
niezależnie od siebie.
