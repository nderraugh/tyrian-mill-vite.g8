A [Giter8][g8] template for Tyrian, Mill and Vite!

# Tyrian + Vite + Mill

This is a port of an instance of [PurpleKingdomGames/tyrian.g8](https://github.com/PurpleKingdomGames/tyrian.g8) to the Mill build system using Vite as the bundler.  Kudos to [Dave Smith](https://github.com/davesmith00000) and PurpleKingdomGames for building a great Elm-inspired frontend framework for Scala.js.

This is a minimal starter template that wires together:

- **Scala 3 + Scala.js + Tyrian + Mill + Vite**
- **[Tyrian](https://tyrian.indigoengine.io/)** (Elm-style UI in Scala)
- **[Mill](https://mill-build.org/)** as the build tool
- **[Vite](https://vitejs.dev/)** for dev server + bundling

The goal is to give you a small, understandable starting point for building Tyrian front-ends with a modern JS toolchain and a pleasant Scala build.

---

## Features

- ✨ **Tyrian**: Elm-inspired architecture in Scala 3 for building web UIs.
- ⚡ **Vite dev server**: Fast hot-reload for your Scala.js-generated JS.
- 🛠 **Mill build**: Simple, composable Scala build using `build.mill`.
- 📦 **Scala.js + Vite integration**: Uses `vite-plugin-scalajs-mill`.
- 🔧 **Tiny surface area**: A single Tyrian app module plus minimal JS glue.

> **Note:** Your main Scala.js module in `build.mill` is called `app`.

To install, use g8:

```bash
g8 nderraugh/tyrian-mill-vite.g8
```

or sbt:

```bash
sbt new nderraugh/tyrian-mill-vite.g8
```

[g8]: http://www.foundweekends.org/giter8/