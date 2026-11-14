# Red ATS Panamá 3D

Visor web en 3D de la red aérea de Panamá: un planeta Tierra con los aeropuertos internacionales que tienen más vuelos hacia Panamá y un mapa 3D del país con sus aeródromos, espacios aéreos, rutas ATS y procedimientos de Tocumen, todo conectado para planificar y "volar" rutas de estudio.

Es una herramienta didáctica con estilo arcade, pensada para aprender visualmente cómo se organiza la red ATS de Panamá.

**Autor:** Delta Charlie · [github.com/Bugaryy](https://github.com/Bugaryy)

---

## Cómo abrirlo

Todo va dentro de un solo archivo: `index.html`. Datos, texturas, relieve y librerías están incrustados, así que no hace falta instalar nada ni descargar archivos extra.

- **En línea:** abre el enlace de GitHub Pages del proyecto.

Funciona en computadora, tablet y móvil. Necesita un navegador con WebGL.



https://github.com/user-attachments/assets/b657d951-f223-43f0-ba25-4338b69c77e8



## Funciones

### Globo
- Planeta Tierra con relieve y unos 100 aeropuertos internacionales con su designador OACI: Centroamérica, Caribe, Colombia y Sudamérica, Norteamérica y Europa.
- Arcos hacia Tocumen con tráfico animado.
- Ficha de cada aeropuerto con distancia y rumbo desde MPTO, tiempo aproximado y por dónde llega y sale de Panamá.
- Capa de centros de control (FIR / ACC / ARTCC) como MHCC, KZMA o SKED.

### Panamá 3D
- Relieve del país con exageración vertical ajustable (desde ×3).
- Aeródromos AD 2 (internacionales) y AD 4 (nacionales) con su designador.
- Radioayudas VOR/DME, puntos ENR 4.4 y aerovías: Inferiores, RNAV Q, Nacionales V y Superiores U.
- Espacios aéreos en volúmenes 3D: TMA Panamá, CTR (ámbar), ATZ (magenta) y FIR MPZL con sus sectores.
- Encuadres rápidos: Todo Panamá, TMA, Chiriquí y FIR.

### Procedimientos
- SID, STAR y aproximaciones (ILS y RNP) de Tocumen por pista y configuración, más las aproximaciones de los demás AD 2.
- Cada procedimiento se dibuja en 3D con sus restricciones de altitud y se puede volar.
- Enlace a las cartas detalladas de Tocumen (próximamente).

### Vuelos
- Planificador de origen, escala y destino entre cualquier aeropuerto extranjero y cualquier aeródromo de Panamá, o entre aeródromos nacionales.
- La ruta une salida (SID), aerovías, llegada (STAR) y aproximación, con perfil vertical, distancia y tiempo.
- Vuelo propio con ficha de datos, cámara que sigue al avión, barra de tiempo (pausa y velocidad) y tráfico automático.

### Tutorial guiado
Lleva la cámara al lugar, señala el elemento real de la interfaz y espera a que hagas cada acción. Recorre el mapa, las capas, los aeródromos, el globo, los vuelos, los procedimientos y el espacio aéreo.

## Controles

| Acción | Computadora | Táctil |
|---|---|---|
| Girar | Arrastrar | Arrastrar con un dedo |
| Desplazar | Clic derecho o Mayús + arrastrar | Dos dedos |
| Acercar / alejar | Rueda | Pellizco |
| Seleccionar | Clic en aeródromo, radioayuda o avión | Tocar |

El panel lateral se oculta y se muestra con la flecha del borde.

## Fuentes de datos

- **AIP Panamá:** aeródromos (AD 2 / AD 4), ENR 3 (rutas ATS), ENR 4 (radioayudas y puntos), TMA, CTR/ATZ, FIR y procedimientos de Tocumen. Los puntos que no se pudieron leer del AIP aparecen marcados como derivados.
- **Relieve:** modelo digital de elevación (teselas de terreno de código abierto).
- **Globo:** imagen Blue Marble de la NASA.
- **Costas y fronteras:** Natural Earth.
- **3D:** [three.js](https://threejs.org) (licencia MIT).

Las coordenadas de algunos aeropuertos extranjeros son aproximadas y solo sirven para ubicarlos en el globo.

## Aviso

Herramienta de estudio con fines didácticos y de uso personal. No es una fuente oficial ni operativa, no sustituye al AIP vigente ni a las cartas publicadas, y no debe usarse para la navegación aérea, la planificación de vuelos reales ni el control de tránsito aéreo.

## Licencia

© 2026 Delta Charlie. Todos los derechos reservados. Consulta el archivo [LICENSE](LICENSE).
