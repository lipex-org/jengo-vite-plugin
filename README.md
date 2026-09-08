# @jengo/vite

A Vite plugin designed for seamless integration with the Jengo CodeIgniter 4 framework, featuring automatic entrypoint discovery and dynamic configuration.

Documentation: https://lipex-org.github.io/jengophp.com/packages/vite-plugin

## Installation

```bash
npm install @jengo/vite --save-dev
```

## Quick Start

```javascript
// vite.config.js
import { defineConfig } from 'vite';
import jengo from '@jengo/vite';

export default defineConfig({
    plugins: [
        jengo(),
    ],
});
```

## Documentation

For full guides on dynamic entrypoint conventions, manifest generation, and asset tags injection in CodeIgniter views, visit https://lipex-org.github.io/jengophp.com/packages/vite-plugin.

## License

Released under the MIT License.
