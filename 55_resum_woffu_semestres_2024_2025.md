# Resum Woffu 2024-2025 per semestres

> Document intern de treball. Lectura feta a partir de captures mensuals de Woffu. Cal validar les xifres amb export CSV/Excel de Woffu abans d'incorporar-les com a xifra definitiva.

## Criteri de calcul

Per parlar d'hores reals de fitxatge visibles:

`hores netes visibles = sortida - entrada - descansos`

Aquest criteri no es el mateix que el resum administratiu de Woffu:

- `Total Woffu`: total computat pel sistema.
- `Diferencia` / `Extra`: saldo administratiu respecte de l'horari teoric.
- `Hores netes visibles`: calcul del temps entre entrada i sortida, restant descansos, a partir de les linies del detall mensual.

Quan hi ha `Vacances`, `Hores d'absencia`, `Naixement i adopcio`, `Incapacitat Temporal` o conceptes similars, el calcul mecanic pot no equivaler a feina efectiva. Per això s'indica tambe una columna de lectura conservadora sense absencies clares detectades per OCR, que s'ha de validar manualment.

## Resum semestral

| Periode | Horari teoric | Hores netes visibles (`sortida - entrada - descansos`) | Diferencia neta vs horari teoric | Total Woffu | Diferencia Woffu | Extra Woffu | Hores netes sense absencies clares detectades | Lectura prudent |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| 2024 gener-juny | 851 h 12 m | 786 h 49 m | -64 h 23 m | 913 h 05 m | +61 h 53 m | +61 h 54 m | 351 h 55 m | El saldo Woffu positiu no coincideix amb el fitxatge net visible; cal revisar permisos/absencies i jornades. |
| 2024 juliol-desembre | 866 h 24 m | 939 h 08 m | +72 h 44 m | 964 h 44 m | +98 h 18 m | +99 h 25 m | 465 h 50 m | Hi ha mesos amb incidencies i possibles permisos/vacances; no llegir el total com a feina efectiva sense validar la columna Jornada. |
| 2025 gener-juny | 744 h 48 m | 792 h 49 m | +48 h 01 m | 883 h 52 m | +139 h 04 m | +139 h 22 m | 251 h 10 m | El resum administratiu es molt superior al fitxatge net; cal separar treball visible de saldos/absencies. |
| 2025 juliol-desembre | 737 h 12 m | 692 h 11 m | -45 h 01 m | 784 h 30 m | +47 h 27 m | +58 h 01 m | 135 h 00 m | Inclou mesos de baixa/IT o absencies clares; no es pot presentar com a treball efectiu sense desglossar. |

## Detall mensual utilitzat

