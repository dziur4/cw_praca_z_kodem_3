# cw_praca_z_kodem

Instalacja:

Sklonuj repozytorium: git clone git@github.com:studentmarekwsb/cw_praca_z_kodem.git

Przejdź do katalogu projektu: cw_praca_z_kodem

Utwórz wirtualne środowisko Pythona: python3 -m venv .venv

Aktywuj wirtualne środowisko:

Dla systemów Linux/Mac: source venv/bin/activate

Dla systemu Windows: venv\Scripts\activate.bat

Zainstaluj zależności: pip install -r requirements.txt


Uruchomienie:

Uruchom aplikację Flask:

- flask run lub
- python -m flask run
- 
Otwórz przeglądarkę i przejdź do adresu: http://127.0.0.1:5000/

Testowanie:

Pobranie strony głównej: curl http://127.0.0.1:5000/

Pobranie strony hello: curl http://127.0.0.1:5000/hello

Pobranie strony hello z podanym imieniem: curl http://127.0.0.1:5000/hello/<name> 

(<name>="twoje imię")

Pamiętamy żeby podczas użycia flask run, otworzyć nowey terminal, w celu wpisania curl http://127.0.0.1:5000/


## Dlaczego ważne jest README w projekcie ?

Plik README jest dokumentem wprowadzającym, który zawiera podstawowe informacje o projekcie, takie jak jego cel, sposób użycia, instalacji, a także zasady współpracy, co czyni go niezbędnym przewodnikiem dla nowych użytkowników i współtwórców.


