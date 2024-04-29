# Image gallery

> A simple movie poster project.

## Table of contents

- [Image gallery](#image-gallery)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Status](#status)
  - [Contact](#contact)

## General info

> The objective of the project is to practice separation of concern in
> JavaScript.

## Screenshots

![Example screenshot](./assets/ss.png)

## Technologies

- JavaScript
- HTML5
- CSS3
- VSC code

## Setup

Clone the repo and run `npm install`

## Code Examples

```js
const filterImagesHandler = (value) => {
	const images = document.querySelectorAll('.image-box');
	images.forEach((img) => {
		const title = img.querySelector('h6').innerText;
		if (title.toLowerCase().includes(value.toLowerCase())) {
			img.classList.remove('hidden');
		} else {
			img.classList.add('hidden');
		}
	});
};
```

## Status

Project is: _done_

## Contact

[Gultekin Birol](https://github.com/gultekinbirol)
