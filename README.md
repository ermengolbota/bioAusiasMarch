# bioAusiasMarch
Exercici fet a classe.

A partir de la biografia de l'Ausiàs March (haureu de modificar una mica l'html )

http://codepen.io/ermengolbota/pen/ZezwOY



Apliqueu-li un CSS que:

1. Mostri el menú en vertical a la part esquerra (20%-80% aprox), però si la pantalla fa menys de 600px aleshores mostrarà el menú primer i després el contingut.
    1. En pantalla gran, el menú s'ha de veure sempre (que no es mogui si es fa scroll, mireu la propietat "position")
    1. En pantalla gran, a sota del menú s'ha de veure la fotografia upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Ausias_Marc.jpg/564px-Ausias_Marc.jpg
    1. En pantalla petita, la imatge serà només la cara, sense fons (heu de retallar-la....) i també es mostrarà a sota del menú. I quan es faci scroll, pujarà normal amb el menú i la resta de pàgina.
1. En qualsevol dispositiu el contingut s'ha de veure correctament (etiqueta meta....)
1. Els títols de cada apartat han d'estar numerats (via CSS)
1. El menú ha de portar a cadascun dels apartats (heu d'afegir àncores a l'html per fer enllaços locals) < 10 minuts
1. Embelleix una mica la presentació (espais, font, colors, fons...) <=20 minuts. 
1. En pantalla gran, en clicar a un link del menú, aquest ha de fer un efecte de vibració (per exemple, feu una transformació girant l'element uns 10 o 15 graus diverses vegades). En JS heu d'escoltar l'onclick i afegir una classe que dispari la vibració.
1. En posar el ratolí a sobre d'un títol (no del menú), faci algun efecte  "animat" amb els "bordes" del títol, i millor, de tot l'apartat en qüestió (tot l'article). És a dir, en el hover del titol heu d'aplicar un estil a tot l'article.
L'animació NO pot afectar a la posició del text. No s'ha de moure.
L'animació ha d'afectar als bordes (inclús l'esquerra) i crear algun efecte de moviment....
la propietat box-sizing: border-box; us pot ser útil pel tema de les mides. Depenent de com ho feu....