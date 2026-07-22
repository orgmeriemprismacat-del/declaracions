# Annex Woffu Jordi - horaris, jornada i disponibilitat

> Document intern de treball. Aquest annex servirà per analitzar els registres de Woffu de Jordi i vincular-los amb afirmacions concretes de la carta, actes, tasques pendents i comunicacions. Cal evitar utilitzar Woffu com a control personal genèric; només s'ha d'usar per qüestions laborals verificables.

## Objectiu

El Woffu de Jordi pot servir per acreditar:

- hores treballades i hores fitxades;
- dies de vacances, absències, baixes o permisos;
- hores compensades o acumulades;
- horaris reals d'entrada i sortida;
- compliment o incompliment de la franja acordada de disponibilitat;
- dies en què constava que treballava però no hi havia avís d'entrada/sortida o resposta;
- contradiccions entre tasques pendents, terminis i disponibilitat real.

## Cautela principal

No s'ha d'utilitzar el Woffu per fer una crítica personal global de Jordi. Ha de vincular-se sempre a una afirmació concreta o a un episodi documentat.

Exemples d'ús correcte:

- "El dia X constava jornada/fitxatge i hi havia una reunió/tasca pendent; no consta avís d'absència o canvi d'horari."
- "En el període X-Y, els registres mostren vacances/hores compensades, cosa que contextualitza l'afirmació sobre manca de descans."
- "La franja 10-14 h constava com a disponibilitat acordada, però en aquests dies concrets no es va respectar o no es va comunicar canvi."

Exemples d'ús que cal evitar:

- "Jordi no treballava mai."
- "Jordi s'aprofitava."
- "Fitxava sense treballar" si no hi ha prova complementària molt clara.
- conclusions d'intenció o mala fe sense suport documental.

## Captures Woffu rebudes

El 20/07/2026 s'han incorporat captures de Woffu a:

`annexos_captures/WF_woffu_jordi/CAPTURES WOFFU/`

Inclouen:

- resum general del registre mensual de jornada;
- resums anuals 2023, 2024, 2025 i 2026;
- captures mensuals de presència de gener 2023 a juliol 2026.

Índex específic:

- `49_index_captures_woffu_jordi.md`

## Primera lectura prudent de les captures

### Resums anuals

Les captures de resum anual mostren hores totals, hores justificades, hores ordinàries i hores extra. Són útils per contrastar afirmacions generals sobre manca de descans, hores acumulades o volum de jornada, però no expliquen per si soles la causa de cada hora o absència. Per això s'han de creuar amb actes, converses, permisos, vacances i tasques concretes.

Captures principals:

- `[WF-REG-RESUM]`
- `[WF-REG-2023]`
- `[WF-REG-2023-01-05]`
- `[WF-REG-2023-06-09]`
- `[WF-REG-2023-10-12]`
- `[WF-REG-2024]`
- `[WF-REG-2025]`
- `[WF-REG-2026]`

### Any 2023 i afirmacio sobre insuficiencia de la mitja jornada

Les captures de 2023 son rellevants per contestar l'afirmacio de Jordi segons la qual la mitja jornada era insuficient i, des de determinat moment, hauria estat assumint de fet una jornada sencera.

### Criteri de calcul

La columna `Extr. a compensar` no s'ha de llegir com si fossin hores reals treballades. Per valorar el temps real de fitxatge visible, el criteri principal ha de ser:

`treball efectiu = Hores ordinàries + Extr. a compensar`

Aquest calcul s'ha de separar del resum administratiu de Woffu (`Total d'hores`, `Horari teoric`, `Diferencia` i `Extr. a compensar`), perquè el resum pot incorporar absencies, permisos, vacances, accident/malaltia, compensacions o regularitzacions segons la icona i el tipus de jornada.

Si una sortida consta abans que l'entrada, s'ha interpretat com un fitxatge que passa de mitjanit. En dies amb incidencies o icones de compensacio/absencia, cal mirar sempre la columna `Jornada` i no fer servir una sola columna de Woffu de manera aillada.

Les diferencies mensuals visibles a Woffu entre `Total d'hores` i `Horari teoric` s'han de considerar saldos administratius si no s'han contrastat amb les entrades, sortides, descansos i tipus de jornada de cada dia.

Aquest criteri queda desenvolupat a:

- `54_calcul_woffu_2023_hores_fitxades_i_compensades.md`
- `55_resum_woffu_semestres_2024_2025.md`

Lectura prudent:

