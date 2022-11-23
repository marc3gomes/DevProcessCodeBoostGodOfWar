# Annotations

I always create a file or folder called `NOTES` at every event or course I attend.

The objective is simple: Write down information relevant to the moment I participated in the event and create a source of consultation in the future.

&#xa0;

## Schedule #2 Class

- [x] Creating folder structure and files;
- [x] Exporting the assets;
- [x] Configuring the project fonts;
- [x] Creating the reset file;
- [x] Creating the grid file;
- [x] Analyzing site patterns and creating in css;
- [x] Starting coding
  - [x] HEADER
  - [x] SECTION HERO
  - [x] SECTION INFOS

## Schedule #3 Class

- [x] Continuing coding
  - [x] SECTION STORY
  - [x] SECTION CHARACTER
- [x] Swiper Slide
- [x] Coding the slide

&#xa0;

## CSS

#### `DISPLAY`
The element can be by default `block` or `inline`. So we have a property to work with the arrangements of these elements.

Example:
```css
/* Turns the element into a block element. */
display: block;

/* Turns element into line element. */
display: inline;

/* Offers the properties of both types of elements. */
display: inline-block;

/* Makes page elements invisible. */
display: none;
```

---

#### `BOX-SIZING`
It maintains the real dimensions of the `Box Model` even with the use of paddings and margins.

Example:
```css
box-sizing: border-box;
```

---

#### `REM`
A relative unit of measure. Used to optimize and standardize sizes, a great option for responsive.

`1rem` = `16px`

Settings
```css
html {
    font-size: 62.5%; /* = 10px */
}

.class {
    font-size: 1rem;
}
```

---

#### `POSITION`
An element by default it is `position: static;`

A `position: absolute;` depends on a relative element, that is, a `position: relative;`, on the closest element.

Example:
```css
/* Static, has no action using displacement methods. */
position: static;

/* Relative, can be controlled with the offset methods. */
position: relative;

/* Floating, loses its position, stays on any element. */
/* Offset methods can also be used. */
position: absolute;

/* Displacement methods. */
top: 0;
left: 0;
bottom: 0;
right: 0;
```

---

#### `MEDIA QUERIES`

A way to define rules for displaying styles according to the screen size of devices.

Used to work the responsive.

Examples:
```css
/* Screens =< 991px will have the BG color green. */
@media (max-width: 991px) {
    .class {
        blackground-bg: green;
    }
}
```

---

#### `FLEXBOX`

Advanced positioning technique within CSS.

Used to position blocks on the screen.

*`Display: flex;` must be defined on the Parent element. To make child elements flexible for displacement.*

Examples:
```css
display: flex;

/* Methods for flex-direction */
flex-direction: column;
flex-direction: column-reverse;
flex-direction: row;
flex-direction: row-reverse;
justify-content: flex-start;
justify-content: flex-end;
justify-content: center;
justify-content: space-between;
align-items: flex-start;
align-items: flex-end;
align-items: center;


```