# Explicacion
duration=3 // son los segundos que dura la animacion dentro del inventario

h=512 // Alto

w=512 // Ancho

// H y W debe coincidir con el tamaño del inventario que este en minecraft/textures/gui/container/inventory.png 
en este caso deberia ser de la misma resolucion. esto tomara seccion por seccion

x=0 // 

Si quieres que se espeficique una posicion.

y=0 //

from=./crytednw.png //hago referencia a la imagen que se encuentre dentro de esta carpeta /anim

to=textures/gui/container/inventory.png 
//Aqui especifico que remplaza por asi decirlo el que se encuentre en la ruta que se describe
que debe tener la misma resolucion

en el caso de que el pack sea de 10 animaciones seria 512x5120 
pero especificar el h=512 w=512 es la seleccion que tendra he ira recorriendo
