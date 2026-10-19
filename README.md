# Panell paper trading

**Només simulació, cap ordre real.** Aquest panell mostra dades de *paper trading* (comptes simulats) i consulta preus públics d'OKX des del navegador. No conté claus ni credencials i no executa cap ordre real.

Pàgina: https://carlesrabadagarces-hub.github.io/desk-panell/

## Com s'actualitza

- `index.html` és una còpia de `desk_v3.html`, regenerat automàticament (cada rebuild del panell, aprox. cada 15 min).
- Per evitar que el repositori creixi amb un fitxer de ~4 MB a cada actualització, la branca `main` es manté amb **un sol commit**: cada publicació fa `git commit --amend` i `git push --force`. Aquest repositori és només de publicació; l'historial no es conserva expressament.
