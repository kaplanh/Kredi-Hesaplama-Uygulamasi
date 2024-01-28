# DOM Example

![DOM example](https://github.com/kaplanh/Dom-Example/assets/101884444/6daeae24-55bd-47e2-adb3-85c89d9af223)


[Click Me!](https://kaplanh.github.io/Dom-Example/)

## Description

The project aims to create a DOM Example using JS and Bootstrap.

## Problem Statement

- Your company has recently started on a project that aims to create a Languages Application. So you and your colleagues have started to work on the project.

## Project Skeleton 

```
Monthly Expense Tracking Application (folder)
|
|----readme.md                        
|----index.html  
|----style.css
|----app.js
``` 


### At the end of the project, following topics are to be covered;

- HTML
   ```
   - for Bootstrap cdnjs link & script
    <link
            href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
            rel="stylesheet"
            integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM"
            crossorigin="anonymous"
        />
   <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2"
      crossorigin="anonymous"
    ></script>
   
   ```
 
- CSS
  
-Bootstrap
 - Bootstrap flex
 - Bootstrap btn
 - Bootstrap text
  
  
- JS
  - DOM Manipulations
    - createElement()
      ```
      const ul = document.createElement("ul")
      ```
    - appendChild()
      ```
      dilSection.appendChild(ul);
      ```
    - closest()
      ```
      const h1 = ul.closest(".container").firstElementChild
      const buttons = ul.closest(".container").querySelectorAll(".btn")
      ```
      
      ```
      ```
     
  - DOM Selectors
    
    ```
     const dilInput = document.querySelector(".diller");
     const silBtn = document.getElementById("sil");
     const buttons = document.querySelectorAll(".btn");
    
    ```
  - Events
    - click
    - keydown
    - load 
    ```
    silBtn.onclick = function () {
    ul.childElementCount > 0
        ? ul.removeChild(ul.lastElementChild)
        : alert("Silinecek dil kalmadi");
    };
    
    dilInput.addEventListener("keydown", (e) => {
    // console.log(e);
    if (e.keyCode === 13) {
        ekleBtn.onclick();
    }
    // if (e.code === 'Enter') {
    //   ekleBtn.onclick();
    // }
    if (e.code === "Delete") {
        silBtn.onclick();
    }
    });

    window.onload = () => {
    javascriptKontrol();
    dilInput.focus();
    };
    
    ```
  - Builtin functions
     - preventDefault()
     - reset()
     - remove()  
  - if else - if - else conditions
  - Ternary & removeChild()
      ```
      silBtn.onclick = function () {
    ul.childElementCount > 0
        ? ul.removeChild(ul.lastElementChild)
        : alert("Silinecek dil kalmadi");
                                 };
      ```

  - Array Methods( forEach() ) & setAtribute()
   ```
    const javascriptKontrol = () => {
    document.querySelectorAll("ul li").forEach((dil) => {
        const kucukHarf = dil.textContent.toLowerCase();
        if (kucukHarf === "javascript") {
            // dil.className = 'red';
            //?Alternatif yöntem
            dil.setAttribute("class", "red");
        }
    });
                                 };
 ```

    

### At the end of the project, developers will be able to;

- improve coding skills within HTML, CSS and JS 

- use git commands (push, pull, commit, add etc.) and Github as a Version Control System.


## Notes

- You can use HTML, CSS, Bootstrap and JS to complete this project.



<p align="center"> ⌛<strong> Happy Coding </strong> ✍ </p>


