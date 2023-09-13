**Zadanie egzaminacyjne**\
Wykonaj aplikację internetową fabryki cukierków. Wykorzystaj do tego
celu edytor zaznaczający składnię oraz program do obróbki grafiki
rastrowej i/lub wektorowej.

Aby wykonać zadanie, zaloguj się na konto **Egzamin** bez hasła. Na
pulpicie znajdziesz archiwum ZIP o nazwie *materialy3.zip* zabezpieczone
hasłem: **Wyp@kujMni3**\
Archiwum należy rozpakować.

Na pulpicie konta **Egzamin** utwórz folder. Jako nazwy folderu użyj
swojego numeru PESEL. Rozpakowane pliki umieść w tym folderze. Wyniki
swojej pracy zapisz w tym folderze.

**Grafika**\
Zdjęcie *cukierki1.jpg* należy zapisać w odcieniach szarości.

Logotyp należy przygotować przy pomocy programu do obróbki grafiki
rastrowej i/lub wektorowej, na podstawie zdjęcia *cukierki2.png*:

> −zdjęcie *cukierki2.png* powinno być tak skadrowane, aby był widoczny
> jedynie czerwony żelek −nad żelkiem powinien znaleźć się napis o
> treści „Cukierki"

−cechy tekstu: tekst powinien być opisany na okręgu zgodnie z obrazem 1,
czcionka Georgia lub Times New Roman, pogrubiona, wypełnienie koloru
fioletowe\
−cechy obrazu: tło przezroczyste, wysokość dokładnie 170 px\
−obraz zapisany jako *logotyp* w formacie umożliwiającym zapis
przezroczystości\
Zdjęcie *cukierki3.jpg* należy skalować do rozmiaru 600 px na 450 px

![](vertopal_cffd48df1a914818a5c3ae95c2811385/media/image1.png){width="2.4430555555555555in"
height="1.8277766841644794in"}

Obraz 1. Logotyp

Strona 2 z 5

**Witryna internetowa**

![](vertopal_cffd48df1a914818a5c3ae95c2811385/media/image2.png){width="7.283333333333333in"
height="4.229166666666667in"}

Obraz 2. Witryna, podstrona Zamówienie

Cechy witryny:\
−strona główna o nazwie *index.html* oraz podstrona *zamowienie.html*\
Cechy wspólne dla obu stron:\
−zastosowany właściwy standard kodowania polskich znaków\
−tytuł strony widoczny na karcie przeglądarki: „Fabryka cukierków"\
−arkusz stylów w pliku o nazwie *styl10.css* prawidłowo połączony z
kodem strony\
−podział strony na bloki: dwa bloki górne, pod nimi baner, poniżej dwa
bloki główne: lewy i prawy oraz na dole stopka. Podział zrealizowany za
pomocą znaczników sekcji, zgodnie z obrazem 2 −zawartość pierwszego
górnego bloku: odnośnik o treści „Zamów cukierki", którego wybranie
prowadzi do strony *zamowienie.html*\
−Zawartość drugiego górnego bloku: odnośnik, którego wybranie prowadzi
do strony *index.html*.

> Odnośnik jest w formie obrazu *logotyp* z tekstem alternatywnym „Nasze
> logo"\
> −zawartość bloku głównego prawego:\
> −nagłówek drugiego stopnia o treści: „Nasza oferta"\
> −tabela o rozmiarze 2x2 (wiersze drugiej kolumny są scalone):\
> −w pierwszym wierszu znajdują się napisy „Kształty" oraz „Możesz
> zamówić dowolny kolor cukierka", łamanie tekstu po słowie „zamówić"\
> −w drugim wierszu znajduje się lista numerowana (uporządkowana) o
> elementach: „cytryna", „liść", „banan"\
> −zawartość stopki: tekst „Autor strony: PESEL", gdzie PESEL to Twój
> numer PESEL. PESEL jest pogrubiony

Strona 3 z 5

Cechy odrębne dla pliku *index.html*:\
−zawartość banera: nagłówek pierwszego stopnia o treści: „Słodka
kraina"\
−zawartość bloku głównego lewego: obraz *cukierki3.jpg* z tekstem
alternatywnym o treści „Nasze cukierki"\
Cechy odrębne dla pliku *zamowienie.html*:\
−zawartość banera: nagłówek pierwszego stopnia o treści: „Strefa
zamówień"\
−zawartość bloku głównego lewego:\
−tekst: „Numer kształtu: "\
−poniżej pole edycyjne typu numerycznego\
−poniżej tekst: „skomponuj swój kolor, podaj RGB: "\
−poniżej trzy pola edycyjne typu numerycznego, każde poprzedzone
tekstem: „R:", „G:", „B:" −przycisk o treści „Zamówienie", którego
wciśnięcie powoduje wywołanie skryptu\
−poniżej paragraf, w którym pierwotnie znajduje się tekst: „Twoje
zamówienie", tekst jest modyfikowany przez skrypt\
−przycisk o treści „Kolor"

**Styl CSS witryny internetowej**\
Cechy formatowania CSS działające na stronie:\
−wspólne dla całej strony: krój czcionki Helvetica\
−wspólne dla dwóch bloków górnych: kolor tła RGB: 146, 184, 112;
wyrównanie tekstu do środka, szerokość 50%, wysokość 170 px\
−wspólne dla banera i stopki: kolor tła RGB: 100, 61, 49; biały kolor
czcionki, wyrównanie tekstu do środka, wysokość 80 px, marginesy
wewnętrzne 5 px\
−wspólne dla bloków głównych: kolor tła RGB: 146, 184, 112; szerokość
50%, wysokość 450 px −odnośnika „Zamówienie" z drugiego bloku górnego:
tło w postaci obrazu *cukierki1.jpg*, margines wewnętrzny prawy 30 px,
dolny 120 px, rozmiar czcionki 150%, bez podkreślenia\
−tabeli i komórki tabeli: obramowanie 2 px, linią kreskowaną zieloną;
marginesy zewnętrzne 30 px, wewnętrzne 20 px\
−nagłówka pierwszego stopnia: odległość między literami 20 px, rozmiar
czcionki 250%

**Skrypt**\
Wymagania dotyczące skryptu:\
−wykonywany po stronie przeglądarki, wywoływany przyciskiem
„Zamówienie"\
−skrypt sprawdza wprowadzony numer kształtu i wypisuje w akapicie
poniżej przycisku „Zamówienie" tekst „Twoje zamówienie to cukierek ", a
dalej w zależności od wprowadzonej wartości: 1 -- „cytryna", 2 --
„liść", 3 -- „banan", inny -- „inny", np. „Twoje zamówienie to cukierek
liść"\
−następnie skrypt sprawdza wartości RGB, a następnie zmienia kolor tła
przycisku „Kolor" na kolor odpowiadający podanej wartości RGB
