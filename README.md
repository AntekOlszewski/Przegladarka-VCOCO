# Przeglądarka V-COCO


### Instalacja
1. Należy sklonować repozytorium.

2. Należy pobrać <a href=https://cocodataset.org/#download/>adnotacje</a> dla zbioru 2014. Jeśli pobieranie na stronie nie działa, można pobrać poleceniem:
curl http://images.cocodataset.org/annotations/annotations_trainval2014.zip -o adnotacje.zip

3. Należy wypakować adnotacje w katalogu katalog_z_projektem/coco-data/annotations/

3. Należy uruchomić plik MakeFile. Na Windowsie trzeba doinstalować program make.
    
4. Należy zainstalować <a href=https://github.com/philferriere/cocoapi/>API COCO</a> zgodnie z podaną instrukcją.

5. W Anconda należy zainstalować pakiet ipywidgets


### Korzystanie z przeglądarki

Przeglądarka znajduje się w pliku V-COCO.ipynb.
Należy z listy wybrać szukanne czynności, zaznaczyć czy wszystkie mają znajdować się na jednej instancji ludzkiej, a następnie kliknąć przycisk "Search".

#### Sterowanie
Search - wyszukuje obrazy zgodne z podanymi kryteriami wyszukiwania.
Next/Previous image - wyświetla następny/poprzedni obraz spełniający kryteria wyszukiwania.
Next/Previous human instance - wyświetla nastętępną/poprzednią instancje ludzką na aktualnie wyświetlanym obrazie, instancja może niespełniać kryteriów wyszukiwania.
