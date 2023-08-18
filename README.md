# Himanshu Giri - Psychotherapy Practice 

![responsive mock-up] (https://github.com/MariaHochstoeger/project1/blob/main/assets/images/readme-images/Mockup%20different%20devices.png)

This is the website of Dr. Himanshu Giri, an English- and Hindi-speaking psychotherapist with a practice in Vienna, Austria. He also offers sessions online.
The site is targeted at adults who are seeking professional help in overcoming mental challenges and want to find out whether Dr. Giri could be the right person to provide the support they seek.

Visit the site [here] (https://mariahochstoeger.github.io/project1/index.html).

## Design

The site was created with persons in mind who, possibly in a time of distress, are looking for help in the form of psychotherapy. The necessary information should be easy to find and give the visitor a good picture of who Dr. Himanshu Giri is and what he can offer. At the same time, a balance needs to be struck so as to not reveal too much information as the therapist and his/her background should not interfere with the therapy process.

### Wireframes

The first wireframes were made in Balsamiq. Laptop screen sizes were chosen for the mock-up in order to have an overview of all information which needed to be added. A mockup of a mobile screen was also added since the site was then built using the mobile-first approach.

### Font and Colour Choices
**Fonts:** 'REM' was chosen as the headings font for its professional yet not intimidating look. 'Poppins' makes up the main part of the site due to it being a quite neutral but still friendly font.

**Colours:** The colour palette was generated using mycolor.space. The base colour was picked from the header picture (taken from Pexel) which shows a blue sky with some clouds. This particular colour palette was chosen for its calming blue tones.

## Features

The site has the very basic features of a static website.

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

- **About page**
    - The informations that site visitors will mostly look for is listed in clear lists, using bullet points where too many items make up the list.
    - Layout is vertical for smaller screens and horizontal to make good use of larger screens.

- **Contact page**
    - A form encourages visitors to leave their contact details for Dr. Giri to get in touch with them directly.
    - Should the site visitor choose to contact Dr. Giri themselves, they are provided with the address, email and phone details. The email address is provided as a link.
    - On larger screens, the contact information changes order and is displayed horizontally for a cleaner look.

- **Footer**
    - The footer contains three icons which link to external social media sites.
    - The links open in new tabs, making it easy for users to come back to the site of Dr. Giri.
    - The footer is consistent throughout the pages.

### Possible Future Features

- Include a video

    Dr. Giri has given a Ted Talk. I would like to embed this video directly on the about page.

- Streamline the about page

    Make the costs on the about page into a table giving an easier overview to the site visitor.

- Give the user more options with the form

    I would like to give the site visitor the option to choose whether they would like to be contacted via email or via phone, and if phone, at which times.

## UX

### Site Goals

The site wants to attract people who face mental or psychological challenges in their lives and are looking for professional help from a qualified psychotherapist. Particularly, the site should speak to English- or Hindi-speaking people located in Vienna, or who would like to try psychotherapy online. 

### User Stories

**As a site visitor:**

- I want to confirm that Dr. Giri is a qualified psychotherapist.
- I want to know which languages Dr. Giri speaks.
- I want to learn about the types of sessions he offers.
- I want to know how much a session costs.
- I want to find out whether Dr. Giri specializes in the field which applies to me.
- I want to see where Dr. Giri is located.
- I want to be able to get in contact with Dr. Giri in the manner that I choose to.
- I want to see a mobile-friendly layout and responsive design.

**As the site administrator:**

- I want to be able to easily update information such as pricing or location.
- I want to be able to add new content such as videos.

## Testing

- I confirmed that this project is responsive and looks good on various common screen sizes by using the devtools devices toolbar.
- I have confirmed that the form works and each field is required. There are error messages if a field is not filled out. If it is filled incorrectly, such as an @ missing in an email, or the phone number field containing letters, there are appropriate error messages.
- I confirmed that header and navbar are easily readable and understandable.

### Bugs

- Imported Google Fonts into html via <link>. This caused css-classes and -ids to not be applied. Fixed it by removing Google Fonts link from index.html and instead importing Google Fonts into style.css.
- Fixed flexbox-styling by applying differently colored borders to better understand the individual elements' behaviours. Border colors were removed after fixing the styling.

### Unfixed Bugs

- None.

### Validator Testing

- HTML ([W3C Validator] (https://validator.w3.org/))
    - No error found.

- CSS ([Jigsaw] (https://jigsaw.w3.org/css-validator/))
    - No error found.

- Performance, Accessibility, Best Practices, SEO (Lighthouse Chrome Dev Tools)
    - 

### Browser Testing (section taken from Kay Welfare, results are my own)

**Layout:** Testing layout and appearance of site for consistency throughout browsers.

**Functionality:** Ensuring all links, navigation and form submit functions as expected throughout browsers.

| Browser     | Layout      | Functionality |
| :---------: | :----------:| :-----------: |
| Chrome      | ✔          | ✔             |
| Edge        | ✔          | ✔             |
| Firefox     | ✔          | ✔             |
| Safari      | not available to me         |
| IE          |deprecated by Microsoft, not tested|



## Sources

- Love Running walk-through project for basic structures of header and footer
- Favicon was generated using favicon.cc 
- The mock-up image of the site on different devices was generated using techsini.com


----

## Credits
- Holly from Tutor Support for spotting a space in the import of my Google Fonts which caused problems with my styling
- https://css-tricks.com/dont-overthink-flexbox-grids/ for helping me figure out how to get the flexbox on my about page to produce same-width children
- https://www.w3schools.com/cssref/pr_list-style-position.php for helping me get the bullet points of my list inside the flex container
- Our group facilitator, Kay Welfare, for her patience and genuine efforts to help. And for not getting tired to repeat certain points over and over again.
- Again, Kay Welfare, for sharing her readme with us.
