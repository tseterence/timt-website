# timt-website
- Photos courtesy of Tomoyuki Kusunose from oma.com (Tenjin Business Center)

2/16/22 Notes:
- slideshow container still not smooth
        - vertical dimension especially for arrow placement 
        - shrinking window on comp and for mobile not responsive

2/14/22 Notes:
- steps to add new project:
1) update table in proj.html
2) create individual project page using previous as examples
1) html: 
        - add new section.project-container
        - update new img class to mySlides"N"
        - update anchor tags so plusSlides(+/- 1, ("N"-1))
2) css: 
        - include .mySlides"N" to {display: none}
3) js: 
        - update slideIndex and slideID, and add showSlides(1, "N")
4) repeat steps 1-3 for individual project page

- mobile-related:
    - slideshow not smooth on mobile when width = 100%
    - landscape responsiveness
    - idea: home and indiv proj page on mobile like instagram feed, followed by description (latter). swipe between images function on mobile. full-screen view of image only for desktop (> 900 px?) since mobile already offers ability to pinch and zoom.
    - //decrease top margin in html pages
    - //increase project table width
    - //set z-index for header/footer in html pages

- {display: block} for <span> tags instead of unnecessary <p> and improper use of <br> (semantics)    
- fix arrow buttons for slideshow
- proper superscript format in proj table "area" column
- "navlink current" border when on individual proj page?
- when clicking on project title in projects page table, open page in new tab? how about when clicking on link in home page?
- hover feature for image caption (home page)? resume (information page)?


2/4/22 Notes:
- sort function in proj table header
- minify CSS/JS code? gzip?

- //contact page: 1 empty space between each line. no space between email and phone#
- //show only two columns in Projects page for mobile (proj & year): 
https://phppot.com/css/automatic-column-hiding-using-css-in-responsive-table/
- //projects table: no space between rows; only 1 empty space between table header and content. clickable link on project row


1/21/22 notes:
- clicking on image within proj page takes you to fullscreen of said image. within fullscreen, (invisible line) clicking on right-half takes you to next photo. left-half to previous photo. esc keydown or X button on top right to close out of fullscreen?

- //height of img within slideshow remains the same (ie positioning of caption and arrows don't move), see: https://stackoverflow.com/questions/47024703/restricting-slideshow-images-to-height-width-of-the-slideshow-container
- //info page: between each line in single paragraph, 4px spacing. between each paragraph, one entire empty line
- // (manually done with vh) center text vertically within page only for Information and Contact pages
- //project list page, takes user to individual proj page
- //from home page, click on caption --> individual proj page
- //no hover feature at all
- //border box around current page
- //"information" --> clickable attached pdf for resume, opened in new tab (see https://apdesign.k-state.edu/about/faculty-staff/baudoin/)