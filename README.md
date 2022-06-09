# AYTOALBA

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Requisitos

Tener instalado *node*
Se pueden utilizar los gestores de paquetes *npm* o *yarn*

La herramienta *npx* nos facilita la instalación de aplicaciones "pre-cargadas", para disponer de una versión mínima de next se puede ejecutar el siguiente comando `npx create-next-app nombre-app`

## Librerías UI

### Tailwindcss

#### Instalación manual
Instalar y configurar manualmente Tailwindcss, siguiendo las instrucciones  [Install Tailwind CSS with Next.js](https://https://tailwindcss.com/docs/guides/nextjs)


```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Configurar el array de paths en `tailwind.config.js`

Añadir las directivas Tailwind a CSS.

Ejecutar la aplicación mediante `npm run dev`

En este momento disponemos de una aplicación sin estilos, para poder utilizarlos debemos añadir `className` a las etiquetas y ver la documentación oficial sobre los componentes. [UI components](https://tailwindui.com/)

### Herramientas útiles

[Visual Studio Code](https://code.visualstudio.com/download)

[GitHub Desktop](https://desktop.github.com/)

[Web based editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor)
