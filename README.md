# Personeelsplanning met SCIP (PySCIPOpt)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GEBRUIKER/REPO/HEAD?labpath=personeelsplanning.ipynb)

Een rosterprobleem (8 medewerkers, 7 dagen, 3 diensten) als gemengd-geheeltallig lineair programma,
opgelost met [SCIP](https://www.scipopt.org/) via [PySCIPOpt](https://github.com/scipopt/PySCIPOpt).

## Inhoud

| Bestand | Doel |
|---|---|
| `personeelsplanning.ipynb` | Het notebook (uitleg, model, visualisatie, oefeningen) |
| `requirements.txt` | Python-afhankelijkheden die Binder installeert |

## Starten op mybinder
[https://mybinder.org/v2/gh/jsoons/mybinder/HEAD?labpath=personeelsplanning.ipynb]
[https://mybinder.org/v2/gh/jsoons/mybinder/]




## Op mybinder.org zetten


1. Zet beide bestanden in de **root** van een publieke Git-repository (GitHub, GitLab, ...).
2. Ga naar <https://mybinder.org>, kies GitHub/GitLab/Git-URL en vul de repo-URL in
   (optioneel bij *Path to a notebook file*: `personeelsplanning.ipynb`, type "File").
3. Vervang in de badge bovenaan `GEBRUIKER/REPO` door je eigen waarden.

De eerste build duurt enkele minuten; PySCIPOpt wordt als kant-en-klaar wheel geïnstalleerd (geen compilatie nodig).

## Getest met

Python 3.12, PySCIPOpt 6.3.0, pandas 3.0, matplotlib 3.10, numpy 2.4. Oplostijd: een fractie van een seconde.
