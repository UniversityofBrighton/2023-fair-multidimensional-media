---
title: 'Interoperable Frameworks'
teaching: 10
exercises: 2
---

![&copy; ImageFlow from AdobeStock](fig/AdobeStock_507575662.jpeg){alt='connect blocks'}

A variety of tools are available over the web to bring together multidimensional content
by deploying storytelling or visualisation techniques:



- [Exhibit](https://www.exhibit.so/)
- [TimeMapper from Open Knowledge Foundation Labs]( https://timemapper.okfnlabs.org/)
- [Meet StoryMaps](https://storymaps.com/)

## What is IIIF?
Whatever the tool used for developing an application,  
it is important to use/reuse multidimensional content by accessing 
it from its existing hosting site.

![&copy; IIIF](fig/International_Image_Interoperability_Framework_logo.png){alt='logo IIIF'}


The International Image Interoperability Framework (IIIF) is a set of technical 
specifications built around shared challenges for accessing multidimensional media.


It is also a community of software, tools, content, people, and 
institutions solving image Interoperability challenges.

From [http://iiif.io/about/](http://iiif.io/about/):
> IIIF (International Image Interoperability Framework) has the following goals:

  > - To give users an unprecedented level of uniform and rich access to image-based resources hosted around the world.
  > - To define a set of common application programming interfaces that support interoperability between image repositories.
  > - To develop, cultivate and document shared technologies, such as image servers and web clients, that provide a world-class user experience in viewing, comparing, manipulating and annotating images.
  
The IIIF technical specifications are the glue that holds things together for image interoperability.

IIIF provides two core APIs:
 
 - Image API (I want to get image pixels)
 - Presentation API (I want to display the images)
 
There are several more APIs that IIIF supports including Search and Authentication. 

This workshop will focus on the Image and Presentation APIs.


## Image API

The [Image API](http://iiif.io/api/image/2.1/) provides 
for a standardized way to request and deliver 
images. This can be for example:

> Give me the original image at full resolution.

> Give me the original image at low resolution.

> Give me a small section at the centre of the image.

> Give me an upside down tiled version of the image in gif format. 

The IIIF Image API allows for 
images to be served dynamically or from a 
static cache (implementation details).

Images are requested using URI templates that have the following syntax:

```
{scheme}://{server}{/prefix}/{identifier}/{region}/{size}/{rotation}/{quality}.{format}
``` 

Here is a quick example of how modifying these parameters 
can change the image that is delivered back to you.

[![transformation &copy; IIIF](transformation.png)](http://iiif.io/api/image/2.1/#order-of-implementation)[^1]
```
region=125,15,120,140 size=90, rotation=!345 quality=gray

.../125,15,120,140/90,/!345/gray.jpg

# Source: http://iiif.io/api/image/2.1/#order-of-implementation
```

::::: challenge

## Trying the Image API

:::::

## [Presentation API](http://iiif.io/api/presentation/2.1/)

The IIIF Presentation API enables you to provide metadata about the structure and layout of image objects. Image type objects represent things like:
 - single images
 - groups of ordered images
 - groups of images that represent pages (book, manuscript)
 
The Presentation API provides metadata about how these image objects can be displayed.

### Basic objects
[![basic objects](https://github.com/IIIF/training/tree/master/intro-to-iiif/images/objects.png)](http://iiif.io/api/presentation/2.1/#basic-types)[^2]

### More complex objects
[![all objects](https://github.com/IIIF/training/tree/master/intro-to-iiif/images/objects-all.png)](http://iiif.io/api/presentation/2.1/#additional-types)[^3]

[^1]: http://iiif.io/api/image/2.1/#order-of-implementation
[^2]: http://iiif.io/api/presentation/2.1/#basic-types
[^3]: http://iiif.io/api/presentation/2.1/#additional-types

Content adopted from [IIIF Training](https://training.iiif.io/) &copy IIIF under CC-BY-4.0 

More information: [Everything you ever wanted to know about IIIF but were too afraid to ask](https://www.slideshare.net/Cogapp/everything-you-ever-wanted-to-know-about-iiif-but-were-too-afraid-to-ask).


