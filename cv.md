# Anzhela Martsinovich

## Contact Info:
* E-mail: anzhela.martsinovich@gmail.com
* GitHub: [https://github.com/AnzhelaMartsinovich](https://github.com/AnzhelaMartsinovich)


## Summary:

*I am a humanitarian who decided to develop in the field of Front-end, because it is a very fascinating and diverse area.*

*At the moment I have knowledge in layout and try to make friends with Java Script)*

*I'm studying at Rolling Scopes school. Studying at this school is very intensive, lecturers give lectures for us 3 times a week, and besides this, we study new material on our own and do various tasks.*

## Skills:

1. HTML, CSS
1. CSS preprocessors: SASS/SCSS, Less
1. Bootstrap 4
1. Version control: Git
1. Methodologies: BEM
1. Pixel perfect
1. Responsive/adaptive design
1. Programming languages: JavaScript basics

## Code examples:

```
const togglePopUp = () => {
	const popup = document.querySelector('.popup'),
		popupBtn = document.querySelectorAll('.popup-btn');

	popupBtn.forEach((elem) => {
		elem.addEventListener('click', () => {
			popup.style.display = 'block';
		});
	});

	popup.addEventListener('click', (event) => {
		let target = event.target;

		if (target.classList.contains('popup-close')) {
			popup.style.display = 'none';
		} else {
			target = target.closest('.popup-content');

			if (!target) {
				popup.style.display = 'none';
			}
		}

	})
};

export default togglePopUp;
```

[Blissmaldives](http://martsinovich-anzhela.ru/blissmaldives/)

[Wedding](http://martsinovich-anzhela.ru/diplom/)

[Good Cardboard](http://martsinovich-anzhela.ru/good_cardboard/)

## Experience/Education:

**Online education**

Glo Academy (courses)

HTML Academy

Codecademy

Codewars

**Glo Academy (work as a mentor)**

**Self-educated**

## English:

Graduated English course February 2018, language level - A2.

I use the site lingualeo.com for reading, learning grammar and listening and Simpler application on my phone for practicing English.