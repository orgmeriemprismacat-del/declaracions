# Pla d'extraccio de missatges per parts

Objectiu: localitzar i guardar nomes els missatges necessaris per contrarestar acusacions concretes de la carta de Jordi, sense descarregar 56 GB de correu.

## Criteri general

No cal extreure "tot Gmail". Cal treballar per acusacio:

1. identificar la frase concreta de Jordi;
2. buscar missatges amb dates, remitents i paraules clau;
3. guardar nomes el fil o missatge que prova o contextualitza el punt;
4. apuntar-lo a la matriu i a l'annex corresponent.

## Prioritat 1: proves directes contra acusacions greus

- "mal tracte continu de Meriem"
- "tasques inassumibles"
- "no se'm comunicaven les coses / se'm deien a posteriori"
- "correccions tardanes / publicacions sense esperar-me"
- "mobbing / bullying"
- "alta forcosament interrompuda"
- "jornada sencera / hores extres / vacances acumulades"
- "Cristina / suposada mentida d'Adam"

## Prioritat 2: patrons de context

- recordatoris previs per privat abans de reunions o canals compartits;
- replanificacions i adaptacions de terminis;
- Jordi sense contestar correus, Trello o xats;
- Jordi indicant que faria una tasca i entregant-la tard o no entregant-la;
- organitzacio creada per facilitar-li la feina;
- suport extern contractat quan no es podia esperar mes.

## Cerques Gmail recomanades

### Per persona

```text
from:(correccio@prisma.cat OR tutoria@prisma.cat OR tutoria.prisma.cat@gmail.com) after:2024/01/01 before:2026/07/15
to:(correccio@prisma.cat OR tutoria@prisma.cat OR tutoria.prisma.cat@gmail.com) after:2024/01/01 before:2026/07/15
```

### Per temes clau

```text
("Fundae" OR "FUNDAE") after:2024/01/01 before:2026/07/15
("xarxes" OR "XS" OR "publicacio" OR "publicació") (Jordi OR correccio OR tutoria) after:2024/01/01 before:2026/07/15
("JASOM" OR "Ja som mestres") after:2024/10/01 before:2024/12/31
("CONCURS BLOG EDUCAT" OR "Educat") after:2024/10/01 before:2024/12/31
("ALBUM" OR "Rastreja" OR "Rastrejals") after:2025/09/01 before:2025/11/01
("Cristina") after:2024/01/01 before:2026/07/15
("vacances" OR "hores" OR "compensar" OR "mitja jornada" OR "jornada sencera") after:2024/01/01 before:2026/07/15
```

### Per acusacions de maltracte o mobbing

```text
("mobbing" OR "bullying" OR "tractat" OR "maltracte" OR "mal tracte" OR "no puc venir") after:2024/01/01 before:2026/07/15
```

## Com guardar cada prova

Per cada prova trobada:

- descarregar o capturar nomes el fil necessari;
- guardar-la en una carpeta d'evidencies;
- posar un nom amb data i tema, per exemple:

```text
2025-01-31_xarxes_no_violencia_correccio_tardana.pdf
2024-12-03_jasom_mailing_revisions.pdf
2025-09-12_fundae_replanificacio_whatsapp.png
```

## Registre minim per cada prova

Afegir a la matriu:

```text
Prova: P-XX
Data:
Canal: Gmail / WhatsApp / Trello / Acta / Woffu
Que acredita:
Quina acusacio contesta:
Estat: forta / context / pendent de reforc
Fitxer:
```

## Regla de seguretat

Si un missatge conte salut, baixa medica o psicoleg, no usar-lo per jutjar l'estat de Jordi. Usar-lo nomes, si cal, per acreditar comunicacions laborals objectives: disponibilitat, horaris, sol.licituds, resposta de l'empresa o replanificacio de tasques.
