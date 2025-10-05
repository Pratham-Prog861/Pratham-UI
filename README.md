# 🚀 Pratham UI

A modern, lightweight React component library built with TypeScript and TailwindCSS. Pratham UI provides essential components for building clean, consistent user interfaces.

![Pratham UI](https://img.shields.io/badge/Pratham-UI-blue)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.2-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.3-blue)
![Storybook](https://img.shields.io/badge/Storybook-7.6-ff69b4)

## ✨ Features

- 📦 **Modern Stack**: Built with React 18, TypeScript, and Vite
- 🎨 **Customizable**: Styled with TailwindCSS and class-variance-authority
- 📚 **Interactive Documentation**: Component playground with Storybook
- 🧩 **Modular Components**: Consistent API across all components
- 🔍 **Type Safety**: Full TypeScript support

## 📋 Components

- **Button**: Customizable buttons with different variants, sizes, and color schemes
- **Input**: Form input components with validation states
- **Text**: Typography components for consistent text styling
- **Layout**: Flexible layout components (Box, Stack)

## 🚀 Getting Started

### Installation

```bash
npm install pratham-ui
# or
yarn add pratham-ui
```

### Usage

```jsx
import { Button, Input, Stack } from 'pratham-ui';

function App() {
  return (
    <Stack spacing="md">
      <Input placeholder="Enter your name" />
      <Button>Submit</Button>
    </Stack>
  );
}
```

## 📖 Documentation

Run Storybook locally to view interactive component documentation:

```bash
npm run storybook
# or
yarn storybook
```

## 🛠️ Development

### Prerequisites

- Node.js (v16+)
- npm or yarn

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```
3. Start Storybook:
   ```bash
   npm run storybook
   # or
   yarn storybook
   ```

### Building

```bash
npm run build
# or
yarn build
```

---

Made with ❤️ by Pratham
