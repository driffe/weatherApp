# Weather App

## Demo
[Check out the demo here](https://weather-app-eight-fawn-99.vercel.app/)

## About the Project

This is a simple weather app utilizing Progressive Web Application (PWA) principles and the OpenWeatherMap API. Feel free to download and use it.

### Built With

* ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
* ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
* ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
* ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Next.js
```sh
  npx create-next-app@latest
```
Check **No** except Tailwind CSS
If you didn't see Tailwind CSS select, follow this instruction.

* Tailwind Css
```sh
  npm install -D tailwindcss postcss autoprefixer
  npx tailwindcss init -p
```
Add the paths to all of your template files in your tailwind.config.js file.
```sh
  module.exports = {
    content: [
      "./app/**/*.{js,ts,jsx,tsx,mdx}",
      "./pages/**/*.{js,ts,jsx,tsx,mdx}",
      "./components/**/*.{js,ts,jsx,tsx,mdx}",
   
      // Or if using `src` directory:
      "./src/**/*.{js,ts,jsx,tsx,mdx}",
    ],
    theme: {
      extend: {},
    },
    plugins: [],
  }
```
Add the @tailwind directives for each of Tailwind’s layers to your globals.css file.
```sh
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```
You can run your build process with
```sh
  npm run dev
```
And stop your build process with ***Ctrl C***.
* React-icons
```sh
  npm install react-icons --save
```
Example
```sh
  import { FaBeer } from 'react-icons/fa';
  
  class Question extends React.Component {
    render() {
      return <h3> Lets go for a <FaBeer />? </h3>
    }
  }
```