- entre gener i agost de 2023, les captures mensuals mostren majoritariament `Horari Jordi 1/2`, amb diferencies horaries puntuals o hores a compensar;
- de gener a maig de 2023 consten 355 h 39 m treballades davant 371 h 15 m teoriques, més 57 h 27 m justificades;
- de juny a agost de 2023 consten 210 h 23 m treballades davant 221 h 15 m teoriques, més 55 h 58 m justificades;
- en conjunt, de gener a agost de 2023 consten 566 h 02 m treballades davant 592 h 30 m teoriques, més 113 h 25 m justificades;
- aquestes dades no acrediten jornada completa sostinguda ni una pressio empresarial illicita;
- el canvi de volum mes clar es concentra especialment al setembre de 2023, amb 170 h 21 m treballades davant 75 h teoriques, i s'ha de tractar com un periode concret, no com a prova que tota la mitja jornada anterior fos estructuralment insuficient;
- els mesos posteriors s'han de llegir separadament, perquè hi apareixen canvis de jornada, absencies, permisos i situacions vinculades al naixement/paternitat. En concret, octubre de 2023 mostra `Horari Cristina` amb moltes linies d'`Hores d'absencia`, i a partir del 16/11/2023 Woffu mostra el permis `Naixement i adopcio`;

Observacions objectives:

- El treball efectiu s'ha calculat com `Hores ordinàries + Extr. a compensar`.
- De gener a agost de 2023 consten 566 h 02 m treballades davant 592 h 30 m teoriques, i 113 h 25 m justificades separadament.
- Setembre de 2023 mostra 170 h 21 m treballades davant 75 h teoriques.
- Les columnes `Total d'hores`, `Diferencia` i `Extr. a compensar` es recullen com a dades administratives de Woffu i s'han de creuar amb la columna `Jornada`.

Cautela:

> No negar que hi hagi algun excés puntual o saldos administratius positius. El punt no es dir que no hi hagi cap hora per sobre de l'horari teoric, sino que el calcul real visible per entrada, sortida i descansos no prova jornada completa sostinguda, ni insuficiencia estructural, ni hores no compensades sense revisar compensacions, absencies, permisos i vacances.

### Febrer 2025

La captura `[WF-PRES-2025-02]` mostra una jornada teòrica de 7 h 36 min i diverses entrades/sortides i descansos molt variables durant el mes. Això és rellevant per contextualitzar que l'equip necessités saber quan Jordi estava disponible, especialment si hi havia tasques dependents o reunions.

Conclusió prudent:

> Els registres de febrer 2025 mostren una distribució horària irregular o dispersa. Aquesta dada no permet valorar la qualitat del treball, però sí ajuda a explicar per què es demanaven confirmacions d'horari o disponibilitat en un context de teletreball i tasques dependents.

### Setembre 2025

La captura `[WF-PRES-2025-09]` mostra dies marcats com a vacances, dies amb jornada ordinària i fitxatges amb entrades/sortides variables. És útil per creuar-ho amb els episodis de Fundae, articles pendents, reunions i preguntes sobre si Jordi treballava o tenia festa.

Cautela:

> La captura actual de Woffu mostra l'estat del registre, però no necessàriament quan es va sol·licitar o aprovar cada absència. Si es vol afirmar que una festa/vacança no estava comunicada a temps, cal afegir prova complementària: WhatsApp, correu, Trello o historial d'aprovació de Woffu.

### Juliol 2026

La captura `[WF-PRES-2026-07]` mostra la reincorporació/reorganització recent amb fitxatges, consultori mèdic, hores d'absència, defunció i permisos no retribuïts. És útil per acreditar que l'empresa diferenciava entre avisar pel grup i registrar administrativament a Woffu, i que les preguntes d'horari responien a necessitats de coordinació.

Cautela:

> No s'ha d'utilitzar per qüestionar motius mèdics o personals. Només serveix per acreditar canal administratiu, disponibilitat, fitxatge i organització del treball.

## Creuaments útils

### 1. Franja de disponibilitat 10-14 h

Objectiu:

- comprovar dies en què havia d'estar disponible de 10 a 14 h;
- identificar entrades tardanes, sortides abans d'hora o trams no comunicats;
- vincular-ho amb reunions, tasques o correus pendents.

Proves vinculades:

- `[WF-HORARI-01]`
- actes on consta l'acord de disponibilitat;
- correus o WhatsApps on se li pregunta si treballa o quan estarà connectat.

#### Recompte verificat de sortides dins la franja

L'acta del 04/02/2025 fixa per a Jordi la franja de disponibilitat de 10 a 14 h i estableix que, si dins d'aquest horari algú no es pot connectar o ha de sortir, ho ha d'avisar al grup de WhatsApp. La revisió de la columna `Fitxatges` de l'export `Presència diari Jordi - 2023-2026`, des del febrer de 2025 fins al 16/07/2026, dona el resultat següent:

