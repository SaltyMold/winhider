# Landing Page and Docs for [Winhider](https://github.com/aamitn/winhider)

Built with Astro and Astro Starlight

GH Pages Build and Deploy Status : [![GH Pages Deploy](https://github.com/aamitn/winhider-website/actions/workflows/astro.yml/badge.svg)](https://github.com/aamitn/winhider-website/actions/workflows/astro.yml)

## Deploy URLs
- https://aamitn.github.io/winhider-website
- https://winhider.bitmutex.com
  
## 🚀 Project Structure
```text
└── /
    ├── public/
    │   ├── iamges
    │   ├── videos
    │   └── favicon.svg
    ├── src/
    │   ├── assets
    │   ├── components
    │   ├── content/
    │   │   └── docs (Astro starlight root)/
    │   │       └── docs (Docs Root)
    |   |         └── doc1.mdx
    |   |         └── doc2.mdx
    │   ├── layouts
    │   ├── pages
    │   ├── styles
    │   └── utils
    ├── package
    ├── astro.config.mjs
    ├── package.json
    ├── tailwind.config.mjs
    └── tsconfig.json
```


## 🧞 Commands
All commands are run from the root of the project, from a terminal:
| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Docs
- [Astro Docs](https://docs.astro.build) 
- [Astro Starlight Docs](https://starlight.astro.build/getting-started/)
