HJÄRNVILAN 3.0
===============

Detta är en statisk, iPhone-anpassad PWA. Öppna INSTALLERA-OCH-UPPDATERA.txt för exakta steg.

Huvudfunktioner
- Historiska dagsvärden med datumväljare och navigeringspilar.
- 7-dagarsöversikt för energi, hjärndimma och sömn.
- Aktivitetssförslag som ändras efter dagens värden och det rullande sjudagarsmönstret.
- Registrering av energi, hjärndimma, sömn, belastning, vatten, vila, promenad, andning och skärmfri paus.
- Dagens tre viktigaste och anteckningar.
- CSV-export samt JSON-säkerhetskopia/återställning.
- Mörkt läge, extra stor text, lugnt läge och vilotimer.
- Offline-stöd via service worker.

Integritet
Appen har ingen serveranslutning för personuppgifter. Det du registrerar lagras i webbläsarens lokala lagring på enheten. Lägg inte exporterade säkerhetskopior i ett offentligt GitHub-repository.

Filer
- index.html: hela appens gränssnitt och logik
- manifest.webmanifest / manifest.json: PWA-metadata
- sw.js / service-worker.js: offline-cache (dubbletter för kompatibilitet vid uppdatering)
- icons/: appikoner
