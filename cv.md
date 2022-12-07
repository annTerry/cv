# Anna Kniazeva
![foto](foto_m.jpg)

## Contact information
* __Location:__ Saint-Petersburg, Russia
* __E-mail:__ alattery@gmail.com
* __Telegram:__ @annaKn
* __GitHub:__ [annTerry](https://github.com/annTerry)
* __LinkedIn:__ [Anna Kniazeva](https://www.linkedin.com/in/anna-kniazeva-23b732234/)

## About Me:
Web-developer since 2002 year. I have much experience with JavaScript from ES3 to ES6. I have been codding  on Perl, PHP, Java etc. Now I'm learning Node.JS. I like old projects, foreign and legacy code and control both and FrontEnd and BackEnd. But if I must choice, I'll prefer FrontEnd. I have been programming from my childhood, and now have more then 15 years of experience in codding on different languages, adding new features and fixing bugs in dozens of applications. I'd want to be useful in improve quality and functionality of applications in modern company.

***
## Skills:
* HTML
* CSS, SCSS
* JavaScript, Typescript  
* Java Basics (jsp, velocity, vaadin, JSON processing, Android Apps)
* Node.JS Basics
* Python Basics
* PHP, Perl, MySQL
* Webpack
* IntelliJ IDEA, VSCode
* Adobe Photoshop, Adobe Premiere

## Code example:
```
class BlockedCheckbox{
  element = document.getElementById('blocking_checkbox');
  constructor() {
    if (this.element) {
      this.element.addEventListener('change', () => {
        let changeEvent = new Event('dataChanged');
        this.element.dispatchEvent(changeEvent);
      })
    }
  }
  elementValue()
  {
    return this.element.checked ? "false" : "true";
  }
}

export {BlockedCheckbox}
```