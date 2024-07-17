# Nuxt 3 + Storybook 8 Template

This is a template repository for setting up a Nuxt 3 project with Storybook 8. This setup aims to streamline the integration of Storybook for building and documenting UI components in a Nuxt 3 application.

## Features

- Nuxt 3 for modern web development
- Storybook 8 for developing and testing UI components
- Essential Storybook addons included for better development experience

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

#### Nuxt Development Server

Start the Nuxt development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`.

#### Storybook

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
- `@nuxtjs/storybook`: ^8.1.5

### Dev Dependencies

- `@storybook/vue3`: ^8.2.4
- `@storybook/vue3-vite`: ^8.2.4
- `@storybook/addon-essentials`: ^8.2.4
- `@storybook/addon-interactions`: ^8.2.4
- `@storybook/addon-links`: ^8.2.4
- `@storybook/addon-onboarding`: ^8.2.4
- `@storybook/blocks`: ^8.2.4
- `@storybook/test`: ^8.2.4
- `@chromatic-com/storybook`: ^1.6.1
- `@vitejs/plugin-vue`: ^5.0.5
- `vite`: ^5.3.4

## Scripts

- `dev`: Start the Nuxt development server
- `build`: Build the Nuxt application
- `generate`: Generate static files for the Nuxt application
- `preview`: Preview the production build
- `storybook`: Start the Storybook development server
- `build-storybook`: Build the Storybook static files

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

```

```
