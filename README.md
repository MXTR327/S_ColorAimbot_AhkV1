**Instrucciones de uso del script**

**Paso 1: Instalación**
* Descarga el script y colócalo en una carpeta de tu elección.

**Paso 2: Ejecución**
* Ejecuta el script haciendo doble clic en el archivo .exe.
* El script creará automáticamente un archivo `config_[RESOLUCIÓN]_[VERSIÓN].ini` adaptado a tu pantalla.

**Paso 3: Uso y Configuración**

**Combinaciones de Teclas:**
* `F5`: Recarga el script.
* `F8`: Activa/Desactiva el script (estado inicial en `script_activo_por_defecto`).
* `F12`: Cierra la aplicación.
* `Ctrl + Shift + D`: Muestra/Oculta las áreas de disparo y ajustes.

**Explicación de Variables en `config.ini`:**

### Sección: *Área_Aimbot*
- *aimAreaX*: Ancho del área de escaneo (1-500).
- *aimAreaY*: Alto del área de escaneo (1-500).
- *maxDistPixelsAgrupamiento*: Agrupamiento de lista de pixels encontrados (0-~~).
- *minPixelsGrupo*: Minimo requerido para considerarlo grupo (0-~~).
  
### Sección: *Area_Antishake*
- *estadoAntishake*: Activar filtro de vibración (`true`/`false`).
- *antishakeAreaX*: Área horizontal ignorada al detectar movimiento (1-30)).
- *antishakeAreaY*: Área vertical ignorada al detectar movimiento (1-30).

### Sección: *Color*
- *utilizar_color_personalizado*: Usar color hexadecimal personalizado (`true`/`false`).
- *color_personalizado*: Color HEX para detección (Ej: `0x000000` para rojo).
- *sensibilidad_color*: Tolerancia de color (0-50). Valores bajos = mayor precisión.

### Sección: *Experimentos*
- *desactivar_escalado_dpi*: Mejora rendimiento en pantallas HD (`true`/`false`).
- *prediccionMS*: Prediccion de posicion a futuro en milisegundos (1-50).
- *aimAntiDetection*: Añade variabilidad aleatoria al movimiento evitando deteccion de anticheats (`true`/`false`).
- *aimHumanizacion*: Limita la velocidad máxima del aimbot para parecer humano (`true`/`false`).
- *aimVelocidadHumanizacion*: Velocidad del humanizador (1-10)
- *intentos_busqueda*: Número de intentos de detección por ciclo (1-15).
  
### Sección: *General*
- *aimVelocidadX*: **Velocidad horizontal del aimbot (1-100).**  
  Ej: `60` = 60% de velocidad.
- *aimVelocidadY*: **Velocidad vertical del aimbot (1-100).**  
  Ej: `50` = 50% de velocidad.

### Sección: *Mouse*
- *aimClickIzquierdo*: Activa el aimbot al hacer clic izquierdo (`true`/`false`).
- *aimClickDerecho*: Activa el aimbot al hacer clic derecho (`true`/`false`).
- *lock*: Activa para usar en primera persona, Desactiva para usar cursor libre (`true`/`false`).
  
### Sección: *Offsets*
- *nivelOffsetX*: Para centrar la mira en el objetivo o desviarla horizontalmente (-4-4).
   Ej: `-4` = Extremo izquierdo.
   Ej: `-3` = Mitad izquierda.
   Ej: `-2` = 1/3 de la izquierda.
   Ej: `-1` = 1/4 de la mitad izquierda.
   Ej: `0` = Alineado a la mitad horizontalmente.
   Ej: `1` = 1/4 de la mitad derecha.
   Ej: `2` = 1/3 de la derecha.
   Ej: `3` = Mitad derecha.
   Ej: `4` = Extremo derecho.
- *nivelOffsetY*: Para centrar la mira en el objetivo o desviarla verticalmente (-4-4).
   Ej: `-4` = Extremo inferior.
   Ej: `-3` = Mitad inferior.
   Ej: `-2` = 1/3 inferior.
   Ej: `-1` = 1/4 de la mitad inferior.
   Ej: `0` = Alineado a la mitad verticalmente.
   Ej: `1` = 1/4 de la mitad superior.
   Ej: `2` = 1/3 superior.
   Ej: `3` = Mitad superior.
   Ej: `4` = Extremo superior.
- *offsetX*: Compensación horizontal del punto de mira (0-15).
- *offsetY*: Compensación vertical del punto de mira (0-50).
  
**Paso 4: Desinstalación**
* Cierra el script con `F12`.
* Elimina todos los archivos relacionados, incluido el `.ini` generado.

**Notas Importantes:**
- El archivo de configuración se genera automáticamente con tu resolución y versión.
- ¡Usa `Delete o Supr` para acceder rápidamente al panel!
- La sección *Experimentos* contiene funciones en desarrollo - úsalas con precaución.
