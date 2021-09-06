# Ekaterina Kuzina

> Email: katya.cuzina2011@yandex.ru   
> Phone: +7(981)9613140   
> Telegram: KitKate96   
> Linkedin: https://www.linkedin.com/in/ekaterina-kuzina-8347a31bb/  
> Vk: https://vk.com/id43349982

### About me
***
Development for me is possibility to improve myself every day, interesting tasks that are worth breaking head over, the opportunity to make life easier for users, communicate with interesting people, the option to learn English ;) 
That's why I am big fan of development.
### Skills
***
- HTML(HTML5)
- CSS(CSS3)
- Sass
- JavaScript
- Git/GitHub
- Bootstrap
- Adobe Photoshop
- Figma

### Code
***

``` 
export let textLettersArr;
export let spans;

export function getRandomInt(max) {
    return Math.floor(Math.random() * max);
}

export function getData(url) {
    fetch(url)
        .then(data => data.json())
        .then(result => {
            textLettersArr = result[getRandomInt(result.length)].text.split('');
            createSpan(textLettersArr);
            spans = document.querySelectorAll('span');
        });
}

export function createSpan(textLettersArr) {
    textLettersArr.forEach(item => {
        const span = document.createElement("span");
        const wrapperContent = document.querySelector('.wrapper-content');
        span.innerHTML = `${item}`;
        wrapperContent.appendChild(span);
    });
}
```
