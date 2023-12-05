# CodeClauseInternship_Basic_Online_Resume
Step 1 (HTML Code):

To get started, we will first need to create a basic HTML file. In this file, we will include the main structure for our resume builder.


After creating the files just paste the following codes into your file. Make sure to save your HTML document with a .html extension, so that it can be properly viewed in a web browser.


Let's break down the code step by step:


1. <!DOCTYPE html>: This declaration at the very beginning of the HTML document specifies the document type and version being used, which is HTML5 in this case.


2. <html>: The root element that contains the entire HTML document.


3. <head>: This section contains metadata about the document and information for browsers. Inside the <head> element, you have:


<meta charset="utf-8">: Specifies the character encoding for the document as UTF-8, which is a widely used character encoding for handling various character sets.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Suggests to Internet Explorer to use the latest rendering engine available.
<title>Resume/CV Builder</title>: Sets the title of the web page to "Resume/CV Builder," which appears in the browser's title bar or tab.
<meta name="description" content="">: Provides a brief description of the page content. The content attribute is empty in this case, but it can be filled with an actual description.
<meta name="viewport" content="width=device-width, initial-scale=1">: Defines the viewport settings for responsive web design. It ensures that the webpage adapts to the width of the device's screen.
<link>: These <link> elements are used to include external CSS stylesheets. One links to the Bootstrap CSS framework, and the other links to a custom stylesheet named "styles.css."

4. <body>: The main content of the web page is placed within the <body> element. It contains various elements, including buttons, forms, and sections for building a resume.


<div class="nav">: This <div> represents a navigation bar at the top of the page. It contains buttons for actions like downloading, saving, and returning to the home page.
<div class="resume" id="resume">: This <div> represents the main content area for building a resume. Inside it, there's a <section> element with the id "print," which presumably contains the resume content.
Within the "resume" section, there are various sub-sections and elements for entering and displaying information related to a person's resume. These include name, contact details, skills, languages, achievements, interests, profile, education, and a customizable "new section."

5. <script>: These <script> elements are used to include JavaScript files for interactivity. One script includes jQuery, a popular JavaScript library. The second script includes html2pdf.js, a library for generating PDFs from HTML content. The third script includes a custom JavaScript file named "script.js," which contains functions and logic for handling user interactions and resume generation.


This is the basic structure of our resume builder using HTML, and now we can move on to styling it using CSS.


Step 2 (CSS Code):

Once the basic HTML structure of the resume builder is in place, the next step is to add styling to the resume builder using CSS.


Next, we will create our CSS file. In this file, we will use some basic CSS rules to style our builder.


Let's break down what each part of the code does:


1. @import statements:


These statements import external CSS stylesheets from Google Fonts. They load the "Raleway" and "Barlow" fonts with specific font weights and display options.

2. * selector:


This selector applies styles to all elements on the page.
It sets margin and padding to 0%, font weight to 500, and font size to 14px for all elements.

3. body selector:


This selector styles the <body> element.
It sets the background to a linear gradient, centers content both vertically and horizontally using display: grid and place-items: center, and changes the font weight to 450 and opacity to 1.

4. .none and .resume selectors:


These selectors are used to style elements with the class .none and .resume, respectively.
.none sets the display property to none, effectively hiding elements with this class.
.resume styles elements with a specific width and adds a box shadow.

5. #print selector:


This selector styles an element with the ID print.
It sets a white background, padding, and a fixed height.

6. .head, .main, .contacts, and .line selectors:


These selectors style different sections of the page's header.
.head and its children define a grid layout for the header.
.main styles the main section of the header with different fonts and styles for the name and post.
.contacts aligns and styles the contact information.
.line adds a horizontal line with a gray background.

7. .mainbody, .border, .title, .skill, .button, .language, .edublock, and .education-head selectors:



These selectors style various elements within the main body of the page.
.mainbody defines a grid layout for the main content area.
.border creates a vertical line with a gray background.
.title styles section titles with a green-yellow bottom border.
.skill, .button, .language, and .edublock style different content sections.
.education-head styles the headings within the education section.

8. .navbtn and .input-checkbox selectors:


These selectors style navigation buttons and input checkboxes.
.navbtn creates circular buttons with a border and shadow and adjusts their positioning.
.input-checkbox adds some margin to checkboxes.

This will give our resume builder an upgraded presentation. Create a CSS file with the name of styles.css and paste the given codes into your CSS file. Remember that you must create a file with the .css extension.
