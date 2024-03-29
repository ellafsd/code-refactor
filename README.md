# code-refactor
Embarking on a digital accessibility odyssey! 🚀
Project Title
Module 1 Challenge: Enhancing Web Accessibility

Project Description
HTML and CSS Challenge to increase the accessible of the given web page 

User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

Implementation Details
Header and Navigation: I replaced the non-semantic <div class="header"> with a semantic <header> element to define the introduction and navigational part of the webpage. Inside the <header>, I used the <nav> element to encapsulate navigation links, making it easier for assistive technologies to identify the site's main navigation area.
Main Content Area: The central content was wrapped in a <main> element instead of a generic <div>. This marks the content as the main body of the document, aiding assistive devices in finding the primary content quickly.
Aside for Side Content: I utilized the <aside> element to wrap the side content, which typically consists of information tangentially related to the main content, like benefits in this case. 
Footer: Lastly, the footer of the page was semantically marked up with the <footer> element, defining it as the closing content of the page. This helps in providing a consistent navigational structure.


