# Sarah Cahill Portfolio Website - T1A1

**Website:**
**Github:**

####Purpose
The purpose of this website is to showcase my skills, projects, work and employment history and personal information to prosepective employers. This ongoing work in progress allows me to have an online presence that can be continuously updated as I learn new skills, and will assist in gaining future employment. The website has been designed to be responsive, ease of use in navigation and ease of access for differently abled users.

####Functionality and Features
**Drop down menu**
The drop down menu is consistently located on the top right corner of each page. The menu button shows a pointer hover, and changes colour when clicked. The dropdown components show a different hover colour (using opaque colours for ease of reading). The menu bar does not contain a link to the page being visited, so not to be repitious. 

**Home page buttons**
These aim to provide the user an extra incentive to click through to other pages, and make a feature of them on the homepage. These buttons also have a hover feature.

**Headers and Footers**
Headers appear consistent with font and styling on each page, with the home page being more stylised for name.
The footer bar is consistent on each page, with the homepage footer giving credit to image sources. 

Component 3: CV Download
Visitors to the website have the ability to download a PDF copy of my CV. This will allow them to incorporate my information into their file systems or show other relevant persons without needing to visit the website repeatedly.

A CV download button exists at the bottom of the CV page. The link is large, bolded text which is the only text of its type on the page. A yellow hover using the same styling as the navigation bar hover signals to the user that it is interactable.

The text "DOWNLOAD CV" takes the imperative voice as if a command, and this represents a call to action for the user.

Lastly, the CV opens in a separate tab so the user does not lose their place on the website and can easily return (simply by clicking back to the tab) and continue engaging with the website.

Component 4: Accessibility
Attention has been paid to the ability of visually-impaired individuals to use the website. This takes the form of providing alt-text for any images on the page, and ensuring that the contrast between elements on the page is high and does not use a colour scheme which would be a problem for color-blind visitors (e.g. red-green colour-blindness).

Acessibility was checked using the Audit function built into the Google Chrome developer tools. Separate audits were conducted for all four webpages. Audit scores of 100 were attained for all webpages.

Accessibility

A Consistent Style
All webpages use a consistent style, including components, fonts, colours, and themes:

The navigation bar, the banners with the name of the webpage, and the buttons to LinkedIn and Github are components which are on every page of the website.
The Poppins font is used for headers and Rubik is used for other text such as paragraphs. These sans-serif fonts were selected for their legibility and modern appearance.
The colour scheme of the website is blue with yellow accents and heavy use of whitespace.
Use of futuristic imagery in the banners of each page provide a unifying theme.
All banner images were tinted blue to conform to the colour theme of the website.
Semantic HTML
HTML elements have been named to enhance the readability of the code. For example, HTML tags such as nav, p, and footer have been used and comments have been added to the HTML document to describe the meaning of each block of code.

Additionally, the classes and id's used in CSS have been named in a way which is intended to enhance readability. For example the class 'flex-centered' includes the name 'flex' because it creates a flexbox using display: flex, and it centers the content which is childed to it using justify-content: center and align-items: center.

Responsive Design
As visitors to the site may use a multitude of devices, the website has been designed to function well on screens of different sizes.

This has been accomplished by the use of CSS Flexbox, which allows control over the positioning of elements in response to a change in screen size. The website is designed to display correctly on a device as small as an iPhone 5/SE, which has a width of 320 pixels. When the screen width is over 900 pixels, the elements of the website no longer expand to fill the space, instead leaving whitespace on the left and right of the screen.

By checking that components are displaying correctly on the smallest smartphones and wide screens such as desktop monitors, the website is viewable by the widest audience.

Three Versions
Three versions of the website have been produced and saved on different branches in Github. These versions are:

'master' branch with the base version
'dark' branch with a dark colour scheme
'no-graphics' branch with the banner graphics removed
Alternate versions can be viewed by typing 'git checkout {branch-name}' in the terminal. For example to view the 'dark' branch, type:

git checkout dark

Subresource integrity
Subresource integrity ensures that the files delivered to your web application do not have any unexpected content such as malicious code injected by a third party.

This has been achieved by creating a hash using sha512 and using this hash as the value of the integrity attribute of our link tag. This ensures that styles.css will only load if it is identical to its state when the sha512 hash was created. If any changes have been made, the stylesheet will not be loaded and the HTML page will be displayed with no CSS styling.

Sitemap
The website simply has all pages link to each other via the navigation bar. A sitemap for the website is presented below.

Sitemap

Screenshots
Home page
screenshot_home

Projects page
screenshot_projects

CV page
screenshot_cv

Target audience
The target audience for the website falls into two categories:

Employers
Project Leads
The website is intended as a showcase of my abilities as a software developer and designer. The most likely use of the website is to provide as evidence of ability alongside a traditional application for employment. Additionally, employers or those leading other projects may chance upon the website and consider me for employment or inclusion in their projects.

Tech stack
HTML is used for the content of all webpages
CSS is used for the styling and positioning of elements.
Netlify is used for web-hosting.
Project Management
Wireframes
Wireframes were created for each page for mobile and desktop screen widths during the planning phase of the project. Considering that four HTML pages were required, this meant that eight wireframes were created in total. These are presented below.

Homepage
wireframe_1

Projects
wireframe_2

Blog
wireframe_3

CV