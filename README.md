# Natio Station: La Emisora del Amor

**Natio Station** es una emisora de radio por Internet que lleva la música del corazón a tus oídos. Disfruta de tus canciones favoritas en formato MP3 con una interfaz moderna y responsiva desarrollada en HTML5 y CSS3. ¡Conectémonos con el amor a través de la música!

---

## Características

- **Radio en Línea:** Escucha una selección curada de canciones en formato MP3 desde cualquier dispositivo con conexión a Internet.
- **Base de Datos en JSON:** Gestiona las pistas de audio y sus metadatos de manera sencilla con un archivo JSON.
- **Diseño Moderno:** Interfaz creada con HTML5 y CSS3 para garantizar compatibilidad, rendimiento y una experiencia visual agradable.
- **Responsivo:** Adaptado para verse perfecto en dispositivos móviles, tabletas y computadoras.

---

## Tecnologías Utilizadas

- **Frontend:**
  - HTML5
  - CSS3
- **Gestor de Datos:**
  - JSON

---

## Estructura del Proyecto

```
├── index.html         # Archivo principal de la aplicación
├── styles/           # Archivos CSS
│   └── main.css     # Estilos principales
├── scripts/          # Scripts JS (si aplica)
├── assets/           # Archivos estáticos (imágenes, MP3, etc.)
│   └── music/      # Pistas en MP3
├── data/             # Archivos JSON
│   └── tracks.json  # Base de datos de canciones
└── README.md        # Documentación del proyecto
```

---

## tracks.json: Estructura de la Base de Datos

El archivo `tracks.json` contiene información sobre las canciones disponibles en la emisora. A continuación, un ejemplo:

```json
[
  {
    "id": 1,
    "title": "Canción del Corazón",
    "artist": "Artista Romántico",
    "file": "assets/music/cancion_del_corazon.mp3"
  },
  {
    "id": 2,
    "title": "Melodía de Amor",
    "artist": "Dúo Sentimiento",
    "file": "assets/music/melodia_de_amor.mp3"
  }
]
```

---

## Instalación y Uso

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/tuusuario/natio-station.git
   ```

2. **Abre el archivo `index.html` en tu navegador:**
   - No necesitas un servidor local; solo un navegador compatible.

3. **Edita el archivo `tracks.json` para agregar tus propias canciones.**

4. **Disfruta de la música!**

---

## Contribución

¡Las contribuciones son bienvenidas! Si deseas agregar nuevas funciones, mejorar el diseño o ampliar la documentación:

1. Haz un fork del repositorio.
2. Crea una rama para tu función o mejora:
   ```bash
   git checkout -b mejora-mi-funcion
   ```
3. Haz commit de tus cambios:
   ```bash
   git commit -m "Agregada nueva función de reproducción aleatoria"
   ```
4. Haz un push a tu rama:
   ```bash
   git push origin mejora-mi-funcion
   ```
5. Crea un Pull Request.

---

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

---

## Contacto

Si tienes preguntas, sugerencias o simplemente quieres decirnos cuál es tu canción favorita, escríbenos a:
- **Email:** 
- **Redes Sociales:**
-  [@natiostationtv](https://www.youtube.com/@natiostationtv)
-  [@natiostation](https://masto.es/@natiostation)

¡Gracias por elegir Natio Station: La emisora del amor! ❤️
