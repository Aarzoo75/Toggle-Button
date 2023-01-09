# Animated Toggle Switch
This is a simple toggle switch animation created using HTML and CSS. It can be used as an on/off button or as a switch to toggle between two different options.

## Features
* Pure HTML and CSS
* Smooth animation on toggle
* Customizable colors and sizes

## How to use
1. Download the `style.css` file and include it in your HTML file using a `link` tag.
2. Add the `.checkbox` class to a `div` element.
3. Inside the `div`, add two `label` elements with the class `checkbox`. These will be the labels for the two options.
4. Add an `input` element with the id `i` and set the `type` attribute to `checkbox`. This will be the actual toggle switch.
5. Customize the colors and sizes by modifying the CSS variables in the `style.css` file.

## Example
```HTML
		<input type="checkbox" id="i">
	
		<label for="i" class="checkbox">
			<div class="checkbox__inner">
				<div class="green__ball"></div>
			</div>
		</label>
		<div class="checkbox__text">
			<span>turned</span>
			<div class="checkbox__text--options">
				<span class="off">off</span>
				<span class="on">on</span>
			</div>
		</div>
```

## Demo
A demo of the toggle switch can be found [here](https://twitter.com/Aarzoo75/status/1582244041349279744).
