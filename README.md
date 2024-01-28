# Federación Colombiana de Esrgima

Repositorio para con el código de la página web de la federación colombiana de esgrima.

## 🧰 Tecnologías

- [pnpm v4]() como gestor de paquetes javascript
- [astro v4]() como framework web
- [typescript]() como super conjunto de javascript


## 🚀 Estructura del proyecto

Dentro de este proyecto usted encontrará los siguientes fichero y archivos:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca las extensiones `.astro` o `.md` de los archivos en el directorio `src/pages/`. Cada página es expuesta como una ruta basada en el nombre del archivo.

En cuanto al directorio `src/components/`, es aquí donde se ponen los componentes web independiente de si son componentes Astro/React/Vue/Svelte/Preact.

Cualquier asset estático (e.g., imágenes) se ubican el el directorio `public/`.

## 🧞 Comandos

Todos los comandos se corren desde la raíz del proyecto desde una terminal.

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

## 📑 Documentación

Por favor revisar la documentación el la carpeta `docs/`