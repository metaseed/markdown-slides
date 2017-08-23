# How to start

* install vscode-reveal extension and edit vscode config`(ctrl+,)`

```json
    // revealjs
    "revealjs.margin": 0.05,
    "revealjs.history": true,
    "revealjs.previewLinks": true,
    "revealjs.customTheme": "style",
    "revealjs.theme": "white",
    "revealjs.width": "100%",
    "revealjs.height": "100%",
    "revealjs.highlightTheme": "color-brewer",
    "revealjs.slideNumber": true,
    "revealjs.center": false,
```

* copy the slide fold to the location of your slide

* create your first slide:

```html
<!-- .slide: data-background="./slide/images/background.svg" -->
<!-- .slide: id="your-side-id" -->
# Topic Title

## Subtopic Title

<small>Created by [metasong](http://metaseed.com) / [@metasong](http://twitter.com/metasong)</small>

---

second slide
```

* question/answer side:

```html
---
<!-- .slide: data-background="./slide/images/question-slide.jpg" -->
## Quiz

--
<!-- .slide: data-background="./slide/images/answer-slide.jpg" -->

## Answer

answer is...
```

## Reference


## Tricks

* term definition list

```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

* remove node modules recursively

```bash
npm install -g rm-modules
rm-modules
```

* [markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
