# websit
Websit is chatgpt plugin hub web project.

## Environmental Dependence
**node 12+**, **vite 2+**

## Deployment steps
**npm i**
**npm run dev**

## 目录结构描述

│  .gitignore				git profile
│  LICENSE 					Open source certification
│  package-lock.json
│  package.json
│  README.md				DESCRIPTION
│  vite.config.js 			vite profile
├─node_modules
├─public
│      favicon.ico
└─src
    │  App.vue
    │  main.js
    │  index.css
    │
    ├─plugins			    api Management module
    │  │ request.js		    api Manage Entry Files
    │  └─modules		    api Module management
    │          home	        Module file
    │
    ├─assets				Static files
    │      logo.png
    │
    ├─components			Public component directory
    │
    ├─router 				router directory
    │      index.js
    │
    ├─store 				vuex directory
    │  │  index.js
    │  
    │
    └─views
        └─home
            │─ components   private component directory
            
        index.vue 

## build
**node run build**     