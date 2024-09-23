# MealsBuddy, saludable es ser bud

### Tecnologías utilizadas
- Remix (react based) + JS + npm
- Tailwind CSS
- Auth0 
- Figma
- Docker (más adelante)

Esto dentro de una arquitectura MVC que levanta una PWA.


### ¿Qué es MealsBuddy?

MealsBuddy es una aplicación web que te ayuda a llevar un control de tus comidas diarias, con el fin de que puedas llevar una alimentación más saludable.

### Guía para correr el proyecto

1. Clonar el repositorio
2. Instalar las dependencias con `npm install`
3. Correr el proyecto con `npm run dev` (lo corre con vite)
4. Acceder a `http://localhost:4200/`


## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever css framework you prefer. See the [Vite docs on css](https://vitejs.dev/guide/features.html#css) for more information.
