# CSS3 Sticky Notes

[![Build Status][travis_badge]][travis_url]
[![Build Status][license_badge]][license_url]

Stylesheet that uses CSS3-transitions and transformations to create "Sticky Notes" (Post-it notes).

The stylesheet can be seen in action here: [seaweed.dk](http://seaweed.dk)

## Compiling the stylesheet

1. Install node.js.
2. Clone repository `git clone https://github.com/TangChr/sticky-notes`
3. Install dependencies `npm i`

```shell
npm run build
```

## Using the stylesheet

```html
<head>
    <link rel="stylesheet" href="css/sticky.css" type="text/css" media="screen" />
</head>
```

```html
<ul class="sticky-notes">
    <li>
        <a href="#">
            <h2>Note #1</h2>
            <p>Content #1</p>
        </a>
    </li>
    <li>
        <a href="#">
            <h2>Note #2</h2>
            <p>Content #2</p>
        </a>
    </li>
    <li>
        <a href="#">
            <h2>Note #3</h2>
            <p>Content #3</p>
        </a>
    </li>
</ul>
```

[travis_badge]: https://img.shields.io/travis/TangChr/sticky-notes.svg
[license_badge]: https://img.shields.io/github/license/TangChr/sticky-notes.svg
[travis_url]: https://travis-ci.org/TangChr/sticky-notes
[license_url]: https://raw.githubusercontent.com/TangChr/sticky-notes/master/LICENSE