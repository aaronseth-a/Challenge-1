# Updates to Horiseon Marketing's Webpage

## Summary

The client wanted their webpage updated with semantic html to make it easier for SEO optimization. Currently the site html was done purely with `<div>` elements. It was visually functional but definitely not semantic. The site was updated using the following semantic elements:
- `<header>`
- `<nav>`
- `<main>`
- `<article>`
- `<aside>`
- `<section>`
- `<footer>`

Also all of the heading elements were updated with respect to the flow of the page. The page title was given the `<h1>`. The headings in the main section were each designated `<h2>`. Those in the aside were designated `<h3>`. Finally the section in the footer was designated `<h4>`. This last could have been changed to `<strong>` or `<span>` but it was decided that the client wanted this to be of note. 

Lastly, `alt` descriptions were added to all images. 

With these changes the Acceptance Criteria should have all been met. One thing of note:  

```
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
```
This acceptance criteria could be said to not be correct due to the use of `<main>`, `<article>`, and `<aside>` tags. An argument could be made that these tags relate to the style and positioning. In that case, all of these tags could be replaced with `<section>` without any change to the layout. However, use of these semantic tags will make it easier for any future developer  who works on this project, including the client, to easily find the desired section to be updated.  

## Challenge Requirements

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

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

## Contact Information

<strong>Name:</strong> Aaron Allen  
<strong>Email:</strong> aaronseth.allen@gmail.com 
