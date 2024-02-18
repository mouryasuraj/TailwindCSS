# Tailwindcss by [Hitesh Choudhary](https://hiteshchoudhary.com/)

## Setup

### 1. Install

```bash
    npm install -D tailwindcss
    npx taiwindcss init
```

### 2. After initializing tailwindcss, It will create tailwind.config.js file. Put the below code in this file.

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### 3. Create src/input.css file inside src directory and put below code inside it.

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 4. Run the command and then it will create output.css in src folder and then check whether css working or not in index.html file.

```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```


## Things learned