- **54 dies** amb almenys una sortida registrada entre les 10:00 i les 14:00, en el recompte brut iniciat l'01/02/2025;
- **55 sortides** dins d'aquesta franja, perquè el 14/02/2025 n'hi consten dues;
- **17 dies** en què l'últim fitxatge del dia és una sortida entre les 10:00 i les 14:00 i no consta cap entrada posterior aquell mateix dia;
- si s'exclou el 03/02/2025, anterior a l'acord del 04/02/2025, queden **53 dies i 54 sortides**;
- si, a més, es compten només els dies posteriors a l'acord amb `Horari teòric` superior a zero, queden **36 dies amb 36 sortides**, dels quals **7** acaben definitivament dins la franja sense entrada posterior.

El total de 54 dies es distribueix en **50 dies entre febrer i desembre de 2025** i **4 dies després de la reincorporació, el juny i juliol de 2026**. Per tant, no s'ha de presentar tot el recompte com si correspongués exclusivament al període anterior a la baixa.

Dies amb alguna sortida dins la franja:

- febrer de 2025, 10 dies: 03/02 13:54; 04/02 13:29; 07/02 13:33; 08/02 11:38; 12/02 13:55; 14/02 10:31 i 12:54; 16/02 11:41; 18/02 12:36; 20/02 11:42; 25/02 12:25;
- març, 8 dies: 04/03 12:16; 05/03 11:06; 09/03 10:35; 14/03 13:34; 17/03 10:41; 18/03 13:28; 24/03 13:56; 31/03 11:56;
- abril, 3 dies: 11/04 12:24; 14/04 11:52; 15/04 13:57;
- maig, 6 dies: 02/05 11:04; 07/05 11:14; 12/05 13:02; 16/05 11:47; 19/05 13:59; 26/05 12:51;
- juny, 9 dies: 04/06 13:54; 10/06 11:15; 11/06 13:47; 12/06 13:01; 13/06 11:43; 14/06 13:37; 18/06 13:13; 20/06 11:37; 30/06 11:49;
- juliol, 2 dies: 14/07 13:58; 26/07 13:04;
- agost, 3 dies: 01/08 13:31; 04/08 13:34; 06/08 12:13;
- setembre, 5 dies: 04/09 11:43; 05/09 12:12; 16/09 12:58; 17/09 13:26; 18/09 12:57;
- octubre, 2 dies: 07/10 13:15; 12/10 12:38;
- desembre, 2 dies: 01/12 13:49; 03/12 12:49;
- juny de 2026, 1 dia: 29/06 12:16;
- juliol de 2026, 3 dies: 02/07 11:28; 07/07 12:30; 16/07 13:10.

Els 17 dies en què no consta cap entrada posterior són: 04/02/2025 13:29; 08/02/2025 11:38; 14/02/2025 12:54; 16/02/2025 11:41; 24/03/2025 13:56; 12/05/2025 13:02; 14/06/2025 13:37; 18/06/2025 13:13; 14/07/2025 13:58; 04/08/2025 13:34; 04/09/2025 11:43; 05/09/2025 12:12; 17/09/2025 13:26; 18/09/2025 12:57; 12/10/2025 12:38; 01/12/2025 13:49; i 03/12/2025 12:49.

**Cautela probatòria:** les 55 sortides brutes no equivalen automàticament a 55 absències injustificades. El 03/02 és anterior a l'acord i en 17 de les dates posteriors l'export mostra `Horari teòric = 0`, inclosos caps de setmana, vacances o altres dies sense jornada teòrica; aquests casos no s'han de presentar com a vulneració de la franja obligatòria sense una anàlisi addicional. En 37 dels 54 dies consta una entrada posterior i les interrupcions poden ser pauses, gestions o incidències. Fins i tot en els 7 dies amb jornada teòrica en què la sortida és definitiva dins la franja cal comprovar, abans de qualificar cap incompliment, si existia avís al grup, permís, justificació, canvi acordat o compensació. El que l'export acredita directament és que hi havia interrupcions de disponibilitat i, per això, una necessitat objectiva de comunicar les sortides i coordinar les tasques dependents.

L'export actual de Woffu marca com a `Vacances` 40 dies de 2025: 4, 7 i 14 de febrer; 26, 27 i 31 de març; 2, 8, 9, 14, 15, 16, 17 i 30 d'abril; 16 de juliol; 5, 6, de l'11 al 14, del 18 al 22 i del 25 al 29 d'agost; i 1, 2, 4, 5, 12, 17, 18, 19 i 26 de setembre.

D'aquests 40 dies de vacances, **11 coincideixen** amb el recompte brut de dies amb sortides entre les 10 i les 14 h: 04/02, 07/02, 14/02, 31/03, 14/04, 15/04, 06/08, 04/09, 05/09, 17/09 i 18/09. Representen **12 sortides**, perquè el 14/02 n'hi ha dues. Sis d'aquests dies —04/02, 14/02, 04/09, 05/09, 17/09 i 18/09— també apareixen entre els 17 dies sense cap entrada posterior.

