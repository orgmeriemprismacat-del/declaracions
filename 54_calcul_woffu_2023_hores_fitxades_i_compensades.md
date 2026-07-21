# Calcul Woffu 2023 - hores netes de fitxatge i saldos administratius

> Document intern de treball. Aquest calcul s'ha fet a partir de les captures Woffu disponibles. Cal validar-lo amb export CSV/Excel de Woffu si es vol incorporar com a xifra definitiva en una contestacio formal.

## Criteri correcte de lectura

Per parlar d'hores reals de fitxatge visibles a les captures mensuals, el criteri principal ha de ser:

`hores netes visibles = sortida - entrada - descansos`

Aixo s'ha de separar del resum administratiu de Woffu:

- `Horari teoric`: hores previstes segons el calendari/jornada assignada.
- `Total d'hores Woffu`: total que Woffu computa en el detall mensual, que pot incorporar hores justificades, permisos, absencies o regularitzacions.
- `Diferencia` / `Extr. a compensar`: saldo administratiu que Woffu mostra respecte de l'horari teoric.

Per tant, si l'objectiu es saber quantes hores consten com a treballades o fitxades en el detall, no s'ha d'agafar la columna `Diferencia` ni el resum d'`Extr. a compensar`. Cal calcular cada dia amb entrada, sortida i descansos.

## Advertiments importants

- Aquest calcul es basa en la lectura de captures; pot tenir petites diferencies de minuts per OCR o lectura visual.
- Quan una fila esta marcada com a `Hores d'absencia`, `Vacances`, `Accident o enfermetat`, `Naixement i adopcio`, `Incapacitat Temporal` o similar, el calcul mecanic d'entrada/sortida pot no equivaler a feina efectiva. En aquests casos cal mirar sempre la columna `Jornada`.
- El resum de Woffu pot donar positiu encara que el calcul net visible no mostri una jornada completa, perquè Woffu pot computar saldos, absencies justificades o compensacions.
- Aquest annex no nega que Jordi pogues fer hores per sobre de l'horari teoric en moments concrets. El que corregeix es que aquestes hores no es poden acreditar nomes amb `Diferencia/Extra`, ni es poden convertir automaticament en prova de jornada completa sostinguda.

## Detall mensual gener-setembre 2023

| Mes 2023 | Jornada que consta majoritariament | Horari teoric | Hores netes visibles (`sortida - entrada - descansos`) | Diferencia neta vs horari teoric | Total Woffu | Diferencia / extra Woffu | Lectura prudent |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| Gener | `Horari Jordi 1/2` | 78 h 45 m | 79 h 40 m | +0 h 55 m | 87 h 22 m | +8 h 37 m | El fitxatge visible queda practicament ajustat a mitja jornada; no acredita jornada completa. |
| Febrer | `Horari Jordi 1/2` | 71 h 15 m | 71 h 16 m | +0 h 01 m | 78 h 09 m | +6 h 54 m | El fitxatge visible queda ajustat a l'horari teoric. |
| Marc | `Horari Jordi 1/2` | 86 h 15 m | 86 h 24 m | +0 h 09 m | 90 h 52 m | +4 h 37 m | El fitxatge visible queda ajustat a l'horari teoric. |
| Abril | `Horari Jordi 1/2` | 52 h 30 m | 56 h 43 m | +4 h 13 m | 62 h 14 m | +9 h 44 m | Hi ha excés puntual, pero no jornada completa. |
| Maig | `Horari Jordi 1/2` | 82 h 30 m | 88 h 04 m | +5 h 34 m | 94 h 27 m | +11 h 57 m | Hi ha excés puntual, pero no jornada completa. |
| Juny | `Horari Jordi 1/2` | 82 h 30 m | 79 h 19 m | -3 h 11 m | 97 h 43 m | +15 h 13 m | El saldo Woffu surt positiu, pero el fitxatge net visible no mostra excés real mensual; cal creuar amb jornades/absencies. |
| Juliol | `Horari Jordi 1/2` | 56 h 15 m | 55 h 35 m | -0 h 40 m | 63 h 18 m | +7 h 03 m | El fitxatge net visible queda lleugerament per sota de l'horari teoric. |
| Agost | `Horari Jordi 1/2` | 82 h 30 m | 82 h 26 m | -0 h 04 m | 105 h 19 m | +22 h 49 m | El saldo Woffu surt positiu, pero el fitxatge net visible queda practicament ajustat; el mes inclou incidencies. |
| Setembre | `Horari Jordi 1/2` | 75 h 00 m | 168 h 01 m | +93 h 01 m | 170 h 20 m | +95 h 20 m | Aquest es el mes que mostra clarament un volum molt superior a la mitja jornada. |

## Resums utils 2023

| Periode | Horari teoric | Hores netes visibles (`sortida - entrada - descansos`) | Diferencia neta vs horari teoric | Total Woffu | Diferencia / extra Woffu | Lectura prudent |
| --- | ---: | ---: | ---: | ---: | ---: | --- |
| Gener-maig 2023 | 371 h 15 m | 382 h 07 m | +10 h 52 m | 413 h 04 m* | +41 h 49 m | No acredita jornada completa ni insuficiencia estructural de la mitja jornada. |
| Juny-agost 2023 | 221 h 15 m | 217 h 20 m | -3 h 55 m | 266 h 20 m | +45 h 05 m | No soste que Jordi fes jornada completa durant juny, juliol i agost. |
| Gener-agost 2023 | 592 h 30 m | 599 h 27 m | +6 h 57 m | 679 h 24 m | +86 h 54 m | El fitxatge net visible queda molt lluny d'una jornada completa sostinguda. |
| Setembre 2023 | 75 h 00 m | 168 h 01 m | +93 h 01 m | 170 h 20 m | +95 h 20 m | Setembre s'ha de tractar com a periode concret i diferenciat. |
| Gener-setembre 2023 | 667 h 30 m | 767 h 28 m | +99 h 58 m | 849 h 44 m | +182 h 14 m | L'increment rellevant es concentra sobretot al setembre. |

`*` El resum agregat de Woffu gener-maig que constava en una lectura previa marcava 413 h 06 m. La suma manual mensual dona 413 h 04 m. Diferencia pendent de validar amb export.

## Observacions objectives

- El calcul s'ha fet amb el criteri `sortida - entrada - descansos`.
- De gener a maig de 2023, l'horari teoric visible suma 371 h 15 m i les hores netes visibles sumen 382 h 07 m.
- De juny a agost de 2023, l'horari teoric suma 221 h 15 m i les hores netes visibles sumen 217 h 20 m.
- De gener a agost de 2023, l'horari teoric suma 592 h 30 m i les hores netes visibles sumen 599 h 27 m.
- Setembre de 2023 mostra 168 h 01 m netes visibles davant 75 h teoriques.
- Les columnes `Total Woffu`, `Diferencia` i `Extr. a compensar` es mantenen a la taula com a dades administratives del sistema, no com a substitut del calcul d'hores netes visibles.

## Cautela

No afirmar que Jordi no fes mai hores de mes. Les dades mostren algun excés puntual i un increment clar al setembre. L'argument correcte és que les hores netes visibles no acrediten jornada completa sostinguda de gener a agost ni que la mitja jornada fos estructuralment insuficient. Tampoc s'ha d'usar la columna `Diferencia/Extr. a compensar` com si fos equivalent a hores reals treballades.
