### Tailwind instalation and Environment setup
```
npm init -y
npm install -D tailwincss
npx tailwindcss init
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch //build
npm run build
```
Different Between Bootstrap and Tailwind
- bootstrap component approach freamwork
- Tailwind utility-frist approach freamwork

### Dark Mode Setup
- if selected Media it apply when user is applying his pc theme dark otherwise it no wil be applied
- if selected class when user want active dark mode usieng a button 

### @layer
//if i makeing component for my style then i apply it under below.I also use class out of my style component in html 
- @layer components{
  .class-name{
    @apply style.....
  }
}


// change Tailwind Default style if I want
- @layer base{
  h1{
    @apply text-2xl
  }
}
// my makeing class were it use and chnage tailwind deafult style for tailwinds class
- @layer utility{
  .text-body{
    font-size : 10px;
  }

}
