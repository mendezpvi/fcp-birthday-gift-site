# Birthday GIFt Site

## *Overview* 📝
As part of the **Web Dev Basics** module in the [**Frontend Career Path**](https://v2.scrimba.com/the-frontend-developer-career-path-c0j) by [**Scrimba**](https://v2.scrimba.com/home), we developed the **Birthday GIFt Site**, focusing on fundamental concepts of HTML, CSS, and accessibility.

## *Screenshot* 📷

![Birthday GIFt Site](./images/birthday-gift-site-screenshot.avif)

## *Links* 🔗

[Scrim code](https://v2.scrimba.com/s0jatukv69) 👀

[Live site](https://mendezpvi.github.io/fcp-birthday-gift-site/) 👀

## *What I learned* 🤓

### CSS Concepts
+ `align-items`
+ `flex-direction`
+ `:hover`
+ **Gradients**
+ **Grouping selector**
### Accessiblility & ARIA
+ Aria roles and Attributes for background images
  + `role="img"`
  + `aria-label="..."`
+ `<em>`
  + Is short for emphasis.
  + It's used for words or phrases that would be stressed when spoken.
  + It's important for assistive technologies.
+ `<strong>`
  + Is used for importance, seriousness, or urgency.
  + **Bolds** the text to make meaning visually clear.
  + Is important for assistive technologies.
### HTML Multimedia
+ Audio & Video tags.
  + Audio transcripts and text tracks.
  + Video `height` and `width` should always be set - **pixels** only!
  + This saves the required space on the page. Without a fixed height and width, the layout can change when the file loads.
  + Do **not** use **height** and **width** to resize a video (user might download bigger file than is required). Use a program to resize the file before using it on the page.
+ Video and audio-specific attributes
  + `controls`
  + `muted`
  + `loop`
  + `autoplay`

    ```css
    <audio controls>
      <a href="media/audio/scrimbaPodTom.mp3">download audio</a>
      <source src="media/audio/scrimbaPodTom.mp3" type="audio/mp3">
      <source src="media/audio/scrimbaPodTom.wav" type="audio/wav">
    </audio>

    <video controls width="400" height="225">
      <a href="media/video/scrimbaPodTom.mp4">download video</a>
      <source src="media/video/scrimbaPodTom.mp4" type="video/mp4">
      <source src="media/video/scrimbaPodTom.webm" type="video/webm">
    </video>
    ```
### Replaced elements
+ Elements whose contents are not affected by CSS.
+ Typical replaced elements are:
  + `<iframe>`
  + `<video>`
  + `<embed>`
  + `<img>`
### HTML Tables
+ Structuring Tabular Data.
+ That is - information presented in a 2D table comprised of **rows** and **columns** of cells.
+ HTML tables **NOT** for:
  + Creating layouts.
  + Anything else.
  + And I mean ***anything***.
+ Basic HTML Table elements
  + `<table>` - the main table element - contains all table data.
  + `<tr>` - defines a row of cells in a table.
  + `<td>` - a cell of a table that contains data.
+ Improve accessibility and add better table structuring:
  + `<thead>` - set of rows defining the head of the columns of the entire table.
  + `<th>` - the header of a group of table cells.
  + `<tbody>` - the table body.
  + `<tfoot>` - table foot element.
  + `<caption>` - the caption (or title) of a table.
  + The **scope** attribute is used to tell screen readers exactly what cells the header is a header for.

## *Author* 🔰

✨ Frontend Mentor - [@medezpvi](https://www.frontendmentor.io/profile/mendezpvi)

✨ X (formerly Twitter) - [@medezpvi](https://x.com/mendezpvi)