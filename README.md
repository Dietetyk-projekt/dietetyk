# dietetyk

•	Tworzenie lokalnej bazy danych - https://msdn.microsoft.com/pl-pl/library/ms233763(v=vs.120).aspx#bkmk_createnewsqldb
•	Łączenie się lokalnymi bazami danych - https://msdn.microsoft.com/pl-pl/library/ms171890.aspx
•	GitHub do Visual Studio - https://visualstudio.github.com/
•	Jak używać GitHuba - https://guides.github.com/activities/hello-world/

Dietetyk:
Zdecydowałem jednak że zrobimy na bazie lokalnej, ewentualnie w kwestii rozwoju można zmienić na bazę współdzieloną w sieci lub całkowicie sieciową (opisane w części do rozwinięcia)
Moduły niezbędne
•	Moduł główny – Strona główna z zakładkami na górze  
o	Lista pacjentów – po lewej stronie lista pacjentów (imię i nazwisko) po naciśnięciu na pacjenta po prawej stronie wyświetlają się dane pacjenta, dobrane przez program normy, na dole przycisk układaj dietę
	Dane pacjenta po prawej stronie:
•	TEXTBOXY - Płeć, Wiek, Masa ciała rzeczywista, Wzrost, Obwód talii, Obwód bioder
	LABELE - Po prawej stronie wyświetla się BMI i WHR
	Wyniki badań pacjenta
•	TEXTBOXY - Cholesterol całkowity, LDL – cholesterol, HDL – cholesterol, Triglicerydy, Glukoza, WBC-leukocyty, LYM krwii obwodowej, RBC-erytrocyty, HGB-hemoglobina, Kwas moczowy, Mocznik, Kreatynina, Bilirubina, Albuminy, Potas, Sód, Wapń, Magnez, Żelazo
	TEXTBOX - Okno na wpisanie uwag dotyczących pacjenta na temat chorób itp.
	Na dole pod listą pacjentów przycisk dodaj pacjenta

	Dodaj pacjenta – Na górze napis dodaj pacjenta, poniżej pola takie same jak  przy wyświetlaniu pacjenta do wpisania danych pacjenta na dole po prawej przycisk zapisz – dopisuje pacjenta do bazy pacjentów
o	Normy – po lewej lista norm zależnie od wieku, płci, masy ciała, wzrostu, po prawej po naciśnięciu na normę wyświetlają się wybrane normy do sprawdzenia
	Wiek, masa ciała, rodzaj aktywności
	Energia, Białko, Tłuszcz, sód, potas, wapń, fosfor, magnez, żelazo, cynk, miedź
	Witamina A,D,E,B1,B2,PP,B6,Foliany,B12,C

	Dodaj normy – Na górze napis dodaj normy, poniżej pola do wpisania danych takich samych jak wyżej, na dole po prawej przycisk zapisz – dopisuje normy do bazy norm
o	Lista produktów - po lewej stronie lista produktów (nazwa, producent) po naciśnięciu na produkt po prawej stronie wyświetlają się informacje na jego temat.
	Kcal, Białko, Tłuszcz, kw.tł. nasycone, kw. tł. Jednonienasycone, kw. tł. Wielonienasycone, Cholesterol, Węglowodany ogółem, Sacharoza, Laktoza, Błonnik pokarmowy, Sód, Potas, Wapń, Fosfor, Magnez, Żelazo, Cynk, Miedź, Mangan, A, D, E, Tiamina, Ryboflawina, Niacyna, B6, Foliany, B12, C

	Dodaj produkt – Na górze napis dodaj produkt, poniżej pola do wpisania danych takie jak wyżej na dole po prawej przycisk zapisz



o	DO OPRACOWANIA - Układanie diety – otwiera się całkowicie nowe okno, na górze napisane imię i nazwisko pacjenta, poniżej jego zapotrzebowanie na kluczowe składniki
Moduły rozwojowe
•	Logowanie do programu po włączeniu programu, dzięki czemu wiemy jakie elementy pobierać z serwera dla danego użytkownika
•	Terminarz do zapisywania pacjentów
•	Informacje ze świata dietetyki – jakieś artykuły itp.
•	Przeniesienie bazy – część bazy np. baza pacjentów, baza podstawowych produktów, baza podstawowych przepisów, podstawowe normatywy w formie offline, a dodatkowe produkt, normatywy i przepisy w formie online – współdzielone między użytkownikami
•	Lista przepisów
•	Dodaj przepis
•	Spersonalizowane drukowanie diety i zaleceń
