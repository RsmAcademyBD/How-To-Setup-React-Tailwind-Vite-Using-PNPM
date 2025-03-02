# Setup React & Tailwind & Vite Using PNPM
Presenting brand new Article: In this article you will learn how to set up tailwind css with create-react-app using pnpm. Just follow the steps in the Article. More article about Android Application And Web Development will uploaded so get in touch with the channel. So you are no more far. You can be developer.

![image](https://github.com/user-attachments/assets/cd2fd433-db58-46a4-8808-074fae20de29)

## 1. Install pnpm and create a new react project
```bash
pnpm create vite my-project
-----------and press enter---------

Then follow next commands ....
Select - React
-----------and press enter---------

Select - JavaScript + SWC
-----------and press enter---------

cd my-project
```
## 2. Install node_modules
```bash
pnpm i
```
## 3. Install Tailwind CSS
```bash
pnpm install tailwindcss @tailwindcss/vite
```
## 5. Configure your Vite plugin

- Add the @tailwindcss/vite plugin to your Vite configuration.
```jsx
import { defineConfig } from "vite";
import react from "@vitejs/plugin-react-swc";
import tailwindcss from "@tailwindcss/vite";

// https://vite.dev/config/
export default defineConfig({
  plugins: [react(), tailwindcss()],
});


```
## 5. Add the Tailwind directives to your CSS

- Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```jsx
@import "tailwindcss";
```

## 6. Start your build process

- Run your build process with npm run start.

```bash
pnpm dev
```
