# Splitsie 🧾💸

Een speelse, single-file web-app om **onderlinge kosten eerlijk te verdelen**. Gooi alle bonnetjes erin, en Splitsie rekent uit wie wat aan wie moet betalen — met zo min mogelijk overboekingen.

Geen server, geen account, geen tracking. Alles draait lokaal in de browser.

## ✨ Wat kan het?

- **Personen toevoegen** met eigen naam en gekleurde avatar.
- **Uitgaven invoeren** per persoon: wat, hoeveel, en door wie betaald.
- **Slim delen:** kies per uitgave of *iedereen* meedeelt, *bepaalde mensen*, of geef *eigen bedragen* per persoon op (met een live-check dat de bedragen precies optellen tot het totaal). Voeg je later een nieuw persoon toe, dan gaat die automatisch meedelen in alle "iedereen"-uitgaven.
- **Uitgaven bewerken:** klik op ✏️ bij een uitgave om bedrag, betaler of verdeling achteraf aan te passen, of op 📄 om een uitgave te dupliceren (handig bij terugkerende kosten). Nieuwste uitgaven staan bovenaan.
- **Namen bewerken:** klik op ✏️ bij een naam om die aan te passen zonder de persoon of z'n uitgaven te verliezen.
- **Automatische afrekening:** balans per persoon (inclusief hoeveel ieder in totaal voorschoot) + de minimale set overboekingen om iedereen gelijk te trekken. De afronding gebeurt op de eindafrekening (niet per losse uitgave), zodat centen niet opstapelen; blijft er dan toch een cent over, dan komt die voor rekening van wie voorschoot, met een korte toelichting.
- **QR-code:** toon een QR-code van de deel-link, zodat mensen aan tafel 'm zo kunnen scannen.
- **Wordt automatisch bewaard:** je afrekening blijft in je browser staan, ook na het sluiten van het tabblad. Met de knop "Alles wissen" begin je opnieuw.
- **Delen via link:** de knop "Deel via link" maakt een link met je hele afrekening erin (zonder server). Wie die opent ziet een alleen-lezen weergave en kan er met één klik een eigen bewerkbare kopie van maken.
- **Overzicht kopiëren:** één klik zet een beknopt overzicht (totaal, uitgaven en wie-betaalt-wie) op je klembord, klaar om te plakken en te delen via bijv. WhatsApp.
- **Licht & donker thema:** knop rechtsboven wisselt tussen light en dark mode. Splitsie volgt standaard je systeemvoorkeur en onthoudt je keuze.
- **Meertalig:** kies rechtsboven je taal — Nederlands, Engels, Frans, Duits, Spaans of Chinees. Splitsie start standaard in de taal van je browser en onthoudt je keuze. Iedereen ziet de app in zijn eigen taal, ook bij een gedeelde link.

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

Splitsie verstuurt niets naar een server en heeft geen account. Je afrekening wordt alleen lokaal in je eigen browser bewaard (via localStorage) — per apparaat en per browser, en blijft staan tot je op "Alles wissen" klikt of je browsergegevens wist. De "Deel via link"-functie stopt je afrekening in de link zelf; er komt geen server aan te pas. Het "Kopieer overzicht"-knopje zet alleen tekst op je klembord; delen doe je zelf via de app van jouw keuze.

## 📄 Licentie

MIT — doe ermee wat je wilt.
