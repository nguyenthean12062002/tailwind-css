# tailwind-css
Tailwind Css


Import tailwind css in React Js
	npm install -D tailwindcss
npx tailwindcss init


config 
	/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
Mode : “jit”,
  theme: {
    extend: {},
  },
  plugins: [],
// tự động watch lại tailwind khi config lại nó
purge: [
    "./src/**/*.html",
    "./src/**/*.js",
    "./src/App.css",
    // Thêm đường dẫn tới các tệp tin CSS của bạn nếu cần thiết
  ],
}


Import  {
@tailwind base;
@tailwind components;
@tailwind utilities;
}
![Uploading image.png…]()
