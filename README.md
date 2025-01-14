# TanStack Start Counter App

A simple demo application built with TanStack Start that implements a persistent counter. This project was created following the [TanStack Start Build from Scratch guide](https://tanstack.com/router/latest/docs/framework/react/start/build-from-scratch).

## Available Scripts

In the project directory, you can run:

### `bun run dev`

Runs the app in development mode using Vinxi dev server.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `bun run build`

Builds the app for production to the `.output` folder.

### `bun run start`

Runs the built app in production mode.

## Installation

```bash
# Install dependencies
bun install

# Start development server
bun run dev
```

## Project Structure

```
.
├── app/
│   ├── routes/
│   │   ├── __root.tsx    # Root layout component
│   │   └── index.tsx     # Home page route
│   ├── client.tsx        # Client entry point
│   ├── router.tsx        # Router configuration
│   ├── routeTree.gen.ts  # Auto-generated route tree
│   └── ssr.tsx          # Server entry point
├── app.config.ts         # TanStack Start configuration
├── package.json
└── tsconfig.json
```

## Learn More

This project was bootstrapped following the [TanStack Start Build from Scratch guide](https://tanstack.com/router/latest/docs/framework/react/start/build-from-scratch).

For more information about TanStack Start and Router, check out:
- [TanStack Start Documentation](https://tanstack.com/router/latest/docs/framework/react/start)
- [TanStack Router Documentation](https://tanstack.com/router/latest/docs/framework/react)
