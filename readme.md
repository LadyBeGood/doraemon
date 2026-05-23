
<div align="center"> 

# Doraemon

<img src="./preview.png" alt="Doraemon">

*Doraemon, built with pure HTML and CSS.*

[![View Live Demo](https://img.shields.io/badge/LIVE_DEMO_➜-gray?style=for-the-badge)](https://ladybegood.github.io/doraemon/)

</div>

> [!IMPORTANT]
> You will probably run into some sub-pixel rendering issues. Don't worry, it's a common quirk of this art style.
> 
> In Firefox, you may see duplicate artifacts at lower (\<500px) resolutions, this is a Firefox specific bug as far as I know.

## Design
The line art and the colouring are rendered entirely through exploiting CSS gradients (**94 in total**) on a single div. No SVGs, pseudo-elements, or external assets are used.

To demonstrate the scale of the layering, the image below shows the result of replacing every colour (except transparent) with a unique random hex code:

<img src="./layers.png" alt="Doraemon image with each gradient having a different colour" />


## License
The code in this repository is licensed under MIT-0. See [license.txt](./license.txt).

This project is a personal, non-commercial CSS art experiment and is not affiliated with or endorsed by the owners of the [Doraemon](https://dora-world.com/) intellectual property. Doraemon is a trademark and copyright of [Fujiko Pro](http://www.fujio-pro.co.jp/english/), [Shin-Ei Animation](https://www.shin-ei-animation.jp/), and [TV Asahi](https://www.tv-asahi.co.jp/doraemon/).

The design is based on [Shutterstock AI Asset #2718900541](https://www.shutterstock.com/image-generated/doraemon-2718900541). 
