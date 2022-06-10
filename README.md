# Przeglądarka V-COCO


### Instalacja
1. Sklonuj repozytorium.

2. Pobierz <a href=https://cocodataset.org/#download/>adnotacje</a> dla zbioru 2014. Jeśli pobieranie na stronie nie działa, można pobrać poleceniem:
curl http://images.cocodataset.org/annotations/annotations_trainval2014.zip -o adnotacje.zip

3. Wypakuj adnotacje w katalogu katalog_z_projektem/coco-data/annotations/

3. Uruchom plik MakeFile. Na Windowsie trzeba doinstalować program make.
    
4. Zainstaluj <a href=https://github.com/philferriere/cocoapi/>API COCO</a> zgodnie z podaną instrukcją.

5. W Anconda zainstaluj pakiet ipywidgets
