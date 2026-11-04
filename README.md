<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Class diagram: Ceejay Estabillo builds iGraphIT, photobook, portfolio and last-light-game" src="assets/banner-dark.svg" width="100%">
</picture>

<br />

I build mobile and web applications with a focus on clean architecture, predictable state, and interfaces that hold up across screen sizes. My work is TypeScript end to end: React Native and Expo on the client, Node.js and Express on the server, Firestore for persistence.

I am the programmer on a four-year capstone project, where I own the front end, the API, and the diagram-rendering layer.

<br />

## Featured project: iGraphIT

A Progressive Web Application that teaches SDLC models and lets students build UML diagrams with rule-based validation. 18 diagram types, from flowcharts and DFDs to class and sequence diagrams.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/architecture-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/architecture-light.svg">
  <img alt="iGraphIT three-tier architecture: Expo client, Express API, Firestore" src="assets/architecture-dark.svg" width="100%">
</picture>

<details>
<summary><b>Engineering notes</b></summary>
<br />

- **Diagram editor.** Custom `UniversalVertexHandler` on top of `@maxgraph/core`, giving draw.io-style selection and rotation handles through the library's native rotation pipeline.
- **Validation engine.** One shared structural rule engine behind 11 diagram-type validators, so each diagram type is checked against its own notation rules.
- **Authentication.** Express API with JWT access and refresh tokens, bcrypt password hashing, and OTP email verification through Nodemailer.
- **Google sign-in.** Redirect flow on mobile, selected by touch-capability detection rather than user-agent sniffing.
- **Performance.** Cache-first profile loading on the account screen.

</details>

[View repository →](https://github.com/ceejaydev1/igraph-it)

<br />

## Repositories

| Repository | Stack | Description |
| :-- | :-- | :-- |
| [igraph-it](https://github.com/ceejaydev1/igraph-it) | JavaScript | SDLC learning and UML diagramming PWA (capstone) |
| [photobook](https://github.com/ceejaydev1/photobook) | TypeScript | <!-- one-line description --> |
| [portfolio](https://github.com/ceejaydev1/portfolio) | HTML | Personal portfolio site |
| [last-light-game](https://github.com/ceejaydev1/last-light-game) | JavaScript | <!-- one-line description --> |

<br />

## Stack

| | |
| :-- | :-- |
| **Languages** | TypeScript · JavaScript · HTML · CSS |
| **Client** | React Native · Expo · Expo Router · React · PWA |
| **Server** | Node.js · Express |
| **Data** | Firebase · Firestore |
| **Tooling** | Git · GitHub · Metro |

<br />

## Status

```ts
const status = {
  building: "iGraphIT, capstone",
  studying: "BS Information Technology, Dominican College of Tarlac",
  learning: ["API design", "deployment pipelines"],
  open_to:  ["internships", "collaboration"],
} as const;
```
