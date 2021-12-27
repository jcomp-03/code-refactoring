# Week 1 Challenge - Code Refactor for Marketing Agency

The purpose of this week's challenge is to refactor existing HTML markup and CSS styling for the website of a marketing agency. In the process, I looked to optimize the HTML structure logic and the suitability of HTML tags for particular segments of the website, and generally to organize and to improve the readability of the existing codebase; additionally, I wished to improve the efficiency of the CSS styling declarations.

Take as an example the existing HTML markup in the screenshot below.

### Screenshot of portion of HTML markup *before* code improvement
![HTML markup before changes](/assets/images/html-pre.PNG)

What was clearly functioning as the header element within the body element was implemented as a div container. While this isn't wrong functionally, semantically the more suitable tag to use is the header tag.

Additionally, the nested div container was converted to a nav element since its purpose is to host the navigation links to sections further down on the webpage. Spacing and line returns were consolidated to improve the readability. The screenshot below shows the same section after code improvement.

### Screenshot of portion of HTML markup *after* code improvement
![HTML markup after changes](/assets/images/html-post.PNG)

In the CSS style sheet, there was an opportunity to improve the specificity of selector statements; a lot of CSS styling was repetitive and could be generalized to decrease the total number of lines of code in the style sheet. For example, the two images below show I am able to condense 24 lines of CSS coding into just 8 (9 if you include the font-family property:value declaration in the body styling section I added).

### Screenshot of portion of CSS stylesheet *before* code improvement
![CSS styling before changes](/assets/images/css-pre.PNG)

### Screenshot of same portion of CSS stylesheet *after* code improvement
![CSS styling after changes](/assets/images/css-post.PNG)
  
  
Comments were added to both the HTML markup as well as the CSS style sheet to give some more context about the changes that were made as well as to inform the code reviewer of what is happening.