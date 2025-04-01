🛠️ Jak zainstalować aplikację OLX Snajper + Discord Webhook

✅ Krok 1: Zainstaluj wymagane biblioteki (Python)
1.1. Zainstaluj Pythona
Pobierz: https://www.python.org/downloads

🔁 Zaznacz opcję: ✅ Add Python to PATH

1.2. Zainstaluj biblioteki z requirements.txt
W folderze z projektem uruchom terminal i wpisz:
pip install -r requirements.txt
lub uruchom plik install requirements.bat

🔍 Krok 2: Skąd wziąć link z OLX?
Wejdź na https://www.olx.pl

Wyszukaj interesujące Cię ogłoszenia (np. "iPhone")

Ustaw odpowiednie filtry (np. „Tylko używane”, „Z wysyłką”, „Smartfony”)

Skopiuj link z paska adresu przeglądarki

Przykład:

https://www.olx.pl/elektronika/telefony/smartfony-telefony-komorkowe/q-iphone/?search%5Border%5D=created_at%3Adesc

⚙️ Krok 3: Skonfiguruj config.json


![image](https://github.com/user-attachments/assets/2ffae2df-b16b-4fe7-b06f-17601208569d)


📢 Krok 4: Jak stworzyć webhook Discord
Wejdź na swój serwer Discord (musisz mieć uprawnienia admina)

Kliknij ⚙️ „Ustawienia serwera” → „Kanały tekstowe” → wybierz kanał

Przejdź do zakładki Integracje → Webhooki

Kliknij „Nowy Webhook”

Nadaj nazwę i wybierz kanał, do którego bot ma wysyłać ogłoszenia

Skopiuj adres webhooka (coś w stylu):

https://discord.com/api/webhooks/1234567890/ABCDEF...

Wklej ten link do config.json w miejscu discord_webhook

▶️ Krok 5: Uruchomienie programu
Po zainstalowaniu wszystkiego i skonfigurowaniu uruchom przez cmd:

python main.py

albo uruchom przez start.bat
