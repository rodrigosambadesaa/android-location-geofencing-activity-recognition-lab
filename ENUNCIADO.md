# Enunciado didáctico reconstruido — Location, Geofencing y Activity Recognition

Laboratorio Android para practicar las APIs de ubicación de Google Play services.

La aplicación debe:

- obtener la última ubicación conocida;
- crear una geovalla de aproximadamente 150 m alrededor de esa posición;
- eliminar la geovalla cuando el usuario lo solicite;
- recibir transiciones **ENTER** y **EXIT** mediante un `BroadcastReceiver`;
- iniciar y detener actualizaciones de **Activity Recognition**;
- mostrar la actividad más probable detectada por el sistema;
- solicitar los permisos de ubicación y reconocimiento de actividad únicamente cuando sean necesarios;
- informar de las limitaciones de entrega en segundo plano impuestas por las versiones Android modernas.

Para probar todas las funciones se requiere un dispositivo físico o emulador con Google Play services.

No existe una base de datos asociada.
