Skopiuj powyższe kod w odpowiednie pliki: app.py dla Flask, app.js dla Express.js.
Stwórz plik requirements.txt dla Flask z zawartością Flask==2.0.0 SQLAlchemy==1.4.22.
Stwórz Dockerfile dla obu aplikacji zgodnie z powyższymi konfiguracjami.
Stwórz plik docker-compose.yml z zawartością przedstawioną powyżej.
Skonfiguruj Traefik zgodnie z konfiguracją traefik.yml.
Uruchom aplikacje za pomocą docker-compose up.
Odwiedź interfejs Traefika, aby sprawdzić przekierowanie pod adresem http://localhost.
Wykonaj zapytania GET /cars i GET /cars?year=XXXX oraz POST /addCar na odpowiednich endpointach.
Powinno zadziałać 
