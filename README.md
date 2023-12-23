# Ejercicio2
Este proyecto deberá contar con 2 vistas:
1. La primera deberá enviar por HttpResponse un string que indique en qué año aproximadamente
nació una persona si le pasamos por la url la edad (para revisar si un string es solo numérico se
puede usar el método .isnumeric() de los strings que devuelve True en caso de que sean solo
números).
2. La segunda solo requerirá que en lugar de pasarle un string como argumento al HttpResponse se
le pase un template en el cual se mostrará un mensaje que diga "Bienvenidos".
La url de acceso deberá ser 'bienvenida/'.