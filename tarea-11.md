# Tarea 11 - Ver la historia del archivo

GitHub guarda cada cambio que se hace a un archivo. Puedes ver quién cambió qué, cuándo, y por qué. Esto es uno de los superpoderes de GitHub.

## Paso 1: Ver quién escribió cada línea (Blame)

1. Abre [`index.html`](index.html) en este repositorio
2. Arriba a la derecha del archivo, haz clic en **"Blame"**
3. Ahora ves el archivo con colores: cada color es un commit diferente
4. A la izquierda de cada bloque ves:
   - **Quién** hizo el cambio (foto y nombre)
   - **Cuándo** lo hizo
   - **Qué mensaje** escribió en el commit

**Pregunta:** ¿Puedes encontrar tu sección? ¿Quién escribió la línea que está justo arriba de la tuya?

## Paso 2: Ver la historia completa (History)

1. Arriba del archivo, haz clic en **"History"** (al lado de Blame)
2. Ves una lista de todos los commits, del más reciente al más antiguo
3. Cada commit muestra:
   - Quién lo hizo
   - El mensaje que escribió
   - Cuándo fue

**Pregunta:** ¿Cuántos commits tiene el archivo? ¿Cuál fue el primero?

## Paso 3: Ver los cambios de un commit (Diff)

1. En la vista de History, haz clic en cualquier commit
2. Ves los cambios:
   - Las líneas en **verde** son lo que se **agregó**
   - Las líneas en **rojo** son lo que se **borró**
   - Las líneas sin color no cambiaron

**Pregunta:** Busca tu commit. ¿Qué líneas agregaste tú?

## ¿Por qué esto es importante?

- Si alguien daña el código, puedes ver **quién** lo hizo y **qué** cambió
- Puedes volver a cualquier versión anterior (como ya hicimos hoy cuando restauramos el archivo)
- En equipos de trabajo, esto es fundamental para no perder el trabajo de nadie
- OpenStreetMap funciona exactamente igual: cada cambio en el mapa tiene un historial completo

## Tarea

Revisa el Blame y el History de `index.html`. Encuentra:
1. Tu commit
2. El commit de un compañero
3. El commit más antiguo del archivo
