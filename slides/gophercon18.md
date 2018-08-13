# Hacker Slides

[twitter]: # (@bketelsen)
[event]: # (Gophercon 2018)
[eventurl]: # (https://www.event.com/)
[title]: # (Deck Title)
[image]: # (/images/demo.png)
[imagealt]: # (A Dog Grinning)
[date]: # (March 17, 2018)
[videourl]: # (https://www.event.com/myvideo/url/)

### Hack together simple slides

<!-- .slide: data-transition="zoom" -->

---

## Welcome

Welcome to Gophercon 2018

--

## More markdown (tables)

****

|h1|h2|h3|
|-|-|-|
|a|b|c|

****

--

## More markdown (code)

```
version: '2'
services:
  slides:
    image: msoedov/hacker-slides

    ports:
      - 8080:8080
    volumes:
      - ./slides:/app/slides
    restart: always

    environment:
     - USER=bob
     - PASSWORD=pa55

```

--

## Local images

![demoPicture](/images/demo.png)

Copy images into slides/images/ & include with MD:

```
![demoPicture](/images/demo.png)

```
or HTML:

```
<img src="/images/demo.png">

```


---

## Learn more

- [RevealJS Demo/Manual](http://lab.hakim.se/reveal-js)
- [RevealJS Project/README](https://github.com/hakimel/reveal.js)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
