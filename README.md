# Angular Universal: Server-side Rendering in Angular Frameworks

Angular Universal enables server-side rendering (SSR) for Angular applications to improve initial load performance and SEO. Server-rendered HTML reduces time-to-first-paint and improves crawlability for search engines.

This project shows how to integrate Syncfusion Angular components (`@syncfusion/ej2-angular-grids`) into an SSR-capable Angular app. It explains where to import Grid modules, how to include global CSS so server-rendered markup is styled correctly, and how to render initial grid data on the server (for example using TransferState) so the client can hydrate without a visible empty state. Guard browser-only APIs with `isPlatformBrowser` and defer DOM access to client-only lifecycle hooks.

## Run the sample project

Clone and run locally:

```bash
git clone https://github.com/SyncfusionExamples/syncfusion-angular-universal.git
cd syncfusion-angular-universal
npm install
```

Build and serve the SSR bundle:

```bash
npm run build:ssr
npm run serve:ssr
```

For the Ionic example (if present), run:

```bash
ionic serve
```
