# How to install and configure Tailwindcss in React App

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react" />
    <img src="https://skillicons.dev/icons?i=vite" />
    <img src="https://skillicons.dev/icons?i=tailwindcss" />
  </a>
</p>
Quick setup how to install tailwindcss freamwork in your project. I will show you how to install Tailwindcss step-by-step. If i encounter problems i will put code with solution down below so that I know how to solve it next time...



## Create React Project
This command create new React project in existing folder. If you want to create new folder in put "project-name" instead "."
```bash
npx create-react-app .
```
If you create new folder use this command to go inside project folder
```bash
cd "project-name"
```
## Install and init Tailwindcss
Install Tailwindcss via npm
```bash
npm install -D tailwindcss
```
Init Tailwindcss
```bash
npx tailwindcss init
```
## Install nmp 
Install nmp in your Project
```bash
npm install
```
## Configure your template paths
Add this code in your 'tailwind.config.js' file 
```bash
/** @type {import('tailwindcss').Config} */
module.exports = {
content: [
  "./src/**/*.{js,jsx,ts,tsx}",
],
theme: {
  extend: {},
},
plugins: [],
}
```
## Add the Tailwind directives to your CSS
Add this code into 'index.css' file
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
## Run your App
Run your build process with npm run start.
```bash
npm run start
```
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vite" />
  </a>
</p>
## Create app via Vite
Same situation as above new folder use "project name" instead "."
```bash
npm create vite@latest . -- --template react
```
## Install Tailwindcss via Vite
Install Tailwindcss
```bash
npm install -D tailwindcss postcss autoprefixer
```
Init Tailwindcss
```bash
npx tailwindcss init -p
```



## Errors and how to solve them
No errors yet



