# Michael Sallee - Project0
### DESCRIPTION:
This project was created to demonstrate an understanding of HTML5, CSS/SASS, Bootstrap 4, & Git.

### FileList
```
project0/
├── README.md             This file containing project details
├── classes.html          Table of Fall '19 classes/descriptions using Bootstrap 4 & CSS
├── contact.html          Virtual business card using Bootstrap4 & CSS
├── css
│   ├── main.css          Global CSS file created from main.scss
│   ├── main.css.map      Mapping of main.scss to main.css
│   └── main.scss         Global SCSS file used to create main.css
├── images
│   ├── crest.png         HES crest
│   └── michael.jpg       Profile photo
├── index.html            Initial page with "Hello, world!" text
└── projects.html         Table styled with CSS and @media
```

### Notes
- Each page uses the same responsive design navigation bar created with Bootstrap 4. Since the code is nearly identical, it could likely be reused via server side includes and/or jQuery.

- Additionally each page contains an under construction warning banner created using Bootstrap 4 and could also be reused via server side includes such as:
  `<?php include("filename"); ?>`
It's my understanding HTML include functionality is currently in draft but very few browsers currently support it or support it only as an experimental feature. Also, in these sections, I kept inline styling so that the full code was containerized and reusable in the future.

