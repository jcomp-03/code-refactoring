# Week 1 Challenge - Code Refactor for Marketing Agency

The purpose of this week's challenge is to refactor existing HTML markup and CSS styling for the website of a marketing agency. In the process, I looked to optimize the HTML structure logic and the appropriateness of HTML tags for particular segments of the website, and generally organized and improved the readability of the existing codebase; additionally, I wished to improve the efficiency of the CSS styling declarations. In the CSS stylesheet, there was a significant opportunity to improve with respect to the specificity of selector statements; a lot of CSS styling was repetitive and could be generalized to decrease the total number of lines of code in the style sheet. For example, the two images below show I am able to condense 24 lines of CSS coding into just 8 (well, 9 if you include the font-family property:value declaration in the <body> styling section I added).

[Click here to go to images](/assets/images/)
  
![CSS styling before changes]("/assets/images/CSS style post.PNG")
  
  

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a professional README describing the project.

- - -
© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
