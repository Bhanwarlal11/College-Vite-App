# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

**Folder Creation**
- open desktop to powershell/cmd
- npm create vite@latest
- edusity
- React
- Javascript

**open educity folder in vscode**
- npm install --- for instal node modules
- npm run dev --- for open live link

**remove files**
- remove all image & svg
- remove App.css
- clear code from App.jsx file
- clear code from Index.css

**color: inherit**
- it is css property.
- it is inherits (pick) color of specific tag

**font used in this project**
- outfit font is used --->> paste into the index.css file

**how to use top,bottom,left,right**
- you need to use first position , then you can use all of these
```
position: fixed;
top: 0;
left: 0;
```

**if you want use image as an backgroud**
- in css file
- the use :
```background : url(../../assets/hero.png) ```
- if you want add any overlay on the background image than use it
``` backgroud : linear-gradient(rgba(8,0,58,0.7),rgba(8,0,58,0.7)) , background : url(../../assets/hero.png) ```

**if you want to add any image in jsx file**
- so , firsly import this image 
- then , use it in your project


**opacity**
- opacity range is 0 to 1
- 0 means - not visible
- 1 means - 100% visible
- majorly this is use in hover effect

**here we are using Title.jsx as usable component**
- because it has multiple useCases
- so, for the changing content
- we will use props


**how to center a element over any image**
```
.play-icon{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}
```


**window.scroll**
-❓

**.btn.dark-btn**
- this means, CSS property applicable only those classes which contains both(btn & dark-btn) classes

**Transform:translate()**
- read about transform & translate CSS Property