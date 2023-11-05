# Snap Shot [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=See%20this%20react%20example&url=https://yog9.github.io/SnapShot/&hashtags=react,context-api,freecodecamp,developers)

[![Build Status](https://travis-ci.org/Yog9/SnapShot.svg?branch=master)](https://travis-ci.org/Yog9/SnapShot)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HitCount](http://hits.dwyl.com/Yog9/SnapShot.svg)](http://hits.dwyl.com/Yog9/SnapShot)

https://github.com/Yog9/SnapShot

https://es.legacy.reactjs.org/community/examples.html

Cada click en cada palabra y cada busqueda desde el buscador "Search", consultan a la API y solo cambia la variable "tag" en cada llamada. Esta es la llamada que  se hace siempre:   

Ej para tag="malta":

https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=636e1481b4f3c446d26b8eb6ebfe7127&tags=malta&per_page=24&format=json&nojsoncallback=1
![image](https://github.com/alberaja/SnapShot-React-OpenSource/assets/29755489/2cf288da-68e9-4f71-8330-d28202be376e)
![image](https://github.com/alberaja/SnapShot-React-OpenSource/assets/29755489/d6463dbb-3f6c-4503-b1f6-5a87534d6dec)
![image](https://github.com/alberaja/SnapShot-React-OpenSource/assets/29755489/3b40e0ea-932b-4c69-994c-1e506d6ede33)
![image](https://github.com/alberaja/SnapShot-React-OpenSource/assets/29755489/987bc81e-7569-47b3-b1df-1c468c99243e)



[Demo of Snap Shot](https://yog9.github.io/SnapShot/)

![](/snapscout.png)

### Summary

Snap Shot is a gallery created using React,React Hooks, React Router and Context API. The Routes were setup for four default pages and a search page. Also the images were displayed using the Flickr API and axios to fetch data.

### Motivation

The purpose of this project was to get familiar with React Hooks and Context API.

### Getting Started

Click the demo link or clone/download the repository on your local machine.
Create a config.js file in api folder inside src folders. In config.js file write
`export const apiKey = "YOUR_FLIKR_API_KEY";`

##### Install dependencies

`yarn install`

##### Run Snap Shot from the root directory.

`yarn start`

### Built With

- React js
- React Router
- React Hooks
- Context API
- Flickr API

### Features

**1. Responsive Design.**

**2. Search functionality added to search photos from API.**

### Coming Soon

- [ ] Cypress E2E Tests

### Contributing

Everyone is welcomed to contribute to this project. You can contribute either by submitting bugs or suggesting improvements by opening an issue on GitHub. Please see the [CONTRIBUTING](CONTRIBUTING.md) guidelines for more information.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
