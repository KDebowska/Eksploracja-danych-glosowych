# Eksploracja-danych-glosowych

Folder Nagrania zawiera pliki wav (nagrania głosu) i txt (etykiety ze słowami i momentami ich wypowiadania). Znajdują się w nim również osobne foldery dla każdego słowa wyciętego z nagrań. 

Skrypt Podziel_pliki.ipynb wczytuje wszystkie nazwy plików z folderu Nagrania i wrzuca je do listy - każdej nazwie pliku przypisany jest numer. Wybierając numer, wybiera się plik wav o danej nazwie na którym chce się wykonać podział oraz przypisanu mu plik txt z etykietami słów (każdy odpowiadający sobie plik wav i txt mają te same nazwy).


EDIT Joanna Niedziałek:
Foldery zip Area_słowa i Zeros_słowa zawierają po 98 plików tekstowych, gdzie w każdym są po 24 wartości odpowiednio parametru pola powierzchni i parametru gęstości przejść przez zero (w tej samej kolejności dla wszystkich z 24 nagrań).
W pliku Podziel_pliki-Copy1.ipynb można wyeksportować fragmenty nagrań, ALE dla 98 słów (bez słów PRZYCISZ i SPRAWDZ, które nie we wszystkich nagraniach się pojawiły). Żeby to działało poprawnie to chyba trzeba w plikach tekstowych z etykietami usunąć te słowa i zostawić 98 pozostałych ALBO pobrać pliki tekstowe zmienione, które mają po 98 słów.
