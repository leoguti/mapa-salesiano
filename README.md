# Mapa del Salesiano - Nuestros Lugares Favoritos

Proyecto colaborativo de la Escuela de OpenStreetMap + Vibe Coding del Club Deportivo Salesiano, Duitama.

**Ver el mapa en vivo:** https://leoguti.github.io/mapa-salesiano/

---

## Tarea 9 - Agregar tu marcador al mapa

### Paso 1: Buscar las coordenadas de tu lugar favorito

1. Abre https://www.openstreetmap.org
2. Busca tu lugar favorito de Duitama
3. Haz clic derecho en el punto exacto
4. Selecciona **"Show address"**
5. Copia los dos números que aparecen (latitud y longitud). Ejemplo: `5.8271, -73.0330`

### Paso 2: Editar el mapa

1. Abre el archivo [`index.html`](index.html) en este repositorio
2. Haz clic en el **lápiz** (icono de editar)
3. Busca la sección con tu nombre, por ejemplo `// === NADIA ===`
4. Borra el comentario de instrucción y reemplázalo con este bloque:

```javascript
        L.marker([LATITUD, LONGITUD]).addTo(map)
            .bindPopup(
                '<div class="popup">' +
                '<h3>NOMBRE DEL LUGAR</h3>' +
                '<p>DESCRIPCION: por qué me gusta este lugar</p>' +
                '<span class="autor">Agregado por: TU NOMBRE</span>' +
                '</div>'
            );
```

5. Cambia:
   - `LATITUD, LONGITUD` por las coordenadas que encontraste
   - `NOMBRE DEL LUGAR` por el nombre real
   - `DESCRIPCION` por tu descripción personal
   - `TU NOMBRE` por tu nombre

### Paso 3: Guardar (commit)

1. Abajo en **"Commit changes"** escribe un mensaje, por ejemplo: `Agregar Plaza de los Libertadores - Nadia`
2. Haz clic en el botón verde **"Commit changes"**

### Paso 4: Ver el resultado

Abre https://leoguti.github.io/mapa-salesiano/ y busca tu marcador en el mapa. Puede tardar 1-2 minutos en actualizarse.

---

## Importante

- Edita solo TU sección, no toques las de los demás
- Si alguien más está editando al mismo tiempo puede haber conflictos. Avisa antes de editar.

---

## Equipo

| Nombre | GitHub |
|---|---|
| Leonardo (instructor) | [@leoguti](https://github.com/leoguti) |
| Nadia | [@NadiaM3100](https://github.com/NadiaM3100) |
| Brayan | [@EsneiderCastro](https://github.com/EsneiderCastro) |
| Cristian | [@CristianTibaduiza](https://github.com/CristianTibaduiza) |
| Camilo Peña | [@JuanCamilo777Pro](https://github.com/JuanCamilo777Pro) |
| Ana María | [@AnaBeco](https://github.com/AnaBeco) |
| Yosef | [@yosef064](https://github.com/yosef064) |
| Edward | [@EDWARD-rincon](https://github.com/EDWARD-rincon) |
| Stefania | [@StefaniaAlvarez](https://github.com/StefaniaAlvarez) |

Escuela de OpenStreetMap + Vibe Coding | Club Deportivo Salesiano | Duitama, 2026
