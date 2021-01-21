# svelte-gradient-typography

![sample gradient text](https://github.com/thetrisatria/svelte-gradient-typography/blob/main/misc/sample.jpg?raw=true)

Gradient typography for [Svelte](https://svelte.dev) inspired by Apple's HomePod Mini landing page

## Get started

### Installation
```sh
npm install svelte-gradient-typography
```

### Usage
First you need to import it on the script section
```js
// ...
	import GradientText from 'svelte-gradient-typography';
// ...
```
then, for basic use (with default style) apply:
```html
    <GradientText>Lorem Ipsum</GradientText>
```

### Customization
To change the font size, add size property as follow
```html
    <GradientText size="100px">
      Lorem Ipsum in Pixel
    </GradientText>
```

To change the default gradient:
```html
    <GradientText 
      gradient="linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);">
      Lorem Ipsum Blue Gradient
    </GradientText>
```
And if you want to customize even further, just add CSS style:
```html
    <GradientText 
      style="font-weight:500;line-height:1.2;text-align:center">
      Lorem Ipsum with Custom CSS
    </GradientText>
```