| Mes | Horari teoric | Hores netes visibles | Diferencia neta vs horari teoric | Total Woffu | Diferencia Woffu | Extra Woffu | Hores netes sense absencies clares detectades |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| 2024-01 | 167 h 12 m | 157 h 14 m | -9 h 58 m | 183 h 15 m | +16 h 03 m | +16 h 03 m | 51 h 50 m |
| 2024-02 | 159 h 36 m | 126 h 22 m | -33 h 14 m | 168 h 26 m | +8 h 50 m | +8 h 50 m | 45 h 05 m |
| 2024-03 | 152 h 00 m | 120 h 21 m | -31 h 39 m | 153 h 10 m | +1 h 10 m | +1 h 11 m | 31 h 28 m |
| 2024-04 | 83 h 36 m | 72 h 29 m | -11 h 07 m | 86 h 48 m | +3 h 12 m | +3 h 12 m | 40 h 20 m |
| 2024-05 | 144 h 24 m | 137 h 58 m | -6 h 26 m | 161 h 02 m | +16 h 38 m | +16 h 38 m | 59 h 48 m |
| 2024-06 | 144 h 24 m | 172 h 25 m | +28 h 01 m | 160 h 24 m | +16 h 00 m | +16 h 00 m | 123 h 25 m |
| 2024-07 | 144 h 24 m | 238 h 49 m | +94 h 25 m | 209 h 14 m | +64 h 50 m | +64 h 50 m | 82 h 03 m |
| 2024-08 | 144 h 24 m | 166 h 06 m | +21 h 42 m | 162 h 43 m | +18 h 19 m | +18 h 19 m | 66 h 25 m |
| 2024-09 | 152 h 00 m | 145 h 13 m | -6 h 47 m | 156 h 24 m | +4 h 24 m | +5 h 31 m | 14 h 09 m |
| 2024-10 | 167 h 12 m | 167 h 12 m | +0 h 00 m | 167 h 12 m | - | - | 167 h 12 m |
| 2024-11 | 152 h 00 m | 124 h 31 m | -27 h 29 m | 159 h 11 m | +7 h 09 m | +7 h 09 m | 74 h 21 m |
| 2024-12 | 106 h 24 m | 97 h 17 m | -9 h 07 m | 110 h 00 m | +3 h 36 m | +3 h 36 m | 61 h 40 m |
| 2025-01 | 83 h 36 m | 83 h 53 m | +0 h 17 m | 101 h 50 m | +18 h 14 m | +18 h 14 m | 13 h 59 m |
| 2025-02 | 129 h 12 m | 138 h 48 m | +9 h 36 m | 150 h 59 m | +21 h 47 m | +21 h 47 m | 63 h 35 m |
| 2025-03 | 136 h 48 m | 175 h 23 m | +38 h 35 m | 168 h 02 m | +31 h 14 m | +31 h 14 m | 33 h 38 m |
| 2025-04 | 83 h 36 m | 99 h 26 m | +15 h 50 m | 112 h 00 m | +28 h 24 m | +28 h 29 m | 23 h 44 m |
| 2025-05 | 159 h 36 m | 141 h 47 m | -17 h 49 m | 174 h 03 m | +14 h 27 m | +14 h 35 m | 49 h 32 m |
| 2025-06 | 152 h 00 m | 153 h 32 m | +1 h 32 m | 176 h 58 m | +24 h 58 m | +25 h 03 m | 66 h 43 m |
| 2025-07 | 159 h 36 m | 135 h 18 m | -24 h 18 m | 177 h 40 m | +18 h 04 m | +18 h 11 m | 68 h 24 m |
| 2025-08 | 30 h 24 m | 33 h 39 m | +3 h 15 m | 40 h 31 m | +10 h 07 m | +10 h 10 m | 7 h 40 m |
| 2025-09 | 91 h 12 m | 94 h 02 m | +2 h 50 m | 104 h 01 m | +12 h 49 m | +23 h 14 m | 7 h 53 m |
| 2025-10 | 167 h 12 m | 165 h 05 m | -2 h 07 m | 173 h 35 m | +6 h 23 m | +6 h 26 m | 51 h 03 m |
| 2025-11 | 152 h 00 m | 152 h 00 m | +0 h 00 m | 152 h 00 m | - | - | 0 h 00 m |
| 2025-12 | 136 h 48 m | 112 h 08 m | -24 h 40 m | 136 h 43 m | +0 h 04 m | - | 0 h 00 m |

## Observacions metodologiques

- Per valorar hores reals visibles s'ha utilitzat el calcul diari `sortida - entrada - descansos`.
- Les columnes `Diferencia` i `Extr. a compensar` es mantenen com a dades administratives de Woffu.
- Els resums de Woffu poden computar hores justificades, permisos, absencies o regularitzacions i, per tant, no sempre coincideixen amb el temps real visible de fitxatge.
- Les dades s'han de contrastar amb el detall mensual, la columna `Jornada`, les absencies, els permisos, les vacances i les compensacions.

## Cautela

No presentar la columna `Hores netes sense absencies clares detectades` com a xifra definitiva. Es una ajuda per detectar mesos amb moltes absencies o permisos visibles, pero requereix validacio manual o export de Woffu.
