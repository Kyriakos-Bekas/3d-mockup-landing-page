# Revolut 3D Mockup Animation

## Project Overview

In this project, I created a simple landing page for the **Revolut** mobile app.

The main focus on this project is the mockup of the app's UI, which gains a 3D perspective with layering on hover (on click for mobile).

For smalle viewports, the mockup also scales down, so that it fits nicely in the screen without having to use the `overflow: hidden;` CSS property.

## Code Structure

For this project I used HTML and CSS only.

### HTML

Correct use of semantic HTML5 elements, that signify the role that each piece has on the page.

### CSS

For achieving the 3D effect, I made use of the `transform-style: preserve-3d;` property on the elements that I wanted to animate on hover. This propert will allow the element to be rendered in 3D space.

In addition to that, after rotating the element on the X, Y and Z axis, we use the `perspective()` function. This function gives perspective to a 3D-positioned element. The perspective property defines how far the object is away from the user. So, a lower value will result in a more intensive 3D effect than a higher value.

In my example, `perspective(1000px)`, it is as if the element is placed _1000px_ away from the viewer.

The project is also completely **responsive**.

## View Project

1. View the live project by clicking [here](https://3d-mockup-landing-page.netlify.app/).

2. Clone the repository

```bash
git clone https://github.com/Kyriakos-Bekas/3d-mockup-landing-page.git
```

3. Download the source code: _Code_ >> _Download ZIP_

![Download Code as ZIP Visual Instructions](https://user-images.githubusercontent.com/74660002/152875739-5b6a15f1-afcd-49b7-b0d9-2d37ce6df56c.png)

## Credit Note

No copyright infringement intended. If you see a problem with this repository, please [contact me](mailto:kyriakosbekas00@gmail.com).

Even though I created the layers in Figma from scratch, some assets might be used that I may not own explicitly.

You can use the source code freely. However, it is recommended that you use assets that you own all rights to.

### Shameless Self-Promotion

If you enjoyed this project, consider leaving me a star :star:

Also, you might want to follow me on [Instagram](https://www.instagram.com/kyriakos_web_dev/), [Twitter](https://twitter.com/KyriakosBekas) and [CodePen](https://codepen.io/kyriakosbekas)

Thanks!
