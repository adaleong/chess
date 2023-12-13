# Documentation
1. Started with setting up the website, I followed this tutorial to publish. https://www.youtube.com/watch?v=CTqqvaVKAJU&t=113s
2. I used the last website we made in class as a reference for how to set up the site.
3. The template wasn't appearing on the site because I had everything dragged into another folder.
4. Edited the title and subtitle by replacing the text.
5. Deleted the template to restart
6. Used the beginning of the band website, changed the header.
7. Changed the font to verdana
8. Created a section with this:
```</h1>
<p>
  <h2>The Board</h2>```

9. Changed the colors in the css file
10. Added 'The Board' header and text, also I realized that the formatting was incorrect because I used h2 instead of h1, and the font section was placed in the wrong section in the styles.css section.
11. Changed `background-color: rgb#4a6cea;` to `background-color: #4a6cea;` this this is a hex code, forgot to remove it the first time and the background colors defaulted to the text color.
12. Edited the body text, changed the formatting for h2.
13. Uploaded the images for 'The Board' section
14. Removed the extra 'h1'
15. header 2 doesn't appear with correct formatting, I had an extra <p> so it defaulted to the formatting under p.
16. Uploaded the image files for the king, added a header and description for the king
17. Edited the titles for consistent formatting
18. Edited the image files since they weren't loading
19. Added a section for the queen
20. Uploaded the queen image file
21. Uploaded an ad file
22. Scaled the ad.
23. Uploaded the rook section and image
24. Created the sections for the bishop, knight, and pawns. I uploaded the images as well.
25. Experimented with creating columns with this code and used this website as a resource: https://www.w3schools.com/howto/howto_css_two_columns.asp 
```
  <div class="row">
    <div class="column"></div>
    <h2>     THE PAWNS</h2
    <div class="column"></div>
    <h2>     THE PAWNS</h2
  </div>
```
26. Changed the image width sizes all the 700px width for consistency.
27. The column didn't really create columns so I'm trying this:
```<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>```
28. Columns didn't work so tried this:
```
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; 

.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>Two Equal Columns</h2>

<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>
```
29. Added a section for basic strategy, changed the text style by adding
```
blockquote {
    color: #D4D7D9;
    font-family: 'Trebuchet MS', sans-serif;;
    text-align: left;

  }
```