# Tarea 12 - Corregir un issue y cerrarlo

## El ciclo completo del trabajo en equipo

En las tareas anteriores:
- Creaste tu marcador (Tarea 9)
- Revisaste el trabajo de tus compañeros (Tarea 10)
- Viste la historia de cambios (Tarea 11)

Ahora vamos a cerrar el ciclo: **corregir un problema y cerrarlo.**

## Paso 1: Buscar un issue que puedas corregir

1. Ve a la pestaña [**Issues**](https://github.com/leoguti/mapa-salesiano/issues) del repositorio
2. Lee los issues abiertos
3. Busca uno que mencione **tu marcador** o uno que tú puedas arreglar

## Paso 2: Corregir el error

1. Abre `index.html`
2. Haz clic en el **lápiz** para editar
3. Busca la línea con el error y corrígela
4. En el mensaje del commit escribe algo como:

```
Corregir coordenadas de Yosef - Cierra #7
```

**Importante:** Cambia el `#7` por el número del issue que estás corrigiendo. Lo ves en la pestaña Issues, cada uno tiene un número.

5. Selecciona **"Commit directly to the main branch"**
6. Haz clic en **"Commit changes"**

## ¿Qué pasa con "Cierra #7"?

Cuando escribes `Cierra #7` en el mensaje del commit, GitHub **automáticamente cierra el issue número 7**. No necesitas ir a cerrarlo a mano.

Esto es una de las funciones más poderosas de GitHub: los commits se conectan con los issues.

Otras palabras que también funcionan:
- `Cierra #7`
- `Closes #7`
- `Fixes #7`
- `Fix #7`

## Paso 3: Verificar

1. Ve a la pestaña Issues
2. El issue debería aparecer como **cerrado** (en morado)
3. Dentro del issue verás un enlace al commit que lo cerró

## ¿Por qué esto es importante?

Este es el ciclo completo de trabajo en equipo:

```
Crear algo → Alguien lo revisa → Reporta un problema → Tú lo corriges → Se cierra el issue
```

Así funcionan los equipos de software en todo el mundo. Y así funciona OpenStreetMap: alguien reporta que falta algo en el mapa, otro lo agrega, y se cierra el reporte.
