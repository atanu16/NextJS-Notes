# Notes-codn


<h3>NextJs </h3>
<h6>1.npx create-next-app@latest --typescript <br>
2.cd my-project <br>
3.npm run dev</h6> 


<h3>Install Tailwind CSS with Next.js</h3>

<h4>Install Tailwind CSS:</h4>

<h6>npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init -p</h6>

<h4>Configure your template paths:<h4>
content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],

    <h4>Add the Tailwind directives to your globals.css CSS</h4>
    
 <h6>@tailwind base;
@tailwind components;
@tailwind utilities; <h6>
