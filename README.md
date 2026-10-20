# Lietuvos elektros biržos kainų prognozavimas mašininio mokymosi metodais

Kursinio darbo projektas. Autorius: Pijus Urbonas, Klaipėdos universitetas, Informatika (duomenų analitika).

## Darbo tema
Lietuvos elektros biržos kainų prognozavimas mašininio mokymosi metodais.

## Tyrimo tikslas
Ištirti, kas lemia Lietuvos elektros biržos kainas, ir palyginti modelius, prognozuojančius jas savaitei į priekį.

## Tyrimo klausimas
Ar mašininio mokymosi modelis (XGBoost), naudojantis orų ir elektros gamybos duomenis, prognozuoja Lietuvos zonos paros prieš (day-ahead) elektros kainas savaitei į priekį tiksliau nei paprastas atskaitos modelis (kaina prieš savaitę)?

## Duomenų šaltiniai
| Šaltinis | Duomenys | Nuoroda |
|---|---|---|
| ENTSO-E Transparency Platform | Valandinės LT zonos biržos kainos, vartojimas, gamyba pagal šaltinį | https://transparency.entsoe.eu/ |
| Open-Meteo | Istoriniai orų duomenys: temperatūra, vėjas, saulės spinduliuotė | https://open-meteo.com/en/docs/historical-weather-api |

Tikslinis kintamasis: paros prieš elektros kaina Lietuvos zonoje, EUR/MWh.

## Projekto struktūra
- `data/` – neapdoroti ir paruošti duomenys
- `notebooks/` – Jupyter užrašinės analizei ir modeliams
- `figures/` – grafikai ir vizualizacijos
- `reports/` – kursinio darbo ataskaitos ir juodraščiai

## Įrankiai
Python, pandas, scikit-learn, XGBoost, Jupyter.
