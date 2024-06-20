# Projecte d'estabilització de costes
La gestió de costes és un tema de gran importància degut al seu impacte en l’economia, el medi ambient i la societat. Factors com la expansió urbana, la construcció d’infraestructures i l’explotació de recursos naturals són algunes de les principals activitats humanes que més han afectat a les costes i els seus ecosistemes. Aquests impactes han provocat conseqüències negatives com les erosions de les platges,  la pèrdua de biodiversitat, la contaminació de les aigües, entre d’altres. És per això que és necessari implementar alternatives de gestió que promoguin la sostenibilitat i la conservació dels recursos de les costes.
En aquesta pàgina web es mostren dos tipus de projectes que es poden dur a terme per tal de lluitar contra la recessió de les costes.  
## Dades
Les dades de la pàgina web han estat extretes d'un treball anomentat "GESTIÓ COSTANERA: CONSEQÜÈNCIES I ALTERNATIVES. (APORTACIONS DE SORRA DE PLATJA, FIXACIÓ DE DUNES, 
CREACIÓ D’ESPIGONS DE DEFENSA, ETC)", realitzat anteriorment en el marc de l'assignatura de biogeografia i biodiversitat del segon curs del grau de geografia, anàlisi territorial i sostenibilitat.
## Estructura de la pàgina web 
La pàgina web està dividida en 5 apartats: Home, Projectes, Membres, Mapes i Contacte. 
1. Home: En aquesta primera pàgina en dona informació general sobre el tema tractat i el context en l'àmbit català.
2. Projectes: Aquí es posen dos exemples sobre possibles mètodes d'estabilització de les costes.
3. Membres: Es mostren els membres del treball d'investigació, juntament amb una fotografia.
4. Mapa: En aquest mapa es mostren exemples de tècniques d'estabilització de costes al municipi de Cunit.
5. Contacte: En aquest últim apartat els possibles visitants de la web podrien contactar amb els responsables de la pàgina, fàcilitant la comunicació entre els lectors i els investigadors.
## Web responsive
Per poder fer que la pàgina web sigui accessible i adaptable en tots els dispositius possibles i les seves variants (telèfons mòbils, tauletes o ordinadors), s'ha utilitzat les regles "media query" en CSS. Això permet redimensionar tant els texts com les imatges de la pàgina web.
```
@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block; 
  }
}
```
## Cartografia 
La cartografia ha estat realitzada mitjançant el software de QGIS, on s'han digitalitzat diversos polígons que mostren exemples de tècniques d'estabilització de costes. La imatge satèl·lit de fons ha estat proporcionada per ESRI. 
Un cop realitzat el mapa en QGIS, s'ha emprat el plugin qgis2web per tal d'exportar la cartografia a un format web que permetés adjuntar-lo a la pàgina.
## Dificultats/millores
Han estat moltes les dificultats per realitzar la pàgina web, ja que partia d'un total desconeixement en aquest àmbit. És un món molt complex i que requereix de moltes hores d'estudi per poder arribar a entendre els diferents llenguatges que es poden arribar a utilitzar. 
Pel que fa a la millores, són moltes les que es podrien fer a la pàgina, però es mostren els requisits mínims per a poder ser una pàgina web amb cara i ulls. 


