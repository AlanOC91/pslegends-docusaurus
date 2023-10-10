---
sidebar_position: 3
---

# Images

**NOTE: All blocks should be center aligned unless otherwise noted.**

Images can and should often be used in articles to help break up the text and to make the article more visually appealing. Images can be added to articles in a number of ways.

## Sourcing Images

If you cannot directly capture images, you can freely use images from the [MobyGames](https://www.mobygames.com/) database. As per their [FAQ](https://www.mobygames.com/info/faq6/), you can use up to 20 of their screenshots for each of your articles. All that is required is to credit them at the end of the article.

MobyGame can split screenshots by platform. For example, when getting Dragon Age: Origins screenshots, we were able to source screenshots from the PS3 version which was appropriate for our article.

Example link: https://www.mobygames.com/game/43297/dragon-age-origins/screenshots/ps3/

To credit them, please add the following in a paragraph block and set the text to small size:

> Screenshot(s) via [MobyGames](https://www.mobygames.com/).

## Adding Images to Articles via the Image Block

The easiest way to add images to articles is to use the Image Block. This block allows you to upload an image from your computer or to select an image from the media library. Once the image is uploaded, you can then add a caption to the image. The caption will be displayed below the image when the article is published. 

**NOTE: Please try center align your image captions. This will make the article look more consistent.**

## Adding Images to Articles via the Slider Block

The Slider Block allows you to add an image gallery with slider functionality to your article. This is useful for adding screenshots to your article. I believe this is most beneficial at the end of the article (before review scores if a review).

![Slider Block](/img/slider_block.png)

## Featured Image

The featured image is the image that will be displayed on the article page and across the site. This is just as important as setting a category. It is recommended that you use an image that is relevant to the article you are writing. If you don't set a featured image, one will be set for you before the article is published.

# Image Optimisation

Images are now automatically optimised when uploaded to the site. The site makes use of [Spatie Image Optimizer](https://github.com/spatie/image-optimizer) to optimise images on upload. This helps reduce the filesize of images and helps to improve the performance of the site.

Optimal filesizes for images would be roughly **100kb - 400kb**. This will vary depending on the image. For example, a 4K screenshot of a game will be a large filesize. However, a screenshot of a game from the PS1 era will be a much smaller filesize.

We recommend you save images as **.jpg** files. This will help to reduce the filesize of the image. Most computer programs these days can change the format of an image, the most common being from .png to .jpg. If you are unsure how to do this, you can use a free online tool such as [this one](https://convertio.co/png-jpg/).