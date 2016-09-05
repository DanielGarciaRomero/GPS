# SISTEMA BCNPròxima - PLA DE DESENVOLUPAMENT DE SOFTWARE #

## 1. ORGANITZACIÓ I EQUIP ##

- Cap de projecte (1 Persona): Ha de planificar i programar el projecte, descompondre-ho en tasques i assignar-les als membres de l'equip. Ha de supervisar, liderar i coordinar l'equip, veure que tots els membres de l'equip estan realitzant les tasques que se'ls ha encarregat.
- Programador Sènior (4 Persones): Són els encarregats de fer la gran majoria del codi, excepte algunes parts que les hi encarreguen als juniors, per tal de que l’aplicació compleixi els requisits establerts.
- Programador Junior (2 Persones): Són el programadors amb menys experiència. S’encarreguen de fer les tasques encarregades pels sèniors i així guanyar coneixements i experiència.
- Dissenyador gràfic (1 Persona): És el responsable de dissenyar tota la interfície gràfica d'usuari i de distribuir les funcionalitats en l'aplicació. Participarà en la campanya de màrqueting.
- Enginyer de requisits (1 Persona): És el responsable d’establir el requisits que haurà de complir l’aplicació per tal de satisfer els objectius establerts pel client.
- Arquitecte del software (1 Persona): És l’encarregat d’analitzar els requisits que influeixen en l’arquitectura i fer-ne un disseny arquitectònic.
- Tester (1 Persona): És el responsable de duu a terme proves preestablertes a l’aplicació abans del seu llançament al mercat per tal de garantir la qualitat, la integritat del disseny i el funcionament correcte d’aquesta.

## 2. PLA DE PROJECTE ##

### 2.1. Estimació d'esforç ###

### UAW

![](http://i.imgur.com/hLh8s5T.jpg)

Els actors que interactuen amb el nostre sistema són, d’una banda, els usuaris i l’administrador, i d’altra banda, Google Maps i els servidors que accedeixen a la base de dades.

### UUCW

![](http://i.imgur.com/imW8hWR.jpg)

Considerem que els casos d’ús que interaccionen amb els servidors o amb Google Maps tenen entre tres i set esdeveniments externs i, per tant, la seva complexitat és mitjana. Pel que fa a la resta, entenem que són simples, ja que tenen com a precondició haver cridat prèviament a un cas d’ús de complexitat mitjana que demani la informació que necessiten als servidors.

### TCF

![](http://i.imgur.com/A9rpkIC.jpg)

Hem assignat una determinada prioritat a cadascuna de les complexitats tècniques de la taula anterior en funció dels requisits no funcionals que pretenem que tingui la nostra aplicació.

### ECF

![](http://i.imgur.com/tUBfwMj.jpg)

El factor d’entorn que creiem que pot influir més negativament en el projecte és la poca familiaritat que tenim amb UP. Quant a la dificultat dels llenguatges de programació o al fet de treballar a temps parcial, suposem que no afectarà gaire perquè altres factors com ara bé l’experiència en l’orientació a objectes o la motivació de l’equip de treball tindran una influència molt positiva.

### UCP i estimació del temps

![](http://i.imgur.com/vSBWBgM.jpg)

A partir del càlcul del UCP i d’un factor PF al qual li hem assignat un valor de 20 perquè no tenim experiència en projectes similars i anteriors a aquest, podem estimar que el nostre projecte ens suposarà un total de 3426 hores de dedicació.

### 2.2. Estimació de cost ###

L'estimació del cost ve donat per diversos factors com per exemple, les hores que es dediquen, el preu per hora que es paga a cada treballador entre altres coses...

![](http://i.imgur.com/DDWk0g4.jpg)

Primer de tot, dividim les hores que estimem que dura el projecte en les quatre fases que té el projecte (Inception, Elaboration, Construction, Transition). Seguidament, repartim les hores de cada fase entre els treballadors.

Les dedicacions previstes per als rols cap de projecte, arquitecte de software i tester les hem assignat basant-nos en les transparències de classe. Pels altres rols, hem distribuït les hores de la forma que hem vist més convenient, ja que no tenim experiència en projectes com aquests.

![](http://i.imgur.com/boRpEmp.jpg)

Haurem de calcular les hores que treballarà cada persona les quals s'obtindran a partir de l'esforç de cada rol i les hores totals del projecte.
Un cop fet això, s'ha de decidir el salari que cobrarà cada treballador que s'haurà calculat amb els preus per hora de cada rol, els quals els hem buscat per internet, i amb les hores que dedicarà cada rol al projecte.

![](http://i.imgur.com/ea5VFDJ.jpg)

A aquest salari, se li sumarà la seguretat social (40%) i els euros fixes que seran 200 euros. Seguidament, se suma un 15% de despeses estructurals sobre el salari calculat anteriorment i com a resultat ens donarà el salari brut de cada persona.

Per últim, veiem que tenim un cost de 97.143,00, sobre aquest haurem de valorar el marge de benefici que volem obtenir (50%) i el percentatge de contingències (10%), això ens dóna un pressupost final de 155.428,80 euros.

## 4. PLA DE FASES ##

La taula amb l'estat dels casos d'ús a cada fase quedaria de la següent manera:
 
![](http://i.imgur.com/XpYp5j8.jpg)

Recordem la taula on hem assignat els percentatges de treball entre les quatre fases dividits entre els treballadors.

![](http://i.imgur.com/DDWk0g4.jpg)

Un cop sabem aquests percentatges i prèviament hem calculat el número d'hores de dedicació que ens suposarà el nostre projecte, 3426,08 hores, podem definir per cada fase el número d'hores que tindrà cada càrrec.

![](http://i.imgur.com/WHYpnRG.jpg)

Donat que hi ha certs càrrecs que estan formats per més d'una persona, hem de dividir les hores de dedicació de cada càrrec entre el nombre d'integrants, per poder definir de manera correcta les dates límits de cada fase.

![](http://i.imgur.com/9Px7o1a.jpg)

Un cop ja tenim les hores per persona i fase, ja podem calcular les dates límits de cada fase. Partint de la data d'inici del projecte del 15 de Febrer i tenint en compte una jornada laboral de 40 hores setmanals, amb els caps de setmana de festa i els dies festius tant de Catalunya com d'Espanya, podem establir les següents dates:

![](http://i.imgur.com/qrVdgAI.jpg)

Ara només queda establir els objectius principals que s'assoliran i el nombre d'iteracions que tindrem per fase, i sabent les dates límits i el nombre d'hores de dedicació de cada fase, obtenim la següent taula:

![](http://i.imgur.com/MTe8ATK.jpg)

## 5. RECURSOS ##

[1] http://www.mediavida.com/foro/dev/cuanto-cobra-hora-programacion-431601

[2] http://www.forosdelweb.com/f6/cuanto-cuesta-valor-hora-disenador-grafico-660347/

[3] http://testeandosoftware.com/informe-de-la-encuesta-2013-sobre-los-sueldos-de-los-testers-en-espana-por-nexo-qa/

[4] http://espana.jobtonic.es/salary/26526/16132.html#chart-avgSalaryByYear

[5] http://www.cursodireccionproyectos.com/2014/01/informe-global-sobre-salarios-de-directores-de-proyectos/
