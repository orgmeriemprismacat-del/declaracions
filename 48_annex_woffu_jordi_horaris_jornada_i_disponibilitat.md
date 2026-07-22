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
