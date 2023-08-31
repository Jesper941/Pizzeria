## CONTENTS

- [CONTENTS](#contents)
- [AUTOMATED TESTING](#automated-testing)
  - [W3C Validator](#w3c-validator)
  - [Full Testing](#full-testing)
- [Bugs](#bugs)
  - [Known Bugs](#known-bugs)
  - [Solved Bugs](#solved-bugs)

Testing was ongoing throughout the entire build. i took help from the Chrome developer tools while building to pinpoint and troubleshoot any issues as i was building the website.

I have gone through each page using google chrome developer tools to ensure that each page is responsive on a variety of different screen sizes and devices.

- - -

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

* [Index Page] ( Pass - Checked the "index.html" using https://validator.w3.org/nu/#textarea )
* [Menu Page] ( Pass - Checked the "menus.html" using https://validator.w3.org/nu/#textarea )
* [Index Page] ( Pass - Checked the "findus.html" using https://validator.w3.org/nu/#textarea )
* [Style.css] ( Pass . Checked the "style.css" using )
  
- - -

### Full Testing

Full testing was performed on the following devices, and additional testing for other devices was carried out using developer tools:

iMac 2021, MacBook Pro 14 inch 2021, iPhone 13 Pro, Samsung S20, 25 inch monitor, windows laptop

Each device tested the site using the following browsers:

Google Chrome on Mac and Windows, Safari

`Index Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| `Navbar` |
| Home Link | Redirects to home page | Click home link | Redirects to home page | Pass |
| Menu Link | Redirects to menu page | Click menu link | Redirects to home page | Pass |
| Login Link (user not logged in) | Redirect to Login page | Click log in link | Redirected to log in page | Pass |
| Sign up Link (user not logged in)  | Redirect to Sign up page | Click sign up link | Redirected to sign up page | Pass |
| View all posts link | Redirects the user to the all threads page | Click view all posts link | Redirected to all posts page | Pass |
| Admin View | Redirects to the admin view page | Click admin view link | Redirected to admin view page | Pass |
| Logout link (user logged in) | User will be logged out | Click log out link| Redirected to home page - login link available | Pass |
| `Home Page` |
| View threads button | Redirects to the threads page | Click button | Redirected to the thread | Pass |
| Start a new thread button | Modal popup to create new thread | Click button | New thread modal popped up | Pass |
| `Login Page` |
| Form - link to sign up page | Redirects user to sign in page | Click link | Redirected to sign up page | Pass |
| Form - Submission with no information | User prompted to fill in information | clicked submit button with no fields filled out | Form highlighted first empty field | Pass |
| `Signup Page` |
| Form - Submission with no information | User prompted to fill in information | clicked submit button with no fields filled out | Form highlighted first empty field | Pass |
| `New Post Page` |
| --- | --- | --- | --- | --- |
| `New Thread Page` |
| --- | --- | --- | --- | --- |
| `Threads Page` |
| --- | --- | --- | --- | --- |
| `Admin Posts Page` |
| --- | --- | --- | --- | --- |
| `Privacy Policy Page` |
| Link to Terms & Conditions Page | Redirects user to the Terms & Conditions page | Click link | Redirected to the terms & conditions page | Pass |
| Get Safe Online link | Redirects the user to the get safe online website in a new browser tab | Click link | site opens, but in same browser tab | Fail |
| Link to Rocket Lawyer site in Attribution section | User is taken to the Rocket Lawyer site in a new browser tab | Click link | Rocket Lawyer site opens, but in same tab | Fail |
| `Terms and Conditions Page` |
| Link to Rocket Lawyer site in Attribution section | User is taken to the Rocket Lawyer site in a new browser tab | Click link | 404 page opens | Fail |
| `404 Page` |
| (User Logged in) Home Button | User will be redirected to the home page | Click home button | Redirected to the home page | Pass |
| (Guest User) Login Button | User redirected to the login page | Click login button | Redirected to the login page | Pass |
| (Guest User) Sign Up Button | User redirected to the sign up page | Click sign up button | Redirected to sign up page | Pass |
| `Footer` |
| Footer - Join now button | Redirects user to the sign up page | Click button | Redirected to sign up page | Pass |
| Footer - Social media links | Opens new tab to the social media site | Clicked each icon | New tabs opened for each site | Pass |
| Footer - Privacy Policy link | Redirects to the privacy policy page | Clicked link | Redirected to privacy policy page | Pass |
| footer - Terms and conditions link | Redirects to the terms and conditions page | Clicked link | Redirected to terms and conditions page | Pass |
|  |  |  |  |  |
| **CONTACT US** |  |  |  |  |
|  |  |  |  |  |
| Submit Form Button - No information entered by user | The form will direct the user to fill in the name field | Clicked submit button with no information filled in | Asked to fill in name field | Pass |
| Submit Form Button - Some information entered | User will be directed to fill in the fields they have left blank | Filled in only part of the form | Asked to fill in the missing fields | Pass |
| Submit form button - all fields filled out | Modal pop up with message confirming message successfully sent | Filled in all forms and pressed submit | Modal popped up with success message | Pass |
| Submit button - hover | when hovered over the button changes colour | Hovered over button | Button changed colour | Pass |
| Name input - focus | When input field is clicked on the border of the input field will change colour | Clicked on input field | Border changed colour | Pass |
| Email input - focus | When input field is clicked on the border of the input field will change colour | Clicked on input field | Border changed colour | Pass |
| Text Area - focus |When text area is clicked on the border of the text area will change colour | Clicked on text area | Border changed colour | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

`Climate Change Charities Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| Logo image link | When clicked you are redirected to the home page | Clicked Logo | Redirected to home page | Pass|
| Navbar home link | When clicked you are redirected to the home page | Clicked link | Redirected to home page | Pass |
| Navbar home link - Hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar quiz link | When clicked you are redirected to the Quiz Section of the home page | Clicked link | Redirected to quiz section of home page | Pass |
| Navbar quiz link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar information link | When clicked you are redirected to the Information section of the home page | Clicked link | Redirected to information section of home page | Pass |
| Navbar information link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar contact us link | When clicked you are redirected to the Contact Us section of the home page | Clicked link | Redirected to contact us section of home page | Pass |
| Navbar contact us link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

`Conservation and Restoration Charities Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| Logo image link | When clicked you are redirected to the home page | Clicked Logo | Redirected to home page | Pass|
| Navbar home link | When clicked you are redirected to the home page | Clicked link | Redirected to home page | Pass |
| Navbar home link - Hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar quiz link | When clicked you are redirected to the Quiz Section of the home page | Clicked link | Redirected to quiz section of home page | Pass |
| Navbar quiz link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar information link | When clicked you are redirected to the Information section of the home page | Clicked link | Redirected to information section of home page | Pass |
| Navbar information link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar contact us link | When clicked you are redirected to the Contact Us section of the home page | Clicked link | Redirected to contact us section of home page | Pass |
| Navbar contact us link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

`End Plastic Pollution Charities Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| Logo image link | When clicked you are redirected to the home page | Clicked Logo | Redirected to home page | Pass|
| Navbar home link | When clicked you are redirected to the home page | Clicked link | Redirected to home page | Pass |
| Navbar home link - Hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar quiz link | When clicked you are redirected to the Quiz Section of the home page | Clicked link | Redirected to quiz section of home page | Pass |
| Navbar quiz link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar information link | When clicked you are redirected to the Information section of the home page | Clicked link | Redirected to information section of home page | Pass |
| Navbar information link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar contact us link | When clicked you are redirected to the Contact Us section of the home page | Clicked link | Redirected to contact us section of home page | Pass |
| Navbar contact us link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

`Environmental Literacy Charities Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| Logo image link | When clicked you are redirected to the home page | Clicked Logo | Redirected to home page | Pass|
| Navbar home link | When clicked you are redirected to the home page | Clicked link | Redirected to home page | Pass |
| Navbar home link - Hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar quiz link | When clicked you are redirected to the Quiz Section of the home page | Clicked link | Redirected to quiz section of home page | Pass |
| Navbar quiz link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar information link | When clicked you are redirected to the Information section of the home page | Clicked link | Redirected to information section of home page | Pass |
| Navbar information link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar contact us link | When clicked you are redirected to the Contact Us section of the home page | Clicked link | Redirected to contact us section of home page | Pass |
| Navbar contact us link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

`Food & Environment Charities Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| Logo image link | When clicked you are redirected to the home page | Clicked Logo | Redirected to home page | Pass|
| Navbar home link | When clicked you are redirected to the home page | Clicked link | Redirected to home page | Pass |
| Navbar home link - Hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar quiz link | When clicked you are redirected to the Quiz Section of the home page | Clicked link | Redirected to quiz section of home page | Pass |
| Navbar quiz link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar information link | When clicked you are redirected to the Information section of the home page | Clicked link | Redirected to information section of home page | Pass |
| Navbar information link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar contact us link | When clicked you are redirected to the Contact Us section of the home page | Clicked link | Redirected to contact us section of home page | Pass |
| Navbar contact us link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

`404 Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| **NAVBAR** |  |  |  |  |
|  |  |  |  |  |
| Logo image link | When clicked you are redirected to the home page | Clicked Logo | Redirected to home page | Pass|
| Navbar home link | When clicked you are redirected to the home page | Clicked link | Redirected to home page | Pass |
| Navbar home link - Hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar quiz link | When clicked you are redirected to the Quiz Section of the home page | Clicked link | Redirected to quiz section of home page | Pass |
| Navbar quiz link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar information link | When clicked you are redirected to the Information section of the home page | Clicked link | Redirected to information section of home page | Pass |
| Navbar information link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
| Navbar contact us link | When clicked you are redirected to the Contact Us section of the home page | Clicked link | Redirected to contact us section of home page | Pass |
| Navbar contact us link - hover | When hovered over a line will appear under the link | Hovered over link | Line appeared under link | Pass |
|  |  |  |  |  |
| **PAGE BUTTONS** |  |  |  |  |
|  |  |  |  |  |
| Go back home button | When clicked you are redirected to the home page | Clicked button | Redirected to home page | Pass |
| Go back home button - hover | When hovered over the button will change colour | Hovered over button | Button changed colour | Pass |
| Take quiz button | When clicked you are redirected to the quiz section on the home page | Clicked button | Redirected to the quiz section of the home page | Pass |
| Take quiz button - hover | When hovered over the button will change colour | Hovered over button | Button changed colour | Pass |
| Information button | When clicked you are redirected to the information section on the home page | Clicked button | Redirected to the information section of the home page | Pass |
| Information button - hover | When hovered over the button will change colour | Hovered over button | Button changed colour | Pass |
| Contact us button | When clicked you are redirected to the contact us section on the home page | Clicked button | Redirected to the contact us section of the home page | Pass |
| Contact us button - hover | When hovered over the button will change colour | Hovered over button | Button changed colour | Pass |
|  |  |  |  |  |
| **FOOTER** |  |  |  |  |
|  |  |  |  |  |
| Alaa GitHub Icon | When clicked you will be redirected to Alaas GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Alaa Linked In Icon | When clicked you will be redirected to Alaas Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Alaa Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian GitHub Icon | When clicked you will be redirected to Cillians GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Cillian GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Cillian Linked In Icon | When clicked you will be redirected to Cillians Linked In profile in a new tab | --Clicked icon- | Profile opened in a new tab | Pass |
| Cillian Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle GitHub Icon | When clicked you will be redirected to Janelles GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Janelle Linked In Icon | When clicked you will be redirected to Janelles Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Janelle Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John GitHub Icon | When clicked you will be redirected to Johns GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| John Linked In Icon | When clicked you will be redirected to Johns Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| John Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera GitHub Icon | When clicked you will be redirected to Keras GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Kera Linked In Icon | When clicked you will be redirected to Keras Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Kera Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor GitHub Icon | When clicked you will be redirected to Trevors GitHub profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor GitHub Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |
| Trevor Linked In Icon | When clicked you will be redirected to Trevors Linked In profile in a new tab | Clicked icon | Profile opened in a new tab | Pass |
| Trevor Linked In Icon - hover | When hovered over a line will appear under the icon | Hovered over icon | Line appeared | Pass |

## Bugs

### Known Bugs

| Known Bug No | Bug Issue | Plan to Resolve |
| :--- | :--- | :--- |
| 1 |  | :--- |

### Solved Bugs

| Bug No | Bug Issue | How Resolved |
| :--- | :--- | :--- |
| 1 |  | :--- |