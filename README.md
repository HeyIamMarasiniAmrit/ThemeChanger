# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:


- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- # themechanger

A small React theme switcher using the **Context API**.  
Easily add light/dark theming to your React app with a `ThemeProvider` and a simple `useTheme()` hook. Preference is persisted to `localStorage`.

<img width="1855" height="1017" alt="Image" src="https://github.com/user-attachments/assets/1ee5635d-5538-4a21-9a60-cd0698d08381" />

## Features

- Light / Dark theme toggle
- Persists user preference in `localStorage`
- `ThemeProvider` + `useTheme()` hook for easy integration
- CSS variables friendly — simple to customize
- Minimal, production-ready code

---

## Installation

```bash
# clone
git clone https://github.com/themechanger.git
cd themechanger

# install
npm install



## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