Segons Meriem, aquests dies es van agafar o registrar com a vacances posteriorment. L'export acredita que actualment consten com a `Vacances`, però no mostra per si sol quan es van sol·licitar, aprovar o regularitzar; per acreditar que la qualificació va ser posterior cal l'historial de Woffu, comunicacions o testimonis. En qualsevol cas, la seva consideració final com a vacances impedeix presentar-los com a temps injustificat, però no resol la qüestió organitzativa si no es va informar l'equip en el moment de marxar. El problema que s'ha de contrastar no és només la sortida, sinó si Jordi avisava que marxava, si indicava si tornaria o si tindria vacances, i si la resta podia saber si havia d'esperar-lo, continuar sense ell o reprogramar les tasques dependents.

Fonts:

- Acta de la reunió del 04/02/2025 (`_extraccio_actes_2025/2025-02-04.docx.txt`).
- `Presència diari Jordi - 2023-2026.pdf`, columna `Fitxatges`.
- `Presència diari Jordi - 2023-2026.xlsx`, columna `Fitxatges`, emprat per verificar les hores que al PDF apareixen partides entre línies.

### 2. Vacances i hores compensades

Objectiu:

- contestar afirmacions sobre manca de descans, vacances acumulades o jornades inassumibles;
- veure períodes en què efectivament va gaudir de vacances, permisos o compensacions;
- separar vacances reals, permisos de paternitat, baixes i dies regalats/no descomptats, si consta.

Proves vinculades:

- `[WF-VACANCES-01]`
- `[WF-PATERNITAT-2024-01]`
- actes i correus sobre vacances o reprogramacions.

### 3. Tasques pendents amb dies fitxats

Objectiu:

- en casos com Fundae, GUST, ALBUM, articles o xarxes, comprovar si hi havia dies de treball disponibles abans del venciment;
- evitar dir només "no ho va fer"; mostrar que hi havia període de treball i recordatoris previs.

Casos prioritaris:

- Fundae setembre 2025;
- GUST abril-maig 2025;
- ALBUM octubre 2025;
- articles Educat;
- publicacions/xarxes amb correccions fora de termini;
- reincorporació 2026 i horaris comunicats.

### 4. Dies amb fitxatge i manca de comunicació

Objectiu:

- acreditar la necessitat de preguntar per disponibilitat;
- contextualitzar per què Meriem/Isa/Pablo demanaven confirmacions;
- contestar que les preguntes sobre horari fossin control hostil.

Proves vinculades:

- Woffu del dia concret;
- Google Chat/WhatsApp/correu preguntant disponibilitat;
- acta on consti obligació d'avisar.

## Plantilla de fitxa per cada episodi

```text
Episodi: [nom]

Període revisat:
[data inicial] - [data final]

Afirmació de Jordi que es contesta:
"..."

Què mostra Woffu:
- [data]: [hores/entrada/sortida/tipus de dia]
- [data]: [hores/entrada/sortida/tipus de dia]

Context:
[tasca pendent, termini, reunió, correu, Trello, acta]

Conclusió prudent:
Els registres de Woffu mostren [fet objectiu]. Això contextualitza la necessitat de coordinació/recordatoris i no permet presentar les peticions d'horari com una actuació hostil sense considerar el funcionament real de la jornada i les dependències de feina.

Proves:
- [WF-...]
- [ACT-...]
- [GM/WA/GC/TR/GS-...]
- [CAP-...]

Cautela:
[què no es pot afirmar només amb Woffu]
```

## Redacció tipus per la resposta de l'empresa

```text
Les preguntes sobre horari o disponibilitat no eren un control personal ni una actuació hostil, sinó una necessitat organitzativa derivada del teletreball i de les dependències entre tasques. Els registres de Woffu s'han de posar en relació amb les actes i comunicacions on es recordava la franja de disponibilitat, l'obligació d'avisar canvis d'horari i les tasques pendents que depenien de Jordi.
```

```text
Pel que fa a l'afirmació sobre un volum de tasques inassumible o manca de descans, cal contrastar-la amb els registres de jornada, vacances, hores compensades, permisos i baixes. L'existència de malestar subjectiu no substitueix l'anàlisi dels períodes efectivament treballats, descansats o compensats.
```

## Pendents si es rep l'export tabular

- identificar format del fitxer: Excel, CSV, PDF o captures;
- crear una taula neta de registres;
- detectar períodes clau;
- creuar amb actes i tasques;
- generar codis `[WF-...]` per cada prova útil;
- exportar captures només dels dies/períodes rellevants.
