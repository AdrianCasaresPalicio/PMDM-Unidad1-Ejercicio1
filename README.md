# Hola Mundo DAM - Unidad 1

## Objetivos del ejercicio

- Comprobar que Android Studio y Git funcionan.
- Crear tu proyecto Android y gestionarlo con Git/GitHub.
- Documentar limitaciones de dispositivos móviles y tecnologías actuales.

## Requisitos previos

- Android Studio instalado.
- Git instalado y configurado (`user.name` y `user.email`).
- Cuenta de GitHub activa.

## Pasos realizados (rellena tú)

1. Crear/confirmar cuenta en GitHub.
2. Pulsar **"Use this template"** en el repo starter de la profesora.
3. Clonar el repo con **Get from VCS** en Android Studio (eligiendo "Use this template")
4. Crear el proyecto “Hello World” dentro del repo (o moverlo después).
5. Hacer commit y push de los cambios al remoto.
6. Crear Issue de reflexión y enlazarlo aquí: [Reflexión U1](#)
## Limitaciones y tecnologías (resumen)
- 
- Limitaciones: Los dispositivos móviles presentan varias limitaciones técnicas que todo desarrollador debe considerar.
CPU limitada, RAM reducida, almacenamiento restringido y conectividad variable son los principales retos.
Por ejemplo, una CPU que se calienta demasiado puede ralentizar una app de edición de imágenes.
Si todo se ejecuta en el hilo principal, esto provoca bloqueos inesperados y frustración en el usuario.
La batería y la conectividad intermitente también son factores críticos en el diseño de apps.
Una batería baja limita operaciones intensivas, mientras que una red inestable retrasa la sincronización de datos.
Para mitigar estos problemas, se pueden agrupar llamadas a la red y usar herramientas como WorkManager.
Esto permite ejecutar tareas cuando el dispositivo tenga suficiente carga o una conexión estable.
Respecto a los perfiles de usuario, un repartidor necesita una app confiable offline.
Debe contar con GPS preciso y notificaciones inmediatas para realizar su trabajo eficientemente.
En cambio, un estudiante busca una interfaz intuitiva y carga rápida de contenidos.
Además, requiere bajo consumo de datos, ideal para dispositivos de gama media y uso cotidiano.


- Tecnologías: ...

Aquí está mi reflexión: https://github.com/AdrianCasaresPalicio/PMDM-Unidad1-Ejercicio1/issues/1
## Comandos Git usados

*(Si usaste el template, probablemente solo hiciste `git add/commit/push`)*
```bash
git add .
git commit -m "Hello World + README"
git push
```
