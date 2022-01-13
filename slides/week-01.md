---
marp: true
# theme: gaia
_class: lead
html: true
paginate: true
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

# HTML Basics

---

# Basic Structure of a HTML Document

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website – Homepage</title>
  </head>
  <body>
    <h1>My Homepage</h1>
    <p>
      This is a paragraph with a <a href="http://example.com">link</a> another website.
    </p>
  </body>
</html>
```

---

![](./images/2021-08-19-22-24-00.png)

--- 

# The DOM – Document Object Model 

![](./images/2021-08-19-21-25-45.png)

An HTML Document can be visualised as a tree-like structure where each of the leaves represent DOM nodes, eg: elements, texts, and attributes.


---

# HTML Elements

---
## `<!DOCTYPE>` Doctype

Doctype tells the browser what version of HTML we using so it knows how to what HTML elements to expect.

`<!DOCTYPE html>` States we are using HTML5.

---

## `<head>` The Document Metadata (Header) element

The head element contains information (metadata) about the document, like its title.
We can reference any resources we might need for the document here, eg: 
- CSS styling
- JavaScript 
- SEO: keywords, description, author

--- 

## `<title>` Document Title element

The title element of your webpage shows in the window/tab of your browser.
Titles are important for SEO.

![](./images/2021-08-19-16-09-29.png)


---

## `<body>` Document Body element

The body element contains the content of the document which displays in the browser's window.

![](./images/2021-08-19-22-28-00.png)

---

## `<h1>`...`<h6>` Headings

There are six levels of headings: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` and `<h6>`.

Each HTML Document should only have one `<h1>` as the main heading for that webpage's content—using more is allowed but is not best practice.

Headings should not skip levels: `<h1>`, followed by `<h2>`, then `<h3>` and so on.

Avoid using heading elements to resize text.

---

| HTML | Output |
| - | - |
| `<h1>Beetles</h1>`<br/>`<h2>External morphology</h2>`<br/>`<h3>Head</h3>`<br/>`<h4>Mouthparts</h4>`<br/>`<h3>Thorax</h3>`<br/>`<h4>Prothorax</h4>`<br/>`<h4>Pterothorax</h4>`|![](./images/2021-08-19-23-37-05.png)|

---

## `<p>` Paragraph

The `<p>` element represents a paragraph. Paragraphs are represented visually as "blocks" of text separated from adjacent blocks by blank lines.

Paragraphs can be any structural grouping of related content, such as images or form fields.

---

| HTML | Output |
| ---- | ------ |
| `<p>`<br/>`Geckos are a group of`<br/>`usually small, usually`<br/>`nocturnal lizards. They...`<br/>`</p>`<br/>  `<p>`<br/>`Some species live in houses`<br/>`where they hunt insects`<br/>`attracted by artificial...`<br/>`</p>` |![](./images/2021-08-19-23-27-57.png)            |

---

## `<img />` Image element

The `<img />` element represents an image. Images are represented visually inline.

Image is a self-closing tag and must have a `src` attribute which takes a URL its value.

`<img src="http://example.com/my-image.jpg" />`

---

| HTML | Output |
| ---- | ------ |
| `<img src="https://www.idesign.wiki/wp-content/uploads/2020/11/timothy-john-berners-lee-3-1024x682.jpg" />` |![](https://www.idesign.wiki/wp-content/uploads/2020/11/timothy-john-berners-lee-3-1024x682.jpg)|

---

| HTML | Output |
| ---- | ------ |
| `<img src="images/cat.jpg" />` | ![](images/cat.jpg) |


---

## Image URLs
URL stands for Uniform Resource Locator. It represents an address of where a resource is located.

---

### Absolute URL
Has the protocol (`http`/`https`), the domain (`example.com`), the path to folder and the filename, e.g.:
`https://www.idesign.wiki/wp-content/uploads/2020/11/timothy-john-berners-lee-3-1024x682.jpg`

---

### Relative URL
Has the path *relative* to current file or domain, e.g.:
- `images/cat.jpg`
- `images/cat.jpg`
- `../images/cat.jpg`
- `/images/cat.jpg`

---

# Footnotes

### Doctypes for previous versions of HTML

**HTML 4.01**
`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`


**XHTML 1.1**
`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">`

---

# Resources

**W3Schools** – Educational website for learning coding online
https://www.w3schools.com/html/default.asp
– Good resources for beginners and learning any web-technology for the first time.

**MDN Web Docs** – Resources for developers, by developers.
https://developer.mozilla.org/en-US/
– Good for understanding 

**WHATWG** – Web Hypertext Application Technology Working Group
<https://html.spec.whatwg.org/dev/>
– Maintains the HTML and DOM Living Standards since 2019
– Previously standards were maintained by [W3C: World Wide Web Consortium](https://www.w3.org)
Read more about the transition from W3C to WHATWG [here](https://www.w3.org/blog/2019/05/w3c-and-whatwg-to-work-together-to-advance-the-open-web-platform/).

---

---

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website – Homepage</title>
  </head>
  <body>
    <h1>My Homepage</h1>
    <p>
      This is a Paragraph.
    </p>
    <h2>This is a Heading 2</h2>
    <h3>This is a Heading 3</h3>
    <p>
      This is a another paragraph with an image of Tim Berners 
      Lee <img src="https://www.idesign.wiki/wp-content/uploads/2020/11/
      timothy-john-berners-lee-3-1024x682.jpg" />
    </p>
    <h3>This is a another Heading 3</h3>
    <p>
      This is a yet another paragraph with an image of a 
      cat. <img src="images/cat.jpg" />
    </p>
  </body>
</html>
```

---

https://github.com/huston-school/

---

## Homework
1. Start creating your Film Festival webpage
2. Heading 1: Title of your Film Festival
3. Paragraph describing your Film Festival
4. Add some extra Headings and Paragraphs with details of films you will be showing.