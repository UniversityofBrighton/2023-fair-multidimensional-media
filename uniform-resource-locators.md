---
title: 'Uniform Resource Locators (URLs)'
teaching: 10
exercises: 2
---

---
title: 'URLs'
teaching: 10
exercises: 2
---


## Introduction 

You might already be familiar with websites bringing together a mixture
of content, such text, images, video or 3D models. Delivering stories over
the web by using a browser provides many advantages. This includes 
people being able to easily access the content regardless of which
platform they are using, such as PCs, mobiles or a VR headsets.

In order to understand how to create stories over the web that 
link multidimensional data, it is first necessary 
to learn how data, of any type, is made available over the Internet.

A webpage is usually written in HTML and other web-languages, 
such as JavaScript, TypeScript or PHP. This code is 
in remote computers so that everyone can access the webpage they render.

To find webpages, we use 
a link on a browser 
called an URL (Uniform Resource Locator),
such as [https://www.brighton.ac.uk](http://www.brighton.ac.uk), 
[https://www.europeana.eu/en](https://www.europeana.eu/en). 

Furthermore, URLs can contain a link to a specific section within a web page
by using anchors. You will notice the use of anchors on a URL, as they 
include using a **#** symbol followed by a word. This word is usually defined
in the HTML code so that the webpage knows which part the user is looking for.

See these examples:

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

This is a very simple browser exercise, but it serves to get
the student thinking on things which are added to a URL for
processing by the webserver.
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Try this examples

What is the difference of navigating to these two different URLs

- [https://sdgs.un.org/](https://sdgs.un.org/)
- [https://sdgs.un.org/#goal_section](https://sdgs.un.org/#goal_section)

:::::::::::::::::::::::: solution 

You will notice that the URL that contains the **#** symbol in the URL
takes you to the sepecific section with the 17 SDG goals.
:::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::


URLs can become more complex if we want the server which
is 'serving' our webpage to perform any additional functionality before, during or
after loading the webpage. Sometimes, we might find a **?** symbol in the URL.
This symbol signifies that some text will be passed as data to the server.
The server might be running additional code which will process this text
and change the content of the webpage accordingly.


::::::::::::::::::::::::::::::::::::: challenge 

## Challenge: Use a query in a URL

Try searching a word in the [Europeana homepage][Europeana]

For example, search for the word: 'modernism'



:::::::::::::::::::::::: solution 

You will note that the URL contains the word modernism:

[https://www.europeana.eu/en/search?page=1&view=grid&query=modernism](https://www.europeana.eu/en/search?page=1&view=grid&query=modernism)

Now, try changing directly the search term to the URL to another word.

Go back to the [Europeana homepage][Europeana].

What happens to the URL when you add more than one word in the search? Why?

:::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::


Finally, many webservers make use of the full URL path to send information
to the server. A URL path usually specifies the location of the file 
or resource that the user wants to access in the server. 

You will find this usually with images, PDF and other multimedia file that
a webpage will be including. For example:
[https://culturedigitalskills.org/wp-content/uploads/Logo-Banner-3-1-1024x244.png](https://culturedigitalskills.org/wp-content/uploads/Logo-Banner-3-1-1024x244.png)


The URL path can also be used to specify text to the server,
so that this is processed. After processing the URL 
request the server will return a webpage. For example,

This method is usually used by Application Programming Interfaces or (APIs).
In this lesson, we won't explore this subject in detail. But it will be
good you are aware that the information is passed to the server via the URL path.

For example, try the URL:

[https://gtr.gtr.ukri.org/gtr/api/projects/5B805CC1-2B54-4CAE-9243-8EF4AFC35E7E](https://gtr.gtr.ukri.org/gtr/api/projects/5B805CC1-2B54-4CAE-9243-8EF4AFC35E7E) 

This URL queries
an API to retrieve information that is contained in the database
about the AHRC funded project 'A Roadmap for a National Training Centre 
on Multidimensional Digital Media in the Arts and Humanities'. As you will see in the
webpage, the information is not an HTML page but another structured type of
data which contains various pieces of information about the project.

To understand how to use these URL, you usually need the guide to the API, such as the
[Gateway to research guide](https://gtr.ukri.org/resources/GtR-2-API-v1.7.5.pdf).


::::::::::::::::::::::::::::::::::::: keypoints 

- URLs can be a simple means to find a website
- URLs can also include additional information which allows a server to change how the webpage is 'served'
- URLs also provide the means to use a website as a database which can be queried via the URL path.

::::::::::::::::::::::::::::::::::::::::::::::::
