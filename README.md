# SRS

## Getting Started

### Prerequisites

- Node.js

[Node.js](https://nodejs.org/en) is used as the runtime for the application and is required for the `react-router` scripts to run.

Install the latest minor and patch version of Node v22 using [nvm](https://github.com/nvm-sh/nvm).

- Bun

[Bun](https://bun.sh/) is used as the package manager and to run `package.json` scripts. Bun is currently not used as the runtime as the `react-router` scripts rely on Node.js APIs that Bun does not yet implement. Hopefully this will change in future so that Bun can be used as the runtime as well.

Install the latest version of Bun based on the instructions [here](https://bun.sh/docs/installation).

### Installation

Install the dependencies:

```bash
bun install
```

### Development

Start the development server with HMR:

```bash
bun run dev
```

The application will be available at `http://localhost:5173`.
