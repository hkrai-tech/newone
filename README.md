# (Instructions) Delete This

1. npm init -y   -- it will give us a  package.json
npm i tailwindcss   -- it'll install tailwind css

----------------------------------------------------------

create a folder and name it   src
inside a folder create a file, and name it style.css
and inside style.css paste the following
add tailwind to css


@tailwind base;

@tailwind components;

@tailwind utilities;

------------------------------------------------------------

create another  folder and name it public
inside public folder create two file,
index.html and style.css

------------------------------------------------------------

edit package.json

  "scripts": {
    "build:css": "tailwind build src/style.css -o public/style.css"
  },

after that paste that command in terminal

npm run build:css 


--------------------------------------------------------------

BOOM 
Now you're done to go  :)
to ease your developement you can try 
tailblocks, tailwindcomponents and so many stuffs

