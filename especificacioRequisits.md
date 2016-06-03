# SISTEMA BCNPròxima - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE #

## 1. ESPECIFICACIÓ FUNCIONAL ##

### 1.1. Diagrama de casos d'ús

![](http://i.imgur.com/iBWuPPG.png)

● Cas d'ús UC001 – Afegir botiga

● Cas d'ús UC002 – Eliminar botiga

● Cas d'ús UC003 – Modificar botiga

● Cas d'ús UC004 – Consultar botiga

● Cas d'ús UC005 – Valorar botiga

● Cas d'ús UC006 – Consultar rutes i mitjans de transport

● Cas d'ús UC007 – Consultar llista de botigues

● Cas d'ús UC008 – Buscar botiga

● Cas d'ús UC009 – Ordenar llista de botigues

● Cas d'ús UC010 – Filtrar llista de botigues

● Cas d'ús UC011 – Afegir promoció

● Cas d'ús UC012 – Eliminar promoció

● Cas d'ús UC013 – Modificar promoció

● Cas d'ús UC014 – Consultar promoció

● Cas d'ús UC015 – Consultar llista de promocions

● Cas d'ús UC016 – Ordenar llista de promocions

● Cas d'ús UC017 – Filtrar llista de promocions

● Cas d'ús UC018 – Registrar usuari

● Cas d'ús UC019 – Eliminar usuari

● Cas d'ús UC020 – Modificar usuari

● Cas d'ús UC021 – Consultar usuari

● Cas d'ús UC022 – Iniciar sessió


### 1.2. Descripció individual dels casos d'ús

### Cas d'ús UC001 – Afegir botiga

L’administrador introdueix la informació de la botiga (nom, imatge representativa, tipus de comerç, direcció, horari, telèfon, email, una breu descripció i els productes que ofereix amb els seus corresponents preus) i el sistema registra les dades.

### Cas d'ús UC002 – Eliminar botiga

L’administrador indica al sistema que vol donar de baixa la botiga en qüestió i el sistema, després de demanar i rebre una confirmació per part de l’administrador, elimina la botiga de la base de dades.

### Cas d'ús UC003 – Modificar botiga

L’administrador pot modificar la informació relativa a qualsevol botiga que hagi estat creada prèviament al sistema.

### Cas d'ús UC004 – Consultar botiga

L’usuari pot consultar la informació de les botigues que li apareixen a la llista de botigues. Aquesta informació constarà de les dades introduïdes per l’administrador a l’hora d’afegir la botiga al sistema, de la valoració mitjana d’aquesta segons els usuaris, de les rutes i mitjans de transport  per arribar-hi i de les promocions que ofereixi durant un període de temps determinat.

### Cas d'ús UC005 – Valorar botiga

L’usuari té la possibilitat de fer conèixer la seva opinió sobre una botiga a altres usuaris i al propi comerç mitjançant una valoració numèrica entre 1 i 5, la qual es representa gràficament amb estrelles més o menys il·luminades, segons la puntuació de l’usuari.

### Cas d'ús UC006 – Consultar rutes i mitjans de transport 

L’usuari indica al sistema que vol veure quines són les rutes i els mitjans de transport més adients per arribar a la botiga des del lloc on es troba i el sistema es comunica amb la API de Google Maps.

### Cas d'ús UC007 – Consultar llista de botigues

L’usuari pot visualitzar el conjunt de botigues en forma de llistat, on només es mostra el nom i una imatge representativa de la botiga.

### Cas d'ús UC008 – Buscar botiga

L’usuari ha d’introduir el nom de la botiga en qüestió o algun tret característic d’aquesta, com ara bé un producte que ofereixi o el sector comercial al qual pertanyi. El sistema mostrarà la botiga o les botigues que coincideixin amb els paràmetres de cerca proporcionats per l’usuari.

### Cas d'ús UC009 – Ordenar llista de botigues

L’usuari té la possibilitat d’ordenar el llistat de botigues per ordre alfabètic, per tipus de comerç, per valoració del propi usuari, per valoració de la resta d’usuaris o bé per proximitat a l’usuari tenint en compte la seva localització.

### Cas d'ús UC010 – Filtrar llista de botigues

L’usuari pot filtrar el llistat de botigues per tipus de comerç (seleccionant quins l’interessen i quins no), per proximitat (indicant la distància màxima que està disposat a recórrer partint del lloc en el qual es troba) o bé per producte (triant aquells que vulgui i que seran oferts per les botigues que se’ns mostraran).

### Cas d'ús UC011 – Afegir promoció

L’administrador pot afegir una promoció i associar-la amb una de les botigues que s’han donat d’alta prèviament al sistema. La informació que caldrà introduir serà, a més a més de la botiga, un nom, una breu descripció, el dia d’inici i el dia d’acabament i els productes en oferta amb els seus corresponents preus antics i preus un cop aplicat el descompte.

### Cas d'ús UC012 – Eliminar promoció

L’administrador indica al sistema que vol eliminar la promoció en qüestió i el sistema, després de demanar i rebre una confirmació per part de l’administrador, l’esborra de la base de dades.

### Cas d'ús UC013 – Modificar promoció

L’administrador pot modificar la informació relativa a qualsevol promoció que hagi estat creada prèviament al sistema. 

### Cas d'ús UC014 – Consultar promoció

L’usuari pot consultar la informació de les promocions que li apareixen a la llista de promocions. Aquesta informació serà el nom de la promoció, una breu descripció d’aquesta, el nom de la botiga que la ofereix, quin dia comença i quin dia acaba i els productes en oferta amb els seus corresponents preus antics i preus un cop aplicat el descompte.

### Cas d'ús UC015 – Consultar llista de promocions

L’usuari pot visualitzar el conjunt de promocions en forma de llistat, on només es mostra el nom i una imatge representativa de la promoció.

### Cas d'ús UC016 – Ordenar llista de promocions

L’usuari té la possibilitat d’ordenar el llistat de promocions per ordre d’inici, per ordre d’acabament, per tipus de comerç, per botiga o bé per producte.

### Cas d'ús UC017 – Filtrar llista de promocions

L’usuari pot filtrar el llistat de promocions per dia d’inici i d’acabament (indicant que vol veure només les que tinguin validesa entre el dia X i el dia Y), per tipus de comerç (seleccionant quins l’interessen i quins no), per botiga (escollint les botigues de les quals vol saber-ne les promocions vigents) o bé per producte (triant aquells que vulgui i que estaran relacionats amb les promocions que se’ns mostraran).

### Cas d'ús UC018 – Registrar usuari

Per tal de registrar un nou usuari al sistema, cal introduir un email vàlid i una contrasenya.

### Cas d'ús UC019 – Eliminar usuari

L’usuari indica al sistema que vol donar-se de baixa i el sistema, després de demanar i rebre una confirmació per part de l’usuari, elimina la seva informació de la base de dades.

### Cas d'ús UC020 – Modificar usuari

L’usuari pot modificar la seva contrasenya sempre que ho desitgi.

### Cas d'ús UC021 – Consultar usuari

L’usuari pot consultar l’email que va introduir a l’hora de registrar-se i la seva contrasenya actual.

### Cas d'ús UC022 – Iniciar sessió

Un usuari que prèviament s’ha registrat al sistema pot iniciar sessió i començar a utilitzar l’aplicació, tot indicant l’email que va introduir a l’hora de registrar-se i la seva contrasenya actual.


### 1.3. Mockups

![](http://i.imgur.com/2v9xcm5.jpg)

## 2. ESPECIFICACIÓ NO FUNCIONAL ##

## Requisit 1: Facilitat d'ús ##

### Descripció:

Els usuaris no requeriran de cap tipus de preparació per aprendre a utilitzar l'aplicació.

### Justificació del requisit:

El nostre sistema ha de ser fàcil d’aprendre a utilitzar per evitar la pèrdua d’interès en la nostra aplicació per part dels usuaris.

### Condició de satisfacció:

El 90% dels usuaris sense experiència que han provat l’aplicació, han sabut completar les tasques que els hi hem proposat en 10 minuts.

## Requisit 2: Eficiència ##

### Descripció:

Amb menys de cinc clics l'usuari podrà accedir a qualsevol funcionalitat.

### Justificació del requisit:

Accedir a les funcionalitats de la nostra aplicació no ha de ser farragós per l'usuari.

### Condició de satisfacció:

Qualsevol funcionalitat de la nostra aplicació ha estat accesible entre 2 i 3 clics pel 80% dels usuaris.

## Requisit 3: Accés a les dades ##

### Descripció:

La introducció de noves botigues i promocions al sistema serà realitzada per personal autoritzat.

### Justificació del requisit:

Els petits comerços han de tenir la seguretat que l'informació que ens proporcionen és la que es mostrarà a l'aplicació.

### Condició de satisfacció:

El sistema identificarà a l’administrador quan aquest introdueixi el seu email i la seva contrasenya i llavors tindrà accés a les dades i podrà modificar-les si vol.

## Requisit 4: Atractiu pel públic ##

### Descripció:

El sistema disposarà d'una interfície atractiva i s'adaptarà al tema del dispositiu.

### Justificació del requisit:

L’aparença del nostre sistema haurà de ser atractiva perquè el nostre públic objectiu utilitzi el sistema. És important ja que l’aparença és la part del nostre sistema que interacciona amb l’usuari.

### Condició de satisfacció:

El 85% dels usuaris entrevistats asseguren que en la primera presa de contacte amb la interfície del sistema ha estat agradable i satisfactòria.

## Requisit 5: Personalitzable ##

### Descripció:

El sistema permetrà escollir l'idioma, preferencies d'ofertes i configuració de notificacions.

### Justificació del requisit:

Volem que el nostre sistema sigui entès per qualsevol usuari i que es pugui configurar com ells vulguin.

### Condició de satisfacció:

El sistema estarà disponible en català, castellà, anglès i les funcionalitats seran personalitzables.

## Requisit 6: Disponibilitat ##

### Descripció:

El sistema estarà disponible les 24 hores del dia els 365 dies de l’any.

### Justificació del requisit:

És necessari perquè l’usuari pugui consultar les ofertes del seu entorn en qualsevol moment.

### Condició de satisfacció:

A les proves realitzades, el 99,99% del temps el sistema ha estat disponible i funcionant correctament.

## Requisit 7: Extensibilitat ##

### Descripció:

El sistema estarà preparat per incorporar noves funcionalitats.

### Justificació del requisit:

El nostre sistema ha de ser extensible, ja que s'anirà actualitzant amb més funcionalitats.

### Condició de satisfacció:

El sistema s'implementarà de tal forma que al afegir noves funcionalitats no afectarà a l'implementació actual.

## Requisit 8: Adaptabilitat ##

### Descripció:

El sistema estarà disponible en Android, iOS i Windows Phone.

### Justificació del requisit:

És necessari per abastar el màxim nombre d'usuaris possibles.

### Condició de satisfacció:

S'implementarà diferents versions del sistema que puguin funcionar en Android, iOS i Windows Phone.

## 3. RECURSOS ##

[1] http://www11.informatik.uni-erlangen.de/Lehre/SS2015/PR-SWE/Material/volere-template.pdf
