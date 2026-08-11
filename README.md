# Ejercicio de Desarrollo Web y Mobile - Replicar el CV de Lord Voldemort

[![Maximiliano López](https://img.shields.io/badge/GitHub-Maximiliano_López-B7E3FF?logo=github&logoColor=black)](https://github.com/maaxilopp)

## Descripción

Réplica de un CV a partir de una imagen de referencia, replicando su diseño lo más fielmente posible. El proyecto pone en práctica conceptos de maquetación con CSS:

- Estructura semántica con `header`, `section`, `footer`
- Layout con **Flexbox** (columnas de Perfil / Contacto, alineación de títulos y fechas)
- Posicionamiento con `position: absolute` / `relative`
- Fuentes personalizadas con `@font-face` (Raleway)
- Imagen de perfil circular con `border-radius` y `object-fit`
- Separadores de sección

## Estructura del proyecto

```
ej1/
├── assets/
│   ├── fonts/              # Fuentes Raleway (Regular y Bold)
│   ├── lord_voldemort.png  # Foto de perfil
│   ├── deathly_hallows.png
│   ├── tor.png
│   ├── Slytherin.png
│   ├── python.png
│   └── java.png
├── ej01.html               # Estructura del CV
├── ej01.css                # Estilos
└── ej_01_referencia.png    # Imagen de referencia
```

## Cómo verlo

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/maaxilopp/Voldemort_DesarrolloWeb.git
   ```
2. Abrí el archivo `ej01.html` en tu navegador.

## Tecnologías utilizadas
- HTML5
- CSS3 (Flexbox, posicionamiento, `@font-face`)
