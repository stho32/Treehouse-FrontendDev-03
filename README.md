# Treehouse-FrontendDev-03

See the results here: Github-Pages-Link (will be replaced as soon as the project is complete)

## Todos

  - mobile-form.png is an example of how the layout should look on a mobile phone that’s 320 pixels wide.
  - desktop-form.png is an example of how the layout should look on tablet and desktop screens that are at least 768 pixels wide.

  
  - [X] Build the layout using a mobile first design:

    - [X] Make sure the HTML file includes the viewport meta tag in the head of the document, see Configuring the Viewport to understand why and how to add this tag.
    - [X] Look at the provided mockup (mobile-form.png) and add the same content to your index.html file.

  - NOTE: It's okay if your checkboxes and radio buttons don't match the look of those in the mockups. It's perfectly fine to use the standard default radio buttons and checkboxes.
  
  
  - [X] Create the form structure:

    - [X] Only use one <form> tag. The <form> tag should contain all the form elements. Add a fieldset and legend for each of the following sections:
      - [X] "Contact Information" section of the page, and
      - [X] The "Newsletter" section of the page

    - NOTE: You don't need to make a functioning form -- that is, it doesn't have to do anything when the form is submitted. To do that, you'd need to add some server-side programming to actually process the user's input.
    
  - [X] Make sure you include the following form field types:

    - [X] text input
    - [X] email input
    - [X] telephone input
    - [X] select menu
    - [X] checkboxes
    - [X] radio buttons
    - [X] textarea
    - [X] submit button


  - [X] Form fields should include the following attributes:

    - [X] input: should include id, type and name attributes.
    - [X] select and textarea: should include id and name attributes.
  
    - NOTE: 
      - Checkboxes should have identical name attributes but unique value attributes
      - Radio Buttons should have identical name attributes but unique value attributes   

  - [X] Add labels to each form element using the HTML <label> tag. The text inside the labels should match the names of the form fields in the mockups.
    - [X] Make sure you properly pair each <label> element with its corresponding form control via the for attribute. See the link above for an example. And don't forget about the textarea element. That needs a functioning label too.
    - [X] NOTE: Remember that to associate a label with a form input element, the label’s “for” attribute should match the input’s unique id.
      
  - [X] Use the input field's placeholder attribute to add the text "required" to:
    - [X] the Full Name field
    - [X] the Email address field


  - [X] Once you have everything in place for the mobile layout, use a media query to add a breakpoint to adjust the layout for wider tablet and desktop screens.
    - [X] Match the design as it should look on a tablet or desktop that is 768px wide using the desktop-form.png mockup.
    - [X] Use a mobile-first approach by writing your media queries using the min-width property in your CSS.


  - [X] Once all your breakpoints are in place, double check your layout matches both the mockups.
    - [X] Check that the label text position matches both mockups:
    - [X] Mobile: Text should be above the form field.
    - [X] Desktop: Text should be to the left side of the form field.

  - [X] Use a Google Font for the text. The design uses the "Merriweather" font but, you can use any Google Font that you'd like.
  - [ ] Add :focus states to the form for when a user clicks or tabs into a text field.


  - [ ] Make sure to check your code is valid by running it through an HTML and CSS validator.

    - [ ] Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
    - [ ] There are a few exceptions that you don’t need to fix:
      - [ ] Don’t worry about any warnings, we just need you to check any errors that might be there.
      - [ ] If CSS validator flags use of calc, vendor prefixes or pseudo-elements/pseudo-classes these errors should be ignored.
      - [ ] If HTML validator flags use of pipe (‘|’) in Google font links/URLs this error can also be ignored.


  - [ ] NOTE: A good practice is to check your project for cross browser compatibility. Making sure that it looks and functions correctly in multiple (at least three) browsers is an important part of being a top-notch developer. If you want, leave a comment to the project reviewer about which browser(s) the project was checked to ensure they are seeing things as you have designed them.
    - [ ] Some browser options:
      - [ ] Google Chrome
      - [ ] Mozilla Firefox
      - [ ] Internet Explorer/Edge
      - [ ] Safari


## Validation

### Form Structure

  - [ ] Only one <form> tag is being used to contain all the form elements.
    - [ ] Fieldsets and legends have been added for each of the following sections:
      - [ ] "Contact Information" section of the page, and
      - [ ] The "Newsletter" section of the page

### Form fields and labels

  - [ ] Includes all of the required form fields:
    - [ ] text input
    - [ ] email input
    - [ ] telephone input
    - [ ] select menu
    - [ ] checkboxes
    - [ ] radio buttons
    - [ ] textfield
    - [ ] submit button
  - [ ] Each form field includes the following attributes:
    
    - [ ] _`input`:_ has `id`, `type` and `name` attributes.
    - [ ] _`select`_ and _`textarea`:_ includes `id` and `name` attributes.
  - [ ] Each form field includes a label, and each label’s `for` attribute is associated with a unique `id` on its corresponding form field.

### Placeholder text

  - [ ] The input field's placeholder attribute has been used to add the text "required" to:
      - [ ] the Full Name field
      - [ ] the Email address field


### Mobile first

  - [ ] The HTML file include the viewport meta tag in the head of each document.
  - [ ] A mobile-first approach is utilized using min-width properties for media queries.
  - [ ] Appropriate media query is in place to match the screen size for tablet and desktop screens at 768px.

### Design and styling

  - [ ] Roughly matches layout of the mobile and desktop mockups. General spacing and arrangement of the elements matches the design of the mockups for:
    - [ ] Mobile
    - [ ] Desktop
  - [ ] The label text position matches the mockups:
    - [ ] Above the form field for mobile.
    - [ ] To the left side of the form field for desktop.
  - [ ] Uses a Google Font.
  - [ ] Includes focus states for text fields.

  - [ ] (+) BOTH of the following additional styling enhancements have been added to the form:
    - [ ] (+) Change the background color for at least ONE of the main sections of the site.
    - [ ] (+) Uses CSS transitions for focus states.

### Valid code 

  - [ ] HTML and CSS code passes the validation.
  - [ ] HTML and CSS errors are accepted exceptions.


