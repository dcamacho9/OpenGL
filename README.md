# OpenGL / GLSL (Shaders)

Compuesto de 4 pr�cticas de OpenGL y GLSL

## Practica 1 Introduccion a GLSL
El objetivo de esta pr�ctica es entender los fundamentos de programaci�n de �shaders�
	��* Implementaci�n de un Shader b�sico
	��* Color por vertice
	��* Acceso a texturas
	��* Normales
	��* Matriz de proyecci�n que conserva el aspect ratio
	��* A�adir elementos a la escena
	��* Control de c�mara con teclado y giro con rat�n
	��* Movimiento de los objetos de la escena
	��* Crear modelo y aladir a la escena definiendo sus v�rtices

Mover con wasd, rat�n con bot�n derecho para vista


## Practica 2 Iluminaci�n en GLSL
El objetivo de esta pr�ctica es aplicar las t�cnicas de iluminaci�n en un cauce gr�fico real.
Se repasar�n conceptos como: modelos de iluminaci�n, modelos de sombreado, tipos luces� 

	��* Sombreado de Goureau
	��* Sombreado de Phong
	��* Texturas
	��* Iluminar objeto con luz direccional y luz focal
	��* Atenuar intensidad lum�nica en funci�n de la distancia
	��* Implementado t�cnica de Bump Mapping
	��* Calcular normales y tangentes de un modelo cargado desde fichero


## Practica 3 Introducci�n a la programaci�n en OpenGL
El objetivo de esta pr�ctica es programar la etapa de aplicaci�n utilizando el API de OpenGL 3.3.

	��* Creaci�n del contexto de OpenGL
	��* Configuraci�n del cauce
	��* Carga de modelo
	��* Renderizado del modelo
	��* Ajuste del viewport
	��* Animaci�n
	��* Texturas
	��* Modificar propriedades de (intensidad y posici�n) de la luz a trav�s de teclado
	��* Definir matriz de proyecci�n que conserve el aspect ratio cuando cambia el aspect ration
	��* A�adir cubos a la escena con VAO
	��* Control de c�mara con el teclado
   	��* Mejorar el comportamiento de las texturas utilizando un filtro anisotr�pico
	��* Implementar funcionalidad de las pr�cticas 1 y 2

## Practica 4 Aumento de realismo - Post-Proceso (MRT)
	El objetivo de esta pr�ctica es entender que los m�todos de iluminaci�n local no pueden simular muchos de los comportamientos t�picos de la luz. La posibilidad de renderizar sobre una textura que se pueda utilizar posteriormente en la escena nos permite dise�ar t�cnicas que suplan de forma m�s o menos efectiva alguna de estas carencias.
	
	��* Renderiza cuadrado sobre el plano de proyecci�n
	��* Motion Blur
	��* Gaussian Blur
	��* Depth of field
	��* Controlar par�metros de Motion Blur a trav�s de teclado
	��* Controlar par�metros del DOF por teclado (distancia focal y distancia de desenfoque m�ximo)
	��* Utilizar el buffer de profundidad para controlar el DOF
	��* Subir nuesvas m�scaras de convoluci�n a trav�s del DOF
	��* Concatena varios filtros Gausianos.
	��* Concatena varios post-proceso distintos
	��* Implementa funcionalidad de las pr�cticas 1,2 y 3