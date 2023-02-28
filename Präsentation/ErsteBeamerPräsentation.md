# Latech Beamer Markdown

% Präsentation in Markdown
% Referent: Noah Amjad
% Date \today


---
theme:  "AnnArbor"
header: includes:
colortheme: "seahorse"
fonttheme: "structorbold"
author:
---

# Erste Folie

Dies ist eine Mit Markdown erstellte Präsentation und übersetzt mit Pandoc in einer Beamer Präsentation als PDF.
```bash
pandoc -t beamer <filename.md> -o <praesentationsname.pdf>
```

# Aufzählung mit Formatierungen

- punkt 1 mit *kursiven Text*
- punkt 2 mit **fetter Text**
- punkt 3 mit ~~durchgestrichener Text~~

# Formeln und Quoting
>**Merke**
>Markdown und Pandoc sind cool und mächtig.

$$ \int_a\limits^\infty \frac{x^2-a}{e^(x-b)} dx $$
$$ f(x) = sqrt(2-x) $$
$$ a^b $$
$$ U_eff = \frac{U^2}{\sqrt{2}} $$

# Bilder einblenden

````
![Umlet Screenshot](UMLet_screenshot.png)
````
![Umlet Screenshot](https://cdn1.epicgames.com/offer/fn/23BR_C4S1_EGS_Launcher_Blade_2560x1440_2560x1440-70d48b6b897fd8509891ebeb1c160117)