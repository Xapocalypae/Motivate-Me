# Motivate-Me



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Key Features](#key-features)
* [Built With](#built-with)
* [Getting Started](#getting-started)
* [Tweaking](#tweaking)
* [License](#license)
* [Contact](#contact)

<!-- ABOUT THE PROJECT -->
## About The Project

Motivate-Me v1.0 is a weekly timer and motivation WebApp 

![preview](img/preview.PNG)

`Xapocalypae`, `Motivate-Me`, `@xapo_amv`, `business@boostingace.com`

### Key Features
* Daily Changing quotes
* Changing backgrounds on refresh
* Timer automatically resets after the weekend is passed and countsdown till next weekend

### Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JAVASCRIPT](https://www.javascript.com/)
* [PIXABAY API](https://pixabay.com/service/about/api/)

## Getting Started

To get a local copy up and running follow these simple steps.

1. Extract the downloaded zip file in a folder
2. Open bg.js in your editor
3. Enter your Pixabay API key in < YOUR API KEY >
```js
var apiUrl= `https://pixabay.com/api/?key=<YOUR API KEY>&q=<CATEGORY>&orientation=horizontal&min_width=1920&min_height=1080&page=${randomNumber(1,26)}`;
```
 4.Save bg.js and open index.html
 5. I have used fontawesome for icons so make sure you have pasted the folder in your code directory. 

## Tweaking

* To change the category of backgrounds open bg.js

```js
var apiUrl= `https://pixabay.com/api/?key=<YOUR API KEY>&q=<CATEGORY>&orientation=horizontal&min_width=1920&min_height=1080&page=${randomNumber(1,26)}`;
```
* Enter your Pixabay API key in < YOUR API KEY >
  
```js
var apiUrl= `https://pixabay.com/api/?key=<YOUR API KEY>&q=<CATEGORY>&orientation=horizontal&min_width=1920&min_height=1080&page=${randomNumber(1,26)}`;
```
* Enter the category of backgounds you want in < CATEGORY > (e.g. Animals, Cars, City, etc)

```js
var apiUrl= `https://pixabay.com/api/?key=<YOUR API KEY>&q=<CATEGORY>&orientation=horizontal&min_width=1920&min_height=1080&page=${randomNumber(1,26)}`;
```


## License

Distributed under the MIT License. See `LICENSE` for more information.


## Contact

Email: business@boostingace.com
