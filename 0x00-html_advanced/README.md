# 0x00. Advanced HTML

# Welcome!

Welcome to the Web Stack specialization. The 3 first projects will give you all basics of the Web development: HTML, CSS and Developer tools.

In this project, you will learn how to use HTML tags to structure a web page. No CSS, no styling - don’t worry, the final page will be “ugly” it’s normal, it’s not the purpose of this project.

## Resources

**Read or watch:**

- [HTML 5.2](https://www.w3.org/TR/html52/)
- [HTML: HyperText Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Reference - A free guide to all HTML elements and attributes](https://htmlreference.io/)
- [Can I use… Support tables for HTML5, CSS3, etc](https://caniuse.com/)
- [HTML Cheat Sheet - WebsiteSetup](https://websitesetup.org/html5-cheat-sheet/)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- Which guidelines to follow for HTML
- How to create the skeleton of an HTML5 page
- How to use semantic HTML tags to structure a - web page
- Which use cases to use `div` vs `span`
- The semantic values of `header`, `main`, `footer`, `article`, `nav`, `section`, `aside`
- How to use headings (and why its important to follow the hierarchical order)
- How to make lists in HTML
- The differences between medias (SVG, GIF, PNG, JPG)
- How to structure data in a table
- How to integrate a video in a webpage
- How to integrate an audio file in a webpage
- How to embed external content
- How to correctly structure an HTML page

## Requirements

- A `README.md` file at the root of the folder of the project is mandatory
- Your code should be W3C compliant and validate with [W3C-Validator](https://github.com/holbertonschool/W3C-Validator)
- `Techium` will be the name of the company we will use across our webpages.

---

## Quiz questions

<details>
<summary>Show</summary>
  
### Question #0

Which information can we find in the tag head? Please select all correct answers

- [x] metadata
- [ ] navigation
- [ ] link to Twiiter
- [x] link to stylesheets

### Question #1

Which tag should we use to change the browser tab text?

- [ ] `<head>`
- [x] `<title>`
- [ ] `<tab>`
- [ ] `<browser>`

### Question #2

How many levels are available in HTML5 for section headings?

- [ ] 1
- [ ] 2
- [ ] 4
- [x] 6
- [ ] 8
- [ ] 10

### Question #3

Which tag should we use to draw an horizontal line? (usually used to separate topics in a paragraph)

- [ ] `<line>`
- [ ] `<br>`
- [ ] `<break>`
- [x] `<hr>`

### Question #4

Which tag should we use to group elements in an unordered list?

- [ ] `<li>`
- [x] `<ul>`
- [ ] `<ol>`
- [ ] `<table>`
- [ ] `<unordered list>`
- [ ] `<list>`

### Question #5

Which tag should we use to create an hyperlink?

- [ ] `<link>`
- [ ] `<to>`
- [ ] `<p>`
- [ ] `<div>`
- [x] `<a>`

### Question #6

Which tag should we use to change the font weight of a text?
Please select all correct answers

- [ ] `<h1>`
- [x] `<b>`
- [ ] `<i>`
- [ ] `<em>`
- [x] `<strong>`
- [ ] `<bold>`

### Question #7

Which tag should we use to embed an image?

- [x] `<img>`
- [ ] `<iframe>`
- [ ] `<div>`
- [ ] `<caption>`

### Question #8

Which tag should we use to embed another website?

- [ ] `<div>`
- [ ] `<a>`
- [x] `<iframe>`
- [ ] `<p>`
- [ ] `<code>`

</details>

---

## Tasks

<details>
<summary>View Contents</summary>

### [0. Create your first webpage](./0-index.html)

Create your first HTML file `0-index.html` with:

- Add the doctype on the first line (without any comment)
- After the doctype, open and close a `html` tag
- Add the language tag, specify English for [ISO language code](https://www.sitepoint.com/iso-2-letter-language-codes/) and add the direction tag (ltr or rtl) on the `html` tag.
- Open your file in your browser (the page should be blank)

**W3C won’t pass - you can ignore it**

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `0-index.html`

### [1. Structure your webpage](./1-index.html)

Copy the content of `0-index.html` into `1-index.html`

**Create the head and body sections**

- inside the `html` tag, create the `head` and `body` tags (empty) in this order

**W3C won’t pass - you can ignore it**

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `1-index.html`

### [2. The head - meta charset, viewport, title, description, favicons](./2-index.html)

Cpy the content of `1-index.html` into `2-index.html`

**Meta charset:**

- add a `meta` tag inside the `head`:
  - add the `charset` attribute with the value `utf-8`

**Viewport:**

- add a `meta` tag inside the `head`:
  - add an attribute `name` on the tag and specify that it is the meta `viewport`
  - add the key `width` with the value `device-width`
  - add the key `initial-scale` with the value `1.0`
  - add the key `viewport-fit` with the value `cover`

**Title:**

- add the `title` tag just after the meta viewport with value: `Homepage - Techium`

**Description:**

- add a `meta` tag inside the `head` section
  - add an attribute `name` on the tag and specify that is the meta `description`
  - add another attribute called `content`
  - add the following description: `Techium is a digital agency`

**Favicons:**

- download the image above to use as a favicon
- Use the tool at [https://realfavicongenerator.net/](https://realfavicongenerator.net/) to generate all the favicon formats
- take the `favicon.ico` and `favicon.png` and place these at the root of your project directory, so that it is siblings with your `[0-9]+-index.html` files.
- inside the `head`, create 2 `link` tags with these 3 attributes: `rel`, `type`, and `href`.
  - the first `link` tag:
    - rel: `icon`
    - type: `image/x-icon`
    - href: `./favicon.ico`
  - the second `link` tag:
    - rel: `icon`
    - type: `image/png`
    - href: `./favicon.png`

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `2-index.html`

### [3. Simple header, main, footer](./3-index.html)

Copy the content of `2-index.html` into `3-index.html`

**Header:**

- create the `header` of your page between the open and close `body` tag
- put the text `Header` inside the header

**Main:**

- create the `main` tag after the `header` tag
  - put the text `Main content` inside your `main` tags

**Footer:**

- create the `footer` tag after the `main` tag
  - put the text `Footer` inside the `footer` tags

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `3-index.html`

### [4. Aside](./article.html)

Copy the contents of `3-index.html` into `article.html`

- change the `<title>` to put: `Article - Techium`
- inside the `main` tags
  - after the text, create the `aside` tags with text `Aside`

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `article.html`

### [5. Section](./5-index.html)

Copy the content of `3-index.html` into `5-index.html`

- inside your `<main>` section
  - remove the text in `main`, create these sections:
    1. create first section and put the text `Hero section` inside
    2. create second section and put the text `Services section` inside
    3. create third section and put the text `Works section` inside
    4. create fourth section and put the text `About section` inside
    5. create fifth section and put the text `Latest news section` inside
    6. create sixth section and put the text `Testimonials section` inside
    7. create seventh section and put the text `Contact section` inside

**Does not need to pass W3C**

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `5-index.html`

### [6. Work, News, Testimonial articles](./6-index.html)

Copy the content of `5-index.html` into `6-index.html`

**Work articles:**

- inside the section `Works section`
  - add 3 `article` tags
    - inside each `article` write `Work #` where the hashtag will be the ordered number (1, 2, or 3)

**News articles:**

- inside the section `Latest news section`
  - add 3 `article` tags
    - inside each `article` write `Article #` where the hashtag will be the ordered number (1, 2, or 3)

**Testimonial articles:**

- inside the section `Testimonials section`
  - add 3 `article` tags
    - inside each `article` write `Testimonial #` where the hashtag will be the ordered number (1, 2, or 3)

**W3C won’t pass - you can ignore it**

**Repo:**

* GitHub repository: `holbertonschool-web_front_end`
* Directory: `0x00-html_advanced`
* File: `6-index.html`

### [7. Navigation](./7-index.html)

Copy the content of 6-index.html into 7-index.html



### [8. Level 1 headings](./8-index.html)

Copy the content of 7-index.html into 8-index.html



### [9. Level 2 headings](./9-index.html)

Copy the content of 8-index.html into 9-index.html


### [10. Level 3 headings](./10-index.html)

Copy the content of 9-index.html into 10-index.html



### [11. styleguide](./11-styleguide.html)

Copy the content of 3-index.html into 11-styleguide.html



### [12. Paragraphs](./12-index.html)

Copy the content of 10-index.html into 12-index.html



### [13. styleguide paragraphs](./13-styleguide.html)

Copy the contents of 11-styleguide.html into 13-styleguide.html



### [14. Span](./14-index.html)

Copy the contents of 12-index.html into 14-index.html



### [15. Div](./15-index.html)

Copy the contents of 14-index.html into 15-index.html



### [16. Structure your sections](./16-index.html)

Copy the contents of 15-index.html into 16-index.html



### [17. Comments](./17-index.html)

Copy the content of 16-index.html into 17-index.html



### [18. link your logo](./18-index.html)

Copy the content of 17-index.html into 18-index.html



### [19. Create new pages](./about.html)

Copy the content of 18-index.html into about.html, latest_news.html and contact.html



### [20. Add links](./20-index.html)

Copy the content of 18-index.html into 20-index.html



### [21. Add social media links](./21-index.html)

Copy the content of 20-index.html into 21-index.html



### [22. "Button" links](./22-index.html)

Copy the content of 21-index.html into 22-index.html



### [23. Services, Works, Latest news links](./23-index.html)

Copy the content of 22-index.html into 23-index.html



### [24. List the links](./24-index.html)

Copy the content of 23-index.html into 24-index.html



### [25. Secondary navigation menu](./25-index.html)

Copy the content of 24-index.html into 25-index.html



### [26. Examples of lists for the styleguide](./26-styleguide.html)

Copy the content of 13-styleguide.html into 26-styleguide.html



### [27. Separate content](./27-index.html)

Copy the content of 25-index.html into 27-index.html



### [28. Horizontal rule example](./28-styleguide.html)

Copy the content of 26-styleguide.html into 28-styleguide.html



### [29. Client quotes](./29-index.html)

Copy the content of 27-index.html into 29-index.html



### [30. Examples of quotes](./30-styleguide.html)

Copy the content of 28-styleguide.html into 30-styleguide.html



### [31. Address and latest news authors](./31-index.html)

Copy the content of 29-index.html into 31-index.html



### [32. Typography section - using the correct tags](./32-styleguide.html)

Using 30-styleguide.html



### [33. Table](./33-styleguide.html)

Copy the content of 32-styleguide.html into 33-styleguide.html



### [34. Details](./34-styleguide.html)

Copy the content of 33-styleguide.html into 34-styleguide.html



### [35. Replace text logo with image logo](./35-index.html)

Using 31-index.html



### [36. Add images to your sections](./36-index.html)

Copy the content of 35-index.html into 36-index.html



### [37. Social icons](./index.html)

Using 36-index.html



### [38. Add a video player in the styleguide](./38-styleguide.html)

Copy the content of 34-styleguide.html into 38-styleguide.html



### [39. Add an audio player in the styleguide](./39-styleguide.html)

Copy the content of 38-styleguide.html into 39-styleguide.html



### [40. Add a iframe example in the styleguide](./styleguide.html)

Copy the content of 39-styleguide.html into styleguide.html



</details>

---

## Author
### _Edgar Miguel Rodríguez G._

- **Github:** [Miguelro123](https://github.com/Miguelro123) 
- **Linkedin:** [Edgar Miguel Rodriguez Garcia](https://www.linkedin.com/in/edgar-miguel-rodriguez-garcia-20a5281a2/)
