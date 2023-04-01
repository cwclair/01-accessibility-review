# Week 01: Accessibility Review
Refactor an existing site to make it more accessible.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Description of Work
I replaced div elements with semantic elements such as header, section, article, aside, and footer. There is one span tag that remains in the code, as I wasn't sure how to style three specific characters without using the span element.

I ensured that the code flows naturally, from header to footer, with the "hero" image immediately following the header, followed next by the main elements (the three services noted in the header menu, "Search Engine Optimization," "Online Reputation Management," and "Social Media Marketing"), and then the three benefits ("Lead Generation," "Brand Awareness," and "Cost Management") that are stylized into a sidebar on the right.

I added alt text to the images in each category, to the icons in the benefits column, and I reconfigured the hero image so that it was not presented as a background image, allowing me to add alt text to the image. Perhaps there is a way to add alt text to a background image? My online research seemed to conclude that it was not feasible, at least not without some odd tactic being applied. I figured, "Why not just use a styled <img> element here?

I consolidated three classes (search-engine-optimization, online-reputation-management, social-media-marketing) into one class (main-services), as the three individual classes had identical stylings. I did the same thing for the three classes used in the sidebar (benefit-lead, benefit-brand, benefit-cost), creating a new, consolidated class called benefit-individual. I thought this naming convention made sense seeing as the parent class for the overall sidebar section was called benefits. I also consolidated the h2/h3 and img stylings for each of these former class groups, since they also were identical (like their parent classes). 

In the aside section, I adjusted the margins in some spots to give what I felt was better separation between each of the three categories. Before, it felt like the preceding p and the subsequent h3 were too close to provide a feeling of delineation.

I added an id to one of the main elements (Search Engine Optimization) so that the link in the nav bar would work.

The heading tags fall in sequential order. I adjust the footer to have an h4 tag, as it didn't make sense to me to have an h2 at the portion of the page. I also adjusted the h3 tag in the Elements area to have a larger point size, to make it more in line with the sizes of the h2 and h4 tags, and to give it more heft, as I felt the h3 didn't stand out as it should.

The last thing I'll note is the first thing I did when starting the assignment, which was to add an actual title to the head section. Hopefully the good folks of Horiseon like it better than "Title."




## Installation
n/a
## Usage
n/a
## Credits
n/a
## License
n/a
