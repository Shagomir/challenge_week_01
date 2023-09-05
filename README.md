# challenge_week_01
Bootcamp challenge for week 01



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

When refactoring this code, I aimed to simplify by removing duplicate classes and specifying semantic tags for the various areas of the page. 

I used: Header for the top area and title
nav for the Navigation links in the upper right.
body for the general content and article links
article for each individual section in the body that is linked to the nav
aside for the side bar with additional information
section for each area within the side bar
footer for the bottom text. 

I removed many duplicate classes, while retaining the IDs for linking purposes. 

I noted that the link for the Search Engine Optimization was not working, so I added this ID to the appropriate article element. 

I also updated the title of the page and the alt text for all images. As I was not able to add alt text for the hero image, I followed the best practice per this article: http://www.davidmacd.com/blog/alternate-text-for-css-background-images.html and changed the hero to a span with the role="img" and aria-label attributes. 

Completed file can be found at https://shagomir.github.io/challenge_week_01/