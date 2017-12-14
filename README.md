#Cuenta regresiva para año nuevo en java script
 
###libreria countdownplugin.js
 
Estoy modificando la estructura del plugin para implementarlo en mi pagina web con bootstrap
Archivos incluidos
1. index.html contiene la pagina de prueba 
2. countdown-plugin.js es la libreria para la cuenta regresiva
3. app.js la inicializacion de parametros y renderizado del elemento "div" para el funcionamiento del plugin

 

```[javascript]
// considerar los valores parametrizables ya sea dentro del plugin o en el archivo app.js
	var settings = $.extend({
			title: 'Cuenta regresiva',
			endYear: '2017',
			endMonth: 'December',
			endDay: '31',
			endTime: '23:59:59',
			flip: true,
			message: 'Happy New Year!!!',
		}, options);

```
 

 
**Resultado final**
 

 
!(https://ibb.co/kbnh5R )
