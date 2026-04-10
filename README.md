# hetwerktgewoon.nl

Landingspagina voor Het Werkt Gewoon — procesoptimalisatie voor kleine teams.

## Stack
Puur HTML/CSS. Geen framework, geen build step. Direct deployen via Vercel.

## Deployen
1. `gh repo create hetwerktgewoon --public` (of via GitHub UI)
2. Push deze map naar de repo
3. Importeer repo in Vercel → deploy
4. Koppel domein hetwerktgewoon.nl via Vercel dashboard

## Itereren via Claude Code
Start Claude Code in deze map en gebruik onderstaande prompts:

### Copy aanpassen
"Pas de hero headline aan naar: [nieuwe tekst]"
"Voeg een vijfde pain point toe: [titel] — [beschrijving]"
"Maak de hero-sub tekst korter en directer"

### Secties toevoegen
"Voeg een 'Over mij' sectie toe na de how-sectie met een korte intro en foto placeholder"
"Voeg een eenvoudig contactformulier toe aan de CTA sectie (naam, email, bedrijf, bericht)"
"Voeg een FAQ sectie toe met 4 vragen"

### Eerste echte case toevoegen
"Vervang de oplossingsrichtingen sectie door een case study blok met: klant [naam/sector], probleem, oplossing, resultaat"

### Stijl aanpassen
"Verander de accentkleur van groen naar [kleur]"
"Maak de navigatie sticky met een subtiele blur achtergrond bij scrollen"
"Voeg subtiele fade-in animaties toe aan secties bij scrollen"

### Technisch
"Voeg Open Graph meta tags toe voor sociale deling"
"Maak een favicon op basis van de initialen HWG"
"Optimaliseer voor mobiel: check alle padding en font sizes op kleine schermen"
