Adaptación Coro Castilleja (2.0)  
================================  

Tareas pendientes:  
### 1. Index.html
	1.1. ~~Nombre~~, 
		~~1.1.1. imagen de fondo cabecera, colores~~  
	1.2. ~~Nombre del cancioneroTochoCastilleja.js~~  
	1.3.  


### 2. CancioneroTochoCastilleja.js EL MASTER ES EL DE CASTI - CORO, por los espacios de las notas~~COORDINADOR_DE_CORO~~  
	2.1. Metodología para añadir nuevos cantos: VER COMENTARIOS MÁS ABAJO  
		2.1.1. Crear copia del cancionero 'on line' (versión master), ¿github, neocities, Drive??  
		2.1.2. Convertir en tabla, con campos.  
		2.1.3. Dos campos de encabezado,  
		2.1.4. Versionar: para evitar líos,  
		2.1.5. Cómo replicar las versiones entre Coordinador de coro y CastiCoro  

	2.2. ~~Añadir cantos 13/01/19~~  


### 3. coro2.js  
	3.1. ~~cambiar 'misa por defecto'~~  
	3.2. 


### 4. Coordinador De Coro  
4.1. ~~Añadir versión en pantalla principal~~  
4.2. Añadir css a la versión  




=============================  
=============================  
CancioneroTochoCastilleja.js tiene la siguiente estructura:  
/* un comentario descriptivo de la estrutura del cancionero,  
entre comentarios tipo JavaScript */  
cantos = [  
( cancionero completo, cada canto entre { } )  
]  

Lo que hay entre ( ), el cancionero completo, es una estructura JSON, que puede visualizarse fácilmente en http://jsoneditoronline.org/, por ejemplo.  

Cuando hay que añadir un canto, se trata de crear la ficha complentando los campos correspondientes al nuevo canto. Completar la siguiente plantilla, y pegar al final de CancioneroTochoCastilleja.js (incrementar versión).  

NOTA: antes de pegarlo, eliminar los saltos de línea que hay aquí, para que todo esté en una misma línea (como todo en json).  

,{"Id":4005,"Letra":"DO   SOL    lam\nCOMO EL PADRE ME AMÓ\nFA    re   SOL     \nYO OS HE AMADO,\nDO      SOL        la      \nPERMANECED EN MI AMOR, \nF       SOL        DO  (SOL)\nPERMANECED EN MI AMOR. (BIS)\n\nla                   DO      \nSi guardáis mis palabras\nFA        SOL         DO \ny como hermanos os amáis,\nmi                    la\ncompartiréis con alegría\n    FA                SOL \nel don de la fraternidad.\n\nSi os ponéis en camino,\nsirviendo siempre a la Verdad,\nfrutos daréis en abundancia,\nmi Amor se manifestará.\n\nESTRIBILLO\n\nNo veréis amor tan grande \ncomo aquel que os mostré, \nyo doy la vida por vosotros,\nAmaos como Yo os amé.\n\nSi hacéis lo que os mando\ny os queréis de corazón,\ncompartiréis mi pleno gozo\nde amar como Él me amó.\n","Titulo":"AMAOS","Autor":"J. Madurga","Libro1":"J","Libro2":"","Temario1":"Ordinario","Temario2":"","Orden":4005,"id":null}

DO       SOL      lam\n
COMO EL PADRE ME AMÓ\n
FA    re   SOL     \n
YO OS HE AMADO,\n
DO      SOL        la      \n
PERMANECED EN MI AMOR, \n
F       SOL        DO  (SOL)\n
PERMANECED EN MI AMOR. (BIS)\n
\n
la                   DO      \n
Si guardáis mis palabras\n
FA        SOL         DO \n
y como hermanos os amáis,\n
mi                    la\n
compartiréis con alegría\n
    FA                SOL \n
el don de la fraternidad.\n

/* **********FICHA VACÍA *************
,{"Id":4006,
"Letra":"",
"Titulo":"",
"Autor":"",
"Libro1":"",
"Libro2":"",
"Temario1":"",
"Temario2":"",
"Orden":4006,
"id":null}



/********** VALORES LIBRO 1 *************************
    'A': 'rito_inicial.entrada',
    'B': 'rito_inicial.perdon',
    'C': 'rito_inicial.gloria',
    'D': 'liturgia_palabra.antifona',
    'E': 'liturgia_palabra.aleluya',
    'F': 'liturgia_eucaristica.ofertorio',
    'G': 'liturgia_eucaristica.santo',
    'H': 'liturgia_eucaristica.padrenuestro',
    'I': 'liturgia_eucaristica.paz',
    'J': 'liturgia_eucaristica.comunion', 
    'K': 'despedida.envio', 
    'M': 'despedida.maria', 
    'V': 'despedida.villancico', 
    'X': 'despedida.extra', 
    'Y': 'despedida.extra', 
    'Z': 'despedida.extra'


/************* VALORES LIBRO 2***************************
vacío
/*     VALORES TEMARIO 1 *****************************
"Temario1":"Maria"
"Temario1":"Adviento"
"Temario1":"Bautismo"
"Temario1":"Cuaresma"
"Temario1":"Feyluz"
"Temario1":"Misioneras"
"Temario1":"Niños"
"Temario1":"Ordinario"
"Temario1":"Pentecostes"
"Temario1":"Perdon"

/*     VALORES TEMARIO 2 *****************************
"Temario2":"Adviento"
"Temario2":"Cuaresma"
"Temario2":"Feyluz"
"Temario2":"Niños"
"Temario2":"Misioneras"
"Temario2":"Maria"
"Temario2":"Ordinario"
"Temario2":"Perdon"
"Temario2":"Pentecostes"

