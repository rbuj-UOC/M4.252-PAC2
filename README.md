# PAC2

La PAC consta d'un exercici pràctic on haureu de realitzar un petit lloc web dedicat a concerts, format
per quatre pàgines que estaran vinculades mitjançant un menú de navegació.

El lloc web tindrà 4 arxius HTML ("index.html", "info.html", "calendari.html" i "tickets.html"), un únic arxiu CSS ("estils.css") situat en una carpeta anomenada "css", i una carpeta ("img") amb els arxius d'imatge necessaris.

Cada pàgina del lloc haurà de tenir un títol únic, que descrigui adientment el seu contingut.

Per crear els documents, utilitzeu les millors tècniques de marcat detallades en el material docent de l'assignatura. Això inclou l'ús correcte de marques per a textos, llistes, enllaços, imatges, contenidors genèrics i estructurals ( span , div , main , nav...). També haureu d'utilitzar els selectors CSS
pertinents.

La base del projecte ha de ser el tipus de document HTML5.

Dins de l'arxiu comprimit MaterialsPAC2.zip trobareu:
- Per copiar i enganxar els textos fàcilment, us proporcionem "TextosCopiaEnganxa.rtf"
- Els colors i tipus de lletra es detallen a l'última pàgina de "TextosCopiaEnganxa.rtf"
- Els arxius d'imatge "01-index.png", "02-info.png", "03-calendari.png", i "04-tickets.png" mostren com ha de ser el disseny final de cada pàgina.
- Les imatges per a la composició de les pàgines es troben dins de la carpeta "img"
- A la carpeta "img" hi ha l'arxiu "favicon-32x32.png" per a la icona de la pestanya del navegador .

Aquesta pràctica consta de 4 activitats:

## Activitat 1

Nom de l'arxiu: "index.html"

L'espai ocupat pel contingut no ha d'excedir el 100% del viewport, per la qual cosa en cap cas han de mostrar-se barres de desplaçament (ni vertical, ni horitzontal).

L'espai ha de repartir-se entre el menú de navegació, el logotip amb el lema principal i el peu de pàgina. La imatge de fons ("home-hero.jpg") ha d'ocupar tot l'espai disponible.

L'aspecte resultant ha de semblar-se al model ("01-index.png").

## Activitat 2

Nom de l'arxiu: "info.html"

Haureu de reproduir amb la màxima fidelitat possible el document que veieu a "02-info.png".

Dins de l'arxiu "TextosCopiaEnganxa.rtf" està l'enllaç al vídeo de YouTube que heu d'inserir .

En l'apartat de l'article que porta com a títol "Caps de cartell" heu d'utilitzar una llista de descripció.

## Activitat 3

Nom de l'arxiu: "calendari.html"

Haureu de reproduir amb la màxima fidelitat possible el document que veieu a "03-calendari.png".

Aquest arxiu conté una taula que heu de preparar perquè sigui com més accessible millor.

## Activitat 4

Nom de l'arxiu: "tickets.html"

Haureu de reproduir amb la màxima fidelitat possible el document que veieu a "04-tickets.png".

Els camps d'aquest formulari han d'estar organitzats formant els següents grups ben diferenciats: "informació personal", "tipus d'entrada", "mètode de pagament", "informació de targeta" i "adreça de tramesa". Els camps de cada grup es detallen en l'arxiu "TextosCopiaEnganxa.rtf".

En cada cas s'indica quins són els camps que l'usuari ha d'omplir de manera obligatòria.

Heu de decidir quin tipus de control de formulari és el que resulta més adient per a la recollida de les dades i la seva validació.

En els camps que han de permetre recollir el nom i els cognoms, a més de ser obligatoris, haureu d'aconseguir que l'usuari no pugui escriure caràcters diferents a lletres, apòstrofs o guions, que són els que normalment poden incloure's en un nom; així mateix, no haurien de contenir menys de 3 caràcters; en el cas del nom, el nombre de caràcters màxim permès ha de ser de 64 i, en el cas dels cognoms, no més de 128 caràcters (per a realitzar aquesta validació haureu d'utilitzar l'atribut "pattern" amb alguna expressió regular , feu una cerca per Internet que us ajudarà a trobar la solució a
aquest punt de l'exercici).

