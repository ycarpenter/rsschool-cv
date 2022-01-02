# Yurii Muratov
## **Front End Developer**

### CONTACTS

* **Discord:** ycarpenter#4504
* **Email:** yurii.carpenter@gmail.com
* **GitHub:** github.com/ycarpenter
* **LinkedIn:** linkedin.com/in/y-carpenter

### PROFILE
I like to set and achieve difficult goals, to create something new and useful.  Previously, it was organization and launch of restaurants, which included selection of location, marketing, building of the team.

Now I’m progressing in the development of web applications. It is impossible to deny that already now users are making their choice in favor of tools with information updating in real time, rather than statistical software solutions.

### LANGUAGES & TECHNOLOGIES
* HTML5/CSS3
* JavaScript ES6+
* Bootstrap
* SCSS
* BEM
* Grid Layuot
* Flexbox
* Responsive design techniques
* GitHub
* TogglTrack
* MindMeister

### SOFT SKILLS
* Scrum
* Self-management
* Self-starting
* Stress Management
* Positive attitude
* Adaptable

### CODE EXAMPLES

* #### Burger menu

```javascript
const navButton = document.getElementById('navBtn');
const burgerMenu = document.getElementById('nav');
const navMenu = document.getElementById('nav-menu');

function closeMenu() {
  burgerMenu.classList.remove('toggleMenu');
}

navButton.addEventListener('click', () => {
  burgerMenu.classList.toggle('toggleMenu');
});

navMenu.addEventListener('click', event => {
  const target = event.target;
  if (target.classList.contains('nav__link')) {
    closeMenu();
  }
});
```

* #### Using fetch() method

```javascript
async function getJokes() {

  let joke = '';

  const apiUrl = 'https://v2.jokeapi.dev/joke/Programming?blacklistFlags=nsfw,religious,political,racist,sexist,explicit';

  try {
    const response = await fetch(apiUrl);
    const data = await response.json();
    if (data.setup) {
      joke = `${data.setup} ... ${data.delivery}`;
    } else {
      joke = data.joke;
    }

    tellJoke(joke);

    toggleButton();

  } catch (error) {
    console.log('something wrong', error);
  }
}

button.addEventListener('click', getJokes);
```
### PROJECT

#### WEBSITE FOR RESTAURANT

* [Click here to see in the network](https://artandmiss.com.ua)
* [Click here to see source code](https://github.com/ycarpenter/artemiskyiv)

* Bringing mock-ups to life using HTML, CSS, JavaScript
* The site is optimized for the most popular devices
* Validation without errors
* Google Analytics connection
* Uploading to hosting
* Implementation of a form handler using PHP, then sending data to Telegram
* Monitoring website performance and rectifying front-end-related issues

### EDUCATION
> #### [**freeCodeCamp**](https://www.freecodecamp.org)
> ##### 08.2021
> #### JavaScript Algorithms and Data Structures
> [Click here to see certifies](https://www.freecodecamp.org/certification/yurii-mr/javascript-algorithms-and-data-structures)

> #### Books
> #### * You Don't Know JS Yet 1nd Edition.
> ##### 09.2020
> Finished read three books of series (Up & Going, Scope & Closures, this & Object Prototypes) 
> #### * Eloquent JavaScript 3rd edition. (Marijn Haverbeke)
> ##### 12.2020 - current time
> Finished read 8 chapter of book.

### ENGLISH

B1, result from Adaptive English test on [examinator.epam.com](https://examinator.epam.com)

I'm practicing grammar on [English Practice Tests](https://englishtap.blogspot.com/p/english-practice-tests.html)

