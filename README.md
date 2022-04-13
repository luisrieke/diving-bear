<h1 align="center">Diving bear website built with Astro</h1>

I created this website for my music. I produce whatever I want to with Ableton, Rekordbox and my guitar. You can find the music on every platform when searching for _diving bear_.

But why did I use Astro? Astro is a framework for building websites. It's a way to build websites that is easy to use and easy to understand.

## Links and external ressources

[Astro documentation](https://github.com/withastro/astro)

[View diving bear website live](https://divingbearmusic.com)

## Installing & Running

### Prerequisites:

- Node v16 or later (check version using `node -v`)

### Commands:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where Astro/React/Vue/Svelte/Preact components are meant to be.

Any static assets, like images, can be placed in the `public/` directory.
