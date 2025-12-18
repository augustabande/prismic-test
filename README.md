# My E-commerce Project

Progetto e-commerce sviluppato con [Prismic][prismic] e [Next.js][nextjs]. Un sito web moderno con gestione dei contenuti headless e interfaccia reattiva.

## ✨ Caratteristiche

- 🚀 Next.js 16 con App Router
- 📝 Gestione contenuti con Prismic CMS
- 🎨 Styling con Tailwind CSS
- 📱 Design responsive
- 🔧 TypeScript per type safety
- 🎯 Slice Machine per componenti modulari

&nbsp;

<img src="https://user-images.githubusercontent.com/8601064/166617932-eaaa1643-f086-4909-9868-56234f8da98d.png" alt="Screenshots of the site seen on deskop and mobile browsers" />

&nbsp;

## 🚀 Installazione

1. Clona il repository:
```sh
git clone <url-del-tuo-repo>
cd my-ecommerce
```

2. Installa le dipendenze:
```sh
npm install
```

3. Configura le variabili d'ambiente:
```sh
cp .env.example .env.local
```
Modifica `.env.local` con i tuoi dati Prismic.

4. Avvia il server di sviluppo:
```sh
npm run dev
```

Il sito sarà disponibile su [http://localhost:3000](http://localhost:3000).

## 📚 Documentazione

- [Documentazione Prismic][prismic-docs]
- [Documentazione Next.js](https://nextjs.org/docs)
- [Guida Tailwind CSS](https://tailwindcss.com/docs)

## 🤝 Contribuire

Vedi [CONTRIBUTING.md](./CONTRIBUTING.md) per le linee guida sui contributi.

## 📄 Scripts

- `npm run dev` - Avvia il server di sviluppo
- `npm run build` - Crea la build di produzione
- `npm run start` - Avvia il server di produzione
- `npm run lint` - Controlla il codice con ESLint
- `npm run format` - Formatta il codice con Prettier

## License

```
Copyright 2013-2022 Prismic <contact@prismic.io> (https://prismic.io)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[prismic]: https://prismic.io/
[prismic-docs]: https://prismic.io/docs/technologies/nextjs
[prismic-sign-up]: https://prismic.io/dashboard/signup
[nextjs]: https://nextjs.org/
[starter-docs]: ./docs/README.md
[live-demo]: https://nextjs-starter-prismic-multi-page.vercel.app/
