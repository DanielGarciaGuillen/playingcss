# Project Title

This is a controler to adjust Css properties based on the 30 days Javascript challenge.

## Getting Started

Use the controler to modify the Css code.

## Demo

## [Css Controler](https://danielgarciaguillen.github.io/playingcss/)
![Css Controler](/image/playingcss.png?raw=true "CssClock")


## Learnings

* Use of CSS variables with :root
* Use the CSS variables and pass them to css elements with `var(--spacing)`
* Get all the control inputs with `const inputs = document.querySelectorAll('.controls input')`
* Add event listeners to all the inputs with `inputs.forEach(input => input.addEventListener('change', handleUpdate))`
* Use dataset.sizing to access the data class on html and modify it.
* Adjust CSS variable with `document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix)`

## Built With

* Vanilla Javascript
* Css
* Html

