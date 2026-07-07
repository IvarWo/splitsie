# Splitsie 🧾💸

Een speelse, single-file web-app om **onderlinge kosten eerlijk te verdelen**. Gooi alle bonnetjes erin, en Splitsie rekent uit wie wat aan wie moet betalen — met zo min mogelijk overboekingen.

Geen server, geen account, geen tracking. Alles draait lokaal in de browser.

## ✨ Wat kan het?

- **Personen toevoegen** met eigen naam en gekleurde avatar.
- **Uitgaven invoeren** per persoon: wat, hoeveel, en door wie betaald.
- **Slim delen:** kies per uitgave of *iedereen* meedeelt, of alleen *bepaalde mensen* (jij vinkt aan wie).
- **Automatische afrekening:** balans per persoon + de minimale set overboekingen om iedereen gelijk te trekken.
- **Betaalverzoeken sturen** (optioneel): open Tikkie, stuur een e-mail, of kopieer een kant-en-klaar bericht voor WhatsApp/je bankapp. Op mobiel gebruikt het het native deelmenu.

## 🚀 Publiceren op GitHub Pages

1. Maak een nieuwe repository op GitHub en upload `index.html` en `README.md`.
2. Ga naar **Settings → Pages**.
3. Kies bij *Source* de branch `main` en map `/ (root)`, en klik **Save**.
4. Na een minuutje staat je app live op `https://<gebruikersnaam>.github.io/<repo-naam>/`.

> Tip: pas in `index.html` de "GitHub"-link onderaan aan naar de URL van je eigen repo.

## 🖥️ Lokaal draaien

Gewoon `index.html` dubbelklikken. Klaar. (Voor de betaal-deelfunctie op mobiel werkt een `https://`-adres, zoals GitHub Pages, het beste.)

## 🧮 Hoe de verdeling werkt

Elke uitgave wordt verdeeld over de mensen die eraan meedoen. De betaler krijgt het volledige bedrag als tegoed. Splitsie telt alle tegoeden en schulden op tot één balans per persoon, en berekent daarna de kortste route om iedereen op nul te krijgen — dus niet iedereen betaalt iedereen, maar zo min mogelijk transacties.

## 🔒 Privacy

Splitsie verstuurt zelf niets en slaat niets op. Betaalverzoeken openen jouw eigen apps; de bedragen vul je daar zelf definitief in.

## 📄 Licentie

MIT — doe ermee wat je wilt.
