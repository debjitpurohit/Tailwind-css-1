# Normally we can use Tailwind css by adding <script src="https://cdn.tailwindcss.com"></script> in head tag
# but if we want to use Tailwind in Production the
# https://tailwindcss.com/docs/installation/using-postcss
# 1>    npm init --y
# 2>  npm install -D tailwindcss postcss autoprefixer
# 3>    npm i vite
# 4>    add scripts and type "start" :"vite" within it
# 5>    npx tailwindcss init
# 6>   add * within content of tailwind.config.css
# 7>   add a file (postcss.config.js) and add some lines ~
module.exports = {
    plugins: {
      tailwindcss: {},
      autoprefixer: {},
    }
  }
# 8>     create main.css and add 
@tailwind base;
@tailwind components;
@tailwind utilities;
      
# 9>    add main.css in html by link:css method     




# 10>    npm run start
