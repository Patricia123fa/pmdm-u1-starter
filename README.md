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
6. Crear Issue de reflexión y enlazarlo aquí: [Reflexión U1](https://github.com/Patricia123fa/pmdm-u1-starter/issues/1)
## Limitaciones y tecnologías (resumen)
- Limitaciones:
  Los móviles tienen CPU y memoria limitada, usando arquitectura big.LITTLE, que delega las tareas según su complejidad.  
- Con un procesamiento limitado, hay aplicaciones que pueden bloquearse o dar fallos, como por ejemplo algunas de edición 3D 
- o juegos con gráficos pesados, por lo que una forma de evitarlo es usar corrutinas. En cuanto a la memoria, en aplicaciones 
- que muestran gran cantidad de datos, como archivos o vídeos pesados, hay que liberar colecciones temporales y buffers, 
- para evitar agotar la memoria. La batería de los dispositivos es limitada y las aplicaciones de navegación son de las que más 
- consumen, por lo que deben optimizarse servicios en primer plano y detectores del nivel para adaptar funciones. La red y 
- conectividad intermitente afectan las aplicaciones de mensajería o streaming, por lo que alguna de las soluciones incluyen caché 
- local y reintentos de backoff. En cuanto al perfil de repartidor, una de las necesidades sería la optimización de batería y la 
- conectividad de red, ya que necesitan de servicios GPS para la realización de su trabajo. Para estudiantes necesitamos un acceso 
- rápido a la descarga de elementos como archivos o vídeos, siendo interesante la posibilidad de visibilidad offline.
- Tecnologías:
- Android (Kotlin/Java, Compose/XML): Desarrollo para Android, Java es mas antiguo y actualmente se utiliza más kotlin.
- iOS (Swift/SwiftUI): Desarrollo para apple.
- Multiplataforma/híbridas (Flutter, React Native, KMP, Ionic…): Sirven para desarrollo en Android e IOS

## Comandos Git usados

*(Si usaste el template, probablemente solo hiciste `git add/commit/push`)*
```bash
git add .
git commit -m "Hello World + README"
git push
git status
```
