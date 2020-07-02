# IoT Core

Con Cloud IoT Core, puede controlar un dispositivo enviándole una configuración de dispositivo. La configuración de un dispositivo es un blob de datos arbitrario definido por el usuario enviado desde Cloud IoT Core a un dispositivo. Los datos pueden ser estructurados o no estructurados. 

La información del estado del dispositivo captura el estado actual del dispositivo, no el entorno. Los dispositivos pueden describir su estado con un conjunto arbitrario de datos definidos por el usuario enviados desde el dispositivo a la nube. Los datos pueden ser estructurados o no estructurados. 

### Configuración del dispositivo
```json
"board": {
	"led1": {
		"duty":0.85,
		"state":true
	},
	"led2": {
		"duty":0.85,
		"state":true
	},
	"timer": {
		"timerOn":"22:00",
		"timerOff":"10:00",
		"timerState":false
	}
}
```

### Estado del dispositivo
```json
{  
  "hum":30.548615,
  "temp":34.038687
}
```