<div align="center">

# ◦ ◦ ◦

# **WrapKit**

_Beautifully crafted React components_  
_Inspired by Human Interface Guidelines_

◦ ◦ ◦

</div>

## Designed for those who appreciate beautiful interfaces

Welcome to **WrapKit** - a modern React component library built with TypeScript, Vite, and Storybook. This library provides reusable UI components designed for scalability, accessibility, and developer experience.

### 🚀 Features

- **TypeScript** - Full type safety and excellent developer experience
- **Storybook** - Interactive component documentation and testing
- **Vite** - Lightning-fast development and build process
- **Modular Architecture** - Each component lives in its own folder with stories and styles
- **Accessibility First** - Components built with a11y best practices

### 📦 Components

- **Button** - Primary UI component for user interactions
- **Header** - Navigation header with user authentication states
- **Page** - Full page layout component

### 🛠️ Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Start Storybook
npm run storybook

# Build for production
npm run build
```

### 📁 Project Structure

```
src/
├── components/
│   ├── Button/
│   │   ├── Button.tsx
│   │   ├── Button.css
│   │   ├── Button.stories.ts
│   │   └── index.ts
│   ├── Header/
│   └── Page/
└── docs/
```

### 🎯 Getting Started

Each component is designed to be used independently. Import what you need:

```tsx
import { Button, Header } from "./components";

function App() {
  return (
    <div>
      <Header />
      <Button primary label="Get Started" />
    </div>
  );
}
```

---

Built using React + TypeScript + Vite
