# Mi diario de HCI

Sitio web estático para un diario semanal de Interacción Humano-Computadora. Está preparado para abrirse localmente y para publicarse en GitHub Pages.

## Estructura

```txt
/
├── index.html
├── README.md
├── assets/
│   ├── images/
│   └── icons/
├── css/
│   ├── styles.css
│   └── delivery.css
├── js/
│   └── main.js
└── pages/
    ├── semana1.html
    ├── semana2.html
    ├── semana3.html
    ├── semana4.html
    ├── semana5.html
    ├── semana6.html
    ├── semana7.html
    ├── semana8.html
    └── delivery-ai.html
```

## Abrir localmente

Abre `index.html` directamente en el navegador. No necesita instalación ni servidor.

El diario usa Google Fonts (`Caveat` y `Nunito`) para dar apariencia de cuaderno. Si no hay internet, el navegador usará fuentes del sistema como respaldo.

## Imágenes reemplazables

Estas imágenes están en `assets/images/` y puedes reemplazarlas por versiones nuevas si hace falta:

- `assets/images/semana2-tiempo.png`
- `assets/images/semana4-figma.png`

Mantén los mismos nombres para que las páginas no necesiten cambios.

## Publicar en GitHub Pages

1. Sube todo el proyecto a un repositorio de GitHub.
2. En GitHub entra a `Settings > Pages`.
3. En `Build and deployment`, elige `Deploy from a branch`.
4. Selecciona la rama principal (`main` o `master`) y la carpeta raíz (`/root`).
5. Guarda los cambios y espera a que GitHub genere la URL.

Todas las rutas son relativas, así que el sitio funciona aunque GitHub Pages lo publique dentro de un subdirectorio.
