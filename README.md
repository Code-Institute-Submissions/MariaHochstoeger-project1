# Himanshu Giri - Psychotherapy Practice

![responsive mock-up] ()

This is the website of Dr. Himanshu Giri, an English- and Hindi-speaking psychotherapist with a practice in Vienna, Austria. He also offers sessions online.
The site is targeted at adults who are seeking professional help in overcoming mental challenges and want to find out whether Dr. Giri could be the right person to provide the support they seek.

## Design

The site was created with persons in mind who, possibly in a time of distress, are looking for help in the form of psychotherapy. The necessary information should be easy to find and give the visitor a good picture of who Dr. Himanshu Giri is and what he can offer. At the same time, a good balance needs to be struck so as to not reveal too much information as the therapist and his/her background should not interfere with the therapy process.

### Wireframes

The first wireframes were made in Balsamiq. Laptop screen sizes were chosen for the mock-up in order to have an overview of all information which needed to be added. A mockup of a mobile screen was also added since the site was then built using the mobile-first approach.

### Font and Colour Choices
**Fonts:** 'REM' was chosen as the headings font for its professional yet not intimidating look. 'Poppins' makes up the main part of the site due to it being a quite neutral but still friendly font.

**Colours:** The colour palette was generated using mycolor.space. The base colour was picked from the header picture (taken from Pexel) which shows a blue sky with some whispy clouds. This particular colour palette was chosen for its calming blue tones.

## Features

The site has very basic features of a static website.

- **Navigation Bar**
    - The navigation bar is always visible on all pages. In the top left corner the logo is a link which brings the user back to the home page, as a user would expect it to.
    - The page which is currently active is underlined in the header.
    - Depending on the screen format, the navigation bar is split into two lines or spaced onto a single line (tablets and wider).

- **Main section**
    - The structure of the main content is consistent throughout the pages to make them easy to understand and navigate with subheaders giving cues about the content of the individual parts.
    - Content varies depending on the page. Texts are kept short to help the user find information quickly.

- **Home page**
    - A picture of Dr. Himanshu Giri greets the user to give them a feeling for who he might be. It is rounded for a softer look.
    - The welcome text gives the user a first understanding of what Dr. Giri offers.
    - Layout is vertical for smaller screens and horizontal to make good use of larger screens.

-**About page**
    - The informations that site visitors will mostly look for is listed in clear lists, using bullet points where too many items make up the list.
    - Layout is vertical for smaller screens and horizontal to make good use of larger screens.

-**Contact page**
    - A form encourages visitors to leave their contact details for Dr. Giri to get in touch with them directly.
    - Should the site visitor choose to contact Dr. Giri themselves, they are provided with the address, electronic and phone details. The email address is provided as a link.

### Possible Future Features

- Make the costs on the about page into a table


## Bugs

- Imported Google Fonts into html via <link>. This caused css-classes and -ids to not be applied. Fixed it by removing Google Fonts link from index.html and instead importing Google Fonts into style.css.
- Fixed flexbox-styling by applying differently colored borders to better understand the individual elements' behaviours
- The boxes on the about page wouldn't 

## Sources

- Love Running walk-through project for basic structures of header and footer
- Favicon was generated using favicon.cc 

----

## Credits
- Holly from Tutor Support for spotting a space in the import of my Google Fonts which caused problems with my styling
- https://css-tricks.com/dont-overthink-flexbox-grids/ for helping me figure out how to get the flexbox on my about page to produce same-width children
- https://www.w3schools.com/cssref/pr_list-style-position.php for helping me get the bullet points of my list inside the flex container
