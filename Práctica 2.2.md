# Sistemas de codificación 
## PARTE 1
### Investigue los dos principales sistemas de codificación (ASCII, UTF-8 o Unicode) y haga una tabla comparativa en términos de ventajas y desventajas, métodos de conversión y aplicación de cada uno.

Aspecto  | ASCII              | UTF-8              |            Unicode | 
|:--------:| :------------------: | :------------------: | :------------------: |
**Ventajas** | Es un sistema muy simple y ampliamente compatible con sistemas heredados. Usa solo 7 bits para representar caracteres, lo que lo hace eficiente en términos de almacenamiento.Fácil de entender y manejar para caracteres en inglés y otros idiomas occidentales. | Es una extensión del sistema ASCII y es compatible hacia atrás con él. Puede representar una amplia gama de caracteres, incluyendo aquellos de muchos idiomas y símbolos especiales. Es eficiente en términos de almacenamiento para caracteres comunes en inglés. Ampliamente adoptado y recomendado para la representación de texto en la web. | Ofrece una representación unificada de caracteres de todos los idiomas del mundo, así como símbolos y emojis. Permite una representación precisa y coherente de texto multilingüe en una amplia variedad de aplicaciones. 
**Desventajas**  | Limitado a 128 caracteres, lo que lo hace inadecuado para representar caracteres de otros idiomas. No es adecuado para la representación de texto multilingüe o caracteres no latinos. | Puede usar más bytes para representar caracteres no comunes en inglés, lo que puede aumentar el tamaño del archivo. | Puede requerir más espacio de almacenamiento que sistemas más simples como ASCII o UTF-8 para representar algunos caracteres, ya que utiliza un esquema de asignación de puntos de código único para cada carácter.
**Método de conversión** | La conversión entre ASCII y otros sistemas (como UTF-8 o Unicode) generalmente implica simplemente extender el conjunto de caracteres y ajustar la codificación. | UTF-8 es compatible con ASCII, por lo que la conversión implica simplemente extender el conjunto de caracteres y ajustar la codificación según sea necesario. | La conversión entre Unicode y otros sistemas generalmente implica asignar puntos de código Unicode a caracteres específicos.
**Aplicaciones** | Todavía se usa ampliamente en sistemas heredados, especialmente en aplicaciones donde se requiere una representación simple de caracteres en inglés. | Ampliamente utilizado en la web y en sistemas informáticos modernos para representar texto multilingüe y caracteres especiales. | Utilizado en aplicaciones globales, sistemas operativos y software moderno para garantizar la compatibilidad multilingüe y la representación precisa de caracteres de todo el mundo. | Ampliamente utilizado en la web y en sistemas informáticos modernos para representar texto multilingüe y caracteres especiales.
## PARTE 2
### Identifique el código para cada carácter de su nombre y primer apellido
#### Para formar mi nombre ALAN:
* A = U+0041
* L = U+004C
* N = U+004E

ALAN 

* U+0041 U+004C U+0041 U+004E = **ALAN**

#### Para formar mi primer apellido SERVÍN
* S = U+0053
* E = U+0045
* R = U+0052
* V = U+0056
* Í = U+00CD
* N = U+004E

SERVÍN

* U+0053 U+0045 U+0052 U+0056 U+00CD U+004E = **SERVÍN**

## PARTE 3
### Traduzca su nombre a tres tipos de caracteres: Cirílico, Chino y Japonés e identyifique el código para cada símbolo y genere su nombre utilizando ese código en LibreOffice.

* **ESPAÑOL** = ALAN SERVÍN 
  * U+0041 U+004C U+0041 U+004E U+0053 U+0045 U+0052 U+0056 U+00CD U+004E
* **CIRÍLICO** = АЛАН СЕРВИН
  * U+0410 U+041B	U+0410 U+041D	U+0421 U+0415 U+0420 U+0412 U+0418 U+041D 
* **CHINO**
  * U+827e U+4f26 U+00b7 U+585e U+6587
* **JAPONES**
  * U+30a2 U+30e9 U+30f3 U+30fb U+30bb U+30eb U+30d3 U+30f3

## PARTE 4
### Elija 10 emojis de su preferencia e identyifique el código para símbolo y generelos utilizando ese código en LibreOffice.

|1.|🎃  | U+1F383  | 6.| U+1F407	| 🐇|
|:---:|:----: |:--------:|----:|:------:|:-----:| 
|2.|🎅  | U+1F385  |  7.|U+1F616|😖|
|3.|🐣  |U+1F423   |	 8.| U+1FA75|🩵|
|4.|👻 |U+1F47B	    | 9.|U+1F916|🤖	|
|5.|🏇|U+1F3C7     |	10. |U+1F6F4|🛴|

## PARTE 5
### VIDEO

