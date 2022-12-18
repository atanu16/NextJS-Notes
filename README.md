# NextJS-Notes


<h3>NextJs </h3>
     
      npx create-next-app@latest --typescript
      cd my-project
      npm run dev

<h5>Create page<h5>
     
     tsrfc

<h3>Install Tailwind CSS with Next.js</h3>
     
      npm install -D tailwindcss postcss autoprefixer
      npx tailwindcss init -p

<h4><h4>
content: [<br>
    "./pages/**/*.{js,ts,jsx,tsx}",<br>
    "./components/**/*.{js,ts,jsx,tsx}",<br>
  ],
    
 <h6>@tailwind base;<br>
@tailwind components;<br>
@tailwind utilities; <h6>

     
<h3>Install Framer Motion CSS with Next.js</h3>
  
    npm install framer-motion 
 <h5>Step-2<h5>
      
    import { motion } from "framer-motion";
     
<h3> Install sanity </h3>
     
      npm install -g @sanity/cli 
      sanity init --coupon sonny2022

        
<h3> Install SocialIcon </h3>
      
      npm install react-social-icons
<h6> Import</h6>
      
      import React from 'react';
      import ReactDOM from 'react-dom';
      import { SocialIcon } from 'react-social-icons';
      ReactDOM.render(<SocialIcon url="https://twitter.com/jaketrent" />, document.body);
      
