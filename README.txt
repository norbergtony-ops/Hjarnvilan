HJÄRNVILAN – IPHONE-VÄNLIG PWA
================================

INNEHÅLL
- index.html: själva appen
- manifest.webmanifest: appnamn, färger och ikoner
- sw.js: offline-stöd
- icons/: hemskärmsikoner

SNABBTEST UTAN PUBLICERING
Öppna index.html i en vanlig webbläsare. De flesta funktionerna fungerar direkt, men en
PWA behöver ligga på en HTTPS-webbadress för att kunna installeras korrekt och använda
offline-cache. OneDrive/iCloud-fildelning är lagring, inte webbhotell.

PUBLICERA GRATIS MED GITHUB PAGES
1. Skapa/logga in på github.com.
2. Skapa ett nytt offentligt repository, till exempel "hjarnvilan".
3. Packa upp ZIP-filen och ladda upp FILERNA I mappen (inte den yttre mappen) till
   repositoryts rot. index.html måste ligga i roten.
4. Öppna repositoryt: Settings > Pages.
5. Under Build and deployment: välj "Deploy from a branch".
6. Välj branch "main" och mapp "/ (root)", tryck Save.
7. Vänta någon minut. Adressen blir normalt:
   https://DITT-GITHUB-NAMN.github.io/hjarnvilan/

INSTALLERA PÅ IPHONE
1. Öppna den publicerade adressen i Safari.
2. Tryck Dela (fyrkant med pil upp).
3. Välj Lägg till på hemskärmen.
4. Slå på Öppna som webbapp om valet visas.
5. Tryck Lägg till.
6. Starta sedan via ikonen Hjärnvilan.

VIKTIGT OM PÅMINNELSER
- Appens egna notiser/timers är säkrast när appen är öppen.
- För en avisering även när appen är stängd: skapa påminnelsen och tryck "Lägg i kalender".
  Öppna .ics-filen och lägg till händelsen i Kalender.
- En helt lokal statisk PWA saknar en push-server och kan därför inte garantera framtida
  bakgrundsnotiser.

DATA OCH INTEGRITET
Allt sparas lokalt i Safari på enheten. Använd "Exportera min säkerhetskopia" ibland.
Rensning av webbplatsdata i Safari kan radera informationen.

VERSION 2.0 – november 2026
