# SISTEMA BCNPròxima - VISIÓ #


## 1. INTRODUCCIÓ ##

Vivim en una societat en la qual els smartphone han guanyat molt protagonisme. Tant que, segons un estudi de la Nottingham Trent University [1], consultem aquest dispositiu 85 vegades al dia. Les grans superfícies se n’aprofiten d’aquest fet per augmentar el seu nombre de clients i es promocionen a través d’Internet, ja sigui mitjançant publicitat o bé disposant d'una pàgina web o aplicació des de la qual vendre el seus productes.

El petit comerç, en canvi, habitualment no disposa del personal o dels coneixements necessaris per poder crear i administrar una pàgina web o una aplicació amb la qual tenir certa presència a la xarxa. És per això que hem creat l’aplicació BCNPròxima.

El nostre sistema pretén incentivar al ciutadà barceloní a canviar els seus hàbits de compra i apropar-lo al comerç de proximitat, donant a conèixer els establiments de la zona i permetent a un possible client mantenir-se informat respecte a novetats en aquestes botigues. Aquestes funcionalitats les podrà gaudir de manera gratuïta des del seu smartphone gràcies a la nostra app.

## 2. EL PROBLEMA ##

Segons l’Indicador de Comerç de Barcelona, la facturació i el nombre de vendes del petit comerç de la ciutat van caure un 0.2% i un 0.7% el 2015, respectivament [2]. La crisi econòmica, l’entrada en vigor a finals del 2014 de la Llei d’arrendaments urbans i el monopoli de les grans superfícies són els factors principals que ens porten a aquesta situació [3].

Tenint en compte que el petit comerç segueix sent la principal font d’ocupació en l’àmbit de la distribució comercial del sector quotidià amb un 55% de llocs de treball generats i que, malgrat tot, aquest percentatge ha anat creixent els darrers anys, el fet d’incentivar el comerç de proximitat repercutiria positivament en l’economia catalana [4].

L’Indicador de Comerç de Barcelona també adverteix que el fet de treballar més hores i obrir els diumenges i dies festius no es correspon amb un increment en el nombre de vendes [2]. D’altra banda, les promocions i el període de rebaixes funcionen prou bé, però resulten insuficients perquè el 64% dels comerciants afirma que ells assumeixen el 100% del cost dels descomptes que fan dels seus productes [2].

Sembla lògic, doncs, que molts petits comerços comencin a creure que la solució passa per promocionar-se  a través d’Internet, de les xarxes socials i d’aplicacions com la nostra (ja que no generen suficients ingressos com per anunciar-se per televisió o pels carrers de la ciutat) amb l’objectiu de fidelitzar el màxim nombre de clients possibles mitjançant el tracte personal, la qualitat del producte, informació que podem obtenir a l’instant sobre aquest, adquisició de punts bescanviables per descomptes o bé per participar en sorteigs de premis, etc.

## 3. PARTS INTERESSADES ##

- *Inversors*. Poden arribar a ser una font de finançament clau per a que el projecte pugui tirar endavant. L’interès en invertir en el nostre sistema dependrà del rèdit econòmic que puguin obtenir en relació al capital invertit.
- *Treballadors del petit comerç*. El fet de promocionar els seus establiments a través de l’aplicació que desenvoluparem podria ser la solució que busquen per fer front al problema de la caiguda de vendes dels darrers anys.
- *Ciutadans*. Els barcelonins i barcelonines que estiguin interessats o interessades en la nostra aplicació seran aquells o aquelles que vulguin trobar informació dels petits comerços més propers a la seva localització.
- *Les grans superfícies*. Els eterns competidors del petit comerç es veurien afectats negativament en cas que la nostra aplicació tingués èxit. Tenint en compte això i el fet que, quants més petits comerços es mostrin satisfets amb el servei que els oferim, més demanda de promoció d’altres establiments tindrem, podem concloure que les grans superfícies també seran la nostra competència, encara que sigui indirectament.
- *Empreses i desenvolupadors d’aplicacions similars a la nostra*. Seran la nostra competència directa. Haurem d’estudiar-la per saber quins són els nostres punts febles i punts forts, per definir quines estratègies de mercat són les més adequades, etc.
- *Desenvolupadors*. Sobre nosaltres recaurà la responsabilitat de tot allò que tingui a veure amb la funcionalitat de l’aplicació i amb el compliment dels requisits de qualitat. Més enllà del possible benefici econòmic, la satisfacció personal que el nostre sistema software sigui útil per a la ciutadania i també l’experiència obtinguda per a futurs projectes són motius més que suficients per tenir interès en desenvolupar l’aplicació.
- *Equip de manteniment*. S’encarregarà de vetllar pel correcte funcionament dels servidors i la base de dades.

## 4. EL PRODUCTE ##

### 4.1. Perspectiva del producte ###

El nostre sistema està dissenyat per ser una aplicació per a dispositius mòbils intel·ligents amb sistema operatiu Android, iOS o Windows Phone.

