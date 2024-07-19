# Nuxt 3 + Storybook 8 Template

This is a template repository for setting up a Nuxt 3 project with Storybook 8. This setup aims to streamline the integration of Storybook for building and documenting UI components in a Nuxt 3 application.

## Known Issues

You may encounter the following warning:

```
 WARN  Using vite.config.js is not supported together with Nuxt. Use options.vite instead. You can read more in https://nuxt.com/docs/api/nuxt-config#vite.
```

This warning suggests that using `vite.config.js` is not supported with Nuxt and advises to use `options.vite` in `nuxt.config.js`. However, when migrating the Vite configuration to `nuxt.config.js`, Storybook fails to start and throws errors. If you have any solutions to this issue, please share them.

wariningがでますが、vite.config.jsの設定をnuxt.config.jsに移すと、storybookがエラーを起こして起動できない。解決法わかる方いたら教えてください


## Features

- Nuxt 3 for modern web development
- Storybook 8 for developing and testing UI components

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/shomtsm/nuxt3-storybook.git
cd nuxt3-storybook
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

### Running the Application

#### Nuxt Development Server With Storybook

Start the Nuxt development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`.
At the same time, the Storybook will be available at `http://localhost:6006`.

#### Storybook Only

Start the Storybook development server:

```bash
npm run storybook
# or
yarn storybook
```

The Storybook will be available at `http://localhost:6006`.

### Building for Production

#### Nuxt

Build the Nuxt application for production:

```bash
npm run build
# or
yarn build
```

Generate static files:

```bash
npm run generate
# or
yarn generate
```

Preview the production build:

```bash
npm run preview
# or
yarn preview
```

#### Storybook

Build the Storybook static files:

```bash
npm run build-storybook
# or
yarn build-storybook
```

## Project Structure

- `nuxt.config.js`: Nuxt configuration file
- `.storybook`: Storybook configuration directory
- `stories`: Directory for Vue components with stories

## Dependencies

### Main Dependencies

- `nuxt`: ^3.12.3
- `vue`: latest

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