Valideu que el camp per al número de la targeta de crèdit tingui 16 dígits (només números) i el camp CVC en tingui tres. Però no són camps obligatoris.

Per als camps obligatoris, mostreu una vora vermella si un cop introduïts tenen un format no vàlid i una vora verda si un cop introduïts tenen un format correcte.

Totes les validacions esmentades (camps obligatoris, tipus de camp, patrons...) seran les pròpies de l'HTML5. A aquestes validacions no se'ls pot donar format personalitzat sense utilitzar JavaScript, per la qual cosa no caldrà tenir en compte aquest format, però sí que aparegui en cada cas el missatge
corresponent (utilitzant els atributs i valors adients).

NOTA: Per tal que aquest formulari "funcionés", les dades recollides haurien de ser processades per algun script. Aquesta tasca queda fora de l'abast de l'assignatura, per la qual cosa l'activitat proposada consisteix únicament a treballar amb les etiquetes HTML i les regles CSS.

## Condicions a tenir en compte en la maquetació dels documents

- Tipus de font: l'arxiu "TextosCopiaEnganxa.rtf" conté informació sobre el tipus de font a utilitzar; heu d'utilitzar el servei de Google Fonts.
- Mida de la lletra: cal fer els canvis de mida dels textos de cada part del document, tot imitant les proporcions del model. En aquesta PAC esperem que les mides de les fonts siguin expressades en unitats rem.
- S'han de respectar els alineaments de cada part del text.
- Enllaços: considereu quines regles CSS heu d'aplicar perquè els enllaços tinguin l'aspecte que es detalla al final de l'arxiu "TextosCopiaEnganxa.rtf". Heu de crear regles que permetin que els enllaços de menú de navegació i peu tinguin un aspecte diferent al dels enllaços dins dels textos.
- Composició: no cal que l'amplada del text en pantalla tingui exactament la mateixa mida que la dels models, si bé s'ha d'aconseguir que sigui llegible i que l'article aparegui centrat en la finestra del navegador. Tingueu en compte que capçalera i peu han d'ocupar el 100% de la finestra del navegador; els continguts de cada pàgina han de tenir una amplada menor.

## Altres activitats a realitzar

Tal com s'aprecia en les imatges model que s'adjunten, les pàgines interiors han de tenir d'una capçalera amb el logotip de l'organització (Amped Festival), que ha de permetre enllaçar amb la pàgina d'inici.

Creació d'un menú de navegació: les pàgines del lloc han d'estar enllaçades per un menú de navegació que haurà d'estar situat en la part superior de cada pàgina. S'ha de construir amb una llista no ordenada convenientment modificada amb CSS per tal que no es mostrin els pics per defecte i perquè els ítems es mostrin l'un al costat de l'altre. Fixeu-vos també que el color de fons té una opacitat del 70%.

Cada pàgina ha de tenir un peu de pàgina on s'inclourà el nom de l'estudiant i un menú d'enllaços buits (no condueixen a cap arxiu) amb l'avís legal, la política de privacitat i la política de cookies.

## Explicació de les entitats HTML i CSS utilitzades

En un document de text apart haureu d'afegir un apartat amb l'explicació de les entitats HTML i CSS utilitzats:

1. Sobre les entitats HTML: ha d'explicar-se l'ús de les etiquetes escollides.
2. Sobre el CSS: ha d'explicar-se tot el CSS utilitzat, incloent-hi quan s'ha utilitzat i per què i per a què s'apliquen els selectors i propietats definides.
3. NOTA: si realitzéssiu qualsevol canvi significatiu respecte dels models als quals heu d'aproximar el resultat, heu d'explicar els motius pels quals els heu realitzat.

## Validació i accessibilitat de les pàgines

Totes les pàgines lliurades, i el full d'estil associat, hauran de validar correctament. Cal assegurar-se
que les pàgines acompleixen amb els criteris d'accessibilitat al contingut web.