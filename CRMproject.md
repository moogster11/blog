---
title: CRM
feature_text: |
  Events and data capture strategy
feature_image: "https://picsum.photos/2560/600?image=873"
excerpt: "A demo of Markdown and HTML includes"
aside: true
---


### CRM

[CRM Form requirements](https://sheffieldhallam.sharepoint.com/:x:/r/sites/8302/ecrm/CRM%20Project%20Team/_layouts/15/Doc.aspx?sourcedoc=%7B7C720F52-8972-4816-821E-5D2C9069C871%7D&file=Forms%20Requirements%20v0.3.xlsx&action=default&mobileredirect=true&DefaultItemOpen=1&ct=1643896239565&wdOrigin=OFFICECOM-WEB.START.OTHER&cid=2a4baa05-c6f3-46fd-a054-d5bc35a3202e)

Form field mapping

Figma - open day interface
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FgK3SlxGxXJMvn2KtOMCs7N%2FCRM---Open-day-journey%3Fnode-id%3D0%253A1" allowfullscreen></iframe>



# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>A small element</small>

[CRM link](_posts/2022-01-02-CRM.md)

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
