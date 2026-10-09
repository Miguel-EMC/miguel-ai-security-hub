# Miguel · AI Security Learning Hub

Sitio estático para seguir una ruta de 12 meses hacia AI Security Engineering. Funciona sin instalación ni servidor: abre `index.html`. La guía original completa, con tareas, cursos, proyectos y enlaces, está en `guia-completa.html`.

## Secciones

- Resumen y métricas de progreso.
- Doce meses con estado y horas invertidas.
- Semana de estudio con importación opcional de horario académico.
- Tres proyectos y acceso a todos los recursos de la guía.
- Exportación e importación de progreso en JSON.

Los datos se guardan en `localStorage` del navegador. No hay cuenta ni sincronización entre dispositivos; exporta tu progreso para respaldarlo o moverlo. El horario privado no forma parte de este repositorio. No subas tu archivo personal de horario ni una exportación de progreso si prefieres mantenerlos privados.

## Publicación con GitHub Pages

Crea un repositorio público, sube los archivos de esta carpeta a la raíz y activa Pages desde la rama principal y la carpeta raíz. No requiere build. `index.html` es la portada y `guia-completa.html` contiene íntegra la guía anterior. Si decides alojarlo en una subcarpeta, los enlaces relativos seguirán funcionando.

## Horario privado

La página acepta un JSON con objetos `day` (0=lunes…6=domingo), `start`, `end`, `title` y `type` (`clase` o `reunion`):

```json
{"events":[{"day":0,"start":"09:00","end":"11:00","title":"Materia","type":"clase"}]}
```

Se importa desde la sección Semana y queda guardado únicamente en tu navegador.


## Prioridades actualizadas — 9 de octubre de 2026

La portada y guía incorporan un plan práctico de cuatro semanas: patrones de agentes, evaluación con datasets y Ragas, seguridad fuera del modelo, resiliencia y Python async. Incluye 15 tareas y criterios para avanzar. La guía añade prácticas de separación de responsabilidades, schemas, testing, lint, dependencias, secretos y ADRs. Se preservan las claves de progreso existentes. El sitio público no contiene notas, nombres de reclutadores ni documentos de entrevistas.

## Guía de ingeniería segura

`ingenieria-segura.html` desarrolla doce competencias, OpenSearch multiusuario, confidencialidad, matriz de pruebas, métricas, herramientas y un plan de 90 días. La ruta mensual de la portada se actualiza con este orden; el progreso sigue usando las mismas claves. Los estados de meses completados se conservan, pero conviene revisarlos si su alcance cambió. El calendario es orientativo y cada fase requiere evidencia.
