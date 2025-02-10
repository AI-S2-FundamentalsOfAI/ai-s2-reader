# Reader AI Semester 2

Samengesteld uit materiaal van Analytical Reasoning, High Performance Progamming en Embedded Operating Systems.

## Benodigd
De reader zou op een standaard TexLive distributie *as-is* te compilen moeten zijn. Aanbevolen wordt om eerst `pdflatex main.tex` te runnen, dan `bibtex main`, gevolgd door nog tweemaal `pdflatex main.tex`. Zo staan alle referenties goed.

Publicatie wordt automatisch afgehandeld door GitHub Actions. Hiervoor dient de `publish` tag naar de te publiceren commit te verwijzen. Dit kan met `git tag -f publish` gevolgd door `git push -f --tags`. De force flag is nodig omdat Git tags by default niet wil hergebruiken, maar dat in deze setup wel nodig is om een voorspelbare link te krijgen waarnaar vanaf Canvas kan worden verwezen.