L’aplicació requerirà, d’una banda, de connexió a Internet per poder accedir als servidors i aquests a la base de dades amb la finalitat d’obtenir informació de les botigues i de les promocions, i d’altra banda, de localització via GPS per tal d’ubicar al smartphone i al nostre usuari, el qual podrà veure quines botigues té més a prop i com arribar a cadascuna d’elles.

![](http://i.imgur.com/ntcOurI.jpg)

### 4.2. Descripció del producte ###

- *Afegir, modificar i/o eliminar botigues*. Comptarem en el nostre equip de treball amb una persona, a la qual denominarem administrador, que s’encarregarà d’introduir, editar i esborrar la informació relacionada amb els establiments que hagin contractat els nostres serveis.
- *Afegir, modificar i/o eliminar promocions*. L’administrador serà l’encarregat d’introduir, editar i esborrar la informació relacionada amb les promocions dels establiments que hagin contractat els nostres serveis.
- *Consultar la informació de les botigues*. Podrem saber quins dies obre i a quines hores, les vies de contacte, la direcció on es troba, quins productes ofereix i a quins preus, quina valoració li atorga la resta d’usuaris, etc.
- *Consultar rutes i mitjans de transport per arribar a les botigues*. L’API de Google Maps ens permetrà ubicar la nostra localització i la de la botiga en un mapa i ens dirà com i quant temps trigaríem en arribar fins a aquesta.
- *Valorar les botigues*. També podrem compartir la nostra opinió sobre una botiga qualsevol amb la resta d’usuaris mitjançant una valoració numèrica entre 1 i 5, la qual es representarà gràficament amb estrelles més o menys il·luminades, segons la nostra puntuació.
- *Consultar les promocions*. Tindrem la possibilitat de veure quins productes estan en oferta (amb els seus corresponents preus antics i preus un cop aplicat el descompte) en una botiga determinada o en el conjunt de botigues que promocionem en la nostra aplicació.
 
### 4.3. Supòsits de funcionament ###

- *Disposar d'un smartphone amb la localització activada*. L’usuari haurà de permetre a la nostra aplicació conèixer la seva ubicació per tal de poder veure quines botigues té més a prop i quines són les rutes i els mitjans de transport més adients per arribar-hi.
- *Disposar de connexió a Internet*. Si volem rebre en tot moment una informació el més actualitzada possible de les botigues o de les promocions, la nostra aplicació ha de poder establir una connexió via Internet amb els nostres servidors i aquests amb la base de dades.
- *Integritat de les dades*. La informació de les botigues i de les promocions que introduirà l’administrador a la base de dades serà íntegre, és a dir, les dades seran certes i completes.
 
### 4.4. Dependències sobre altres sistemes ###

- *GPS*. El sistema dependrà de la senyal GPS per poder obtenir la localització del usuari en temps real.
- *Google Maps*. El sistema requerirà de Google Maps per poder situar a l'usuari en un mapa, localitzar i mostrar les botigues properes i calcular el recorregut per arribar a elles.
- *Base de dades*. El sistema emmagatzemarà tota la informació dels establiments, dels usuaris i de les promocions en una base de dades, la qual condicionarà la disponibilitat del servei i la seva rapidesa.
- *Sistema Operatiu del dispositiu*. El sistema dependrà d'Android, iOS i Windows Phone per poder oferir totes les seves funcionalitats als usuaris i poder seguir afegint-ne de noves.
  
### 4.5. Altres requisits ###

- *Facilitat d'ús*. Els usuaris no requeriran de cap tipus de preparació per aprendre a utilitzar l'aplicació.
- *Eficiència*. Amb menys de cinc clics l'usuari podrà accedir a qualsevol funcionalitat.
- *Accés a les dades*. La introducció de noves botigues i promocions al sistema serà realitzada per personal autoritzat.
- *Atractiu per al públic*. El sistema disposarà d'una interfície atractiva i s'adaptarà al tema del dispositiu.
- *Personalitzable*. El sistema permetrà escollir l'idioma, preferències d'ofertes i configuració de notificacions.
- *Disponibilitat*. El sistema estarà disponible les 24 hores del dia els 365 dies de l’any.
- *Extensibilitat*. El sistema estarà preparat per incorporar noves funcionalitats.
- *Adaptabilitat*. El sistema estarà disponible en Android, iOS i Windows Phone.

## 5. RECURSOS ##

[1] http://www.ntu.ac.uk/apps/news/180892-15/People_check_their_smartphones_85_times_a_day_(and_they_dont_even_know_the.aspx

[2] http://comerc.bcn.cat/sites/default/files/arxius/icob_t4_2015_def-_v4_0.pdf

[3] http://www.eldiario.es/catalunyaplural/tradicional-centre-Barcelona-abaixa-persiana_0_198781031.html

[4] http://premsa.gencat.cat/pres_fsvp/AppJava/notapremsavw/286809/ca/petit-comerc-proximitat-segueix-sent-major-font-docupacio-grans-formats-distribucio.do