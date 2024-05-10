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

**web3forms**

**What is event.preventDefault()**
- 

**how to add scroot features in <Header/>**
- so we use React Scoll (npm)
```
<Link activeClass="active"
      to="target"
      spy={true}
      smooth={true}
      hashSpy={true}
      offset={50}
      duration={500}
      delay={1000}
      isDynamic={true}
      onSetActive={this.handleSetActive}
      onSetInactive={this.handleSetInactive}
      ignoreCancelEvents={false}
      spyThrottle={500}
>
  Your name
</Link>
```
- if you use any" link to='footer'" then you need to specify{name='footer' OR|||| id='footer'}
- if you give unique classname of each container , then you dont need to specify 'id or name'


**how to complete view while clicked to link tag**
- so , you adjust offset in link tag

**you can use{ order:2} for adjust element in css while using media queries*

**Now we have completed our university project**
**upload this website**
- first, create dist folder 
- using - `npm run build`
- dist folder contains - index.html & assets folder
- you need to upload only `Dist folder`

`https://bhanwarlal11.github.io/College-Vite-App/`