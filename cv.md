# Ekaterina Kuzina

> Email: katya.cuzina2011@yandex.ru   
> Phone: +7(981)9613140   
> Telegram: KitKate96   
> Linkedin: https://www.linkedin.com/in/ekaterina-kuzina-8347a31bb/  
> Vk: https://vk.com/id43349982   
> GitHub : https://github.com/Ekaterina-Kuzina

### About me
***
Development for me is possibility to improve myself every day, interesting tasks that are worth breaking head over, the opportunity to make life easier for users, communicate with interesting people, the option to learn English ;) 
That's why I am big fan of development.

My path began with courses in web design, due to this I learned about layout and  in the future about web development. After the magic of the code turned into  landing pages and applications, my choice was obvious!

I graduated from St. Petersburg University (bachelor's and master's degrees) with a degree in chemical engineer. During my graduate studies, I was a participant in the "Work and Travel" program and lived in America for 6 months.

I worked as a chemical engineer about a year. The understanding that the specialty is interesting, but not mine, came during the learning process. During my last year in university and working like a chemical engineer i was totally obsessed with development and spend all my free time for that . 

I'm totaly sure that frontent development is my goal and I do my best!!! 
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

### Education
*** 

| Period        | University / couse |
| ------------- | -------------------|
| 2014-2018     | Saint-Petersburg State Institute of Technology (Faculty: Chemical and biotechnology) |
| 2018-2020     | Saint-Petersburg State Institute of Technology (Faculty: Chemistry of substances and materials)(masters degree) |
| 2019-2020     | Udemy courses 'Web-developer', 'JavaScript - developer', self studying by youTube, docs and etc  |
| 2021          | Yandex course(React-developer), RSSchool course |

### Languages
***

- English B1 (I was participate of work and travel program. I lived in America for 6 months)
- German A1