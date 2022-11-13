# Normally we can use Tailwind css by adding <script src="https://cdn.tailwindcss.com"></script> in head tag
# but if we want to use Tailwind in Production make sure your html named as index.html
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


# { npx tailwindcss init confdebu --full } for customization of tailwind.config.js file and add your own css as a object in the tailwind.config.js file tobe direct theme e nh extended e dite hbe thle overwrite hbe nah but {screen} add korte hole direct theme e diye overwrite krte hbe 
#   add "build":  "vite build" in scripts of package.json for build then run { npm run build } that form a file named as dist where u can find your html and ready made css
