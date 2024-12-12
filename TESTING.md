<div>
<img src="assets/images/dj-silver-soul-logo.svg" alt="DJ Silver Soul Logo" style="width: 200px; padding-bottom: 20px;">
</div>

# <span style="color: #d27d60">Testing</span>

---

![DJ Silver Soul website shown in a variety of screen sizes](documentation/dj-silver-soul-responsive.webp)

Visit the deployed site here: [DJ Silver Soul](https://sd-powell.github.io/portfolio_project_1/)

---

## CONTENTS

* [AUTOMATED TESTING](#)
  * [W3C Validator](#)
  * [W3C CSS Validator](#)
  * [Lighthouse](#)
* [MANUAL TESTING](#)


Testing was conducted continuously throughout the development process to ensure a functional and user-friendly website. Chrome Developer Tools were extensively utilised during the build to identify and resolve issues promptly. Regular testing allowed for a smoother development process and ensured the final product met quality standards.

Throughout the development process, ChatGPT was utilized as a valuable resource for brainstorming ideas, refining content, and troubleshooting challenges. By offering alternative solutions and best practices, ChatGPT contributed significantly to the website’s overall quality and functionality.

Each page is tested using Chrome Developer Tools to ensure that it is responsive on a variety of different screen sizes and devices.

---

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website.

| Directory                             | File tested  | Screenshot                                           | Notes                            |
| ------------------------------------- | ------------ | ---------------------------------------------------- | -------------------------------- |
| documentation/testing-w3-index.webp   | index.html   | ![screenshot](documentation/testing-w3-index.webp)   | no errors occurred when checking |
| documentation/testing-w3-about.webp   | about.html   | ![screenshot](documentation/testing-w3-about.webp)   | no errors occurred when checking |
| documentation/testing-w3-booking.webp | booking.html | ![screenshot](documentation/testing-w3-booking.webp) | no errors occurred when checking |
| documentation/testing-w3-success.webp | success.html | ![screenshot](documentation/testing-w3-success.webp) | no errors occurred when checking |

---

### CSS Validator

[CSS W3C Validator](https://jigsaw.w3.org/css-validator/) was used to validate my CSS file.

| Directory                                | File tested  | Screenshot                                              | Notes                            |
| ---------------------------------------- | ------------ | ------------------------------------------------------- | -------------------------------- |
| documentation/testing-w3css-success.webp | style.css    | ![screenshot](documentation/testing-w3css-success.webp) | no errors occurred when checking |

---

### Lighthouse

I've tested my deployed project using the Lighthouse Audit tool to to test the performance, accessibility, best practices and SEO of the website.

| Page    | Mobile                                                      | Desktop                                                      | Notes |
| ------- | ----------------------------------------------------------- | ------------------------------------------------------------ | ----- |
| Home    | ![screenshot](documentation/lighthouse-mobile-home.webp)    | ![screenshot](documentation/lighthouse-desktop-home.webp)    | Works as expected.  |
| About   | ![screenshot](documentation/lighthouse-mobile-about.webp)   | ![screenshot](documentation/lighthouse-desktop-home.webp)    | Works as expected. |
| Booking | ![screenshot](documentation/lighthouse-mobile-booking.webp) | ![screenshot](documentation/lighthouse-desktop-booking.webp) | Works as expected. |
| Success | ![screenshot](documentation/lighthouse-mobile-success.webp) | ![screenshot](documentation/lighthouse-desktop-success.webp) | Works as expected. |

---

## MANUAL TESTING

### Testing User Stories

`First Time Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| As a new site user, I want to learn about the DJ’s background, style, and experience so that I can connect with their journey and understand why they’re the right choice for my event or music needs. | The site provides a comprehensive narrative of the DJ's journey, specialties, and passion for music, helping users decide if the DJ aligns with their preferences. |
| As a new site user, I want to browse and listen to sample mixes or sets to understand the DJ’s style and see if it suits my preferences or event. | The Mixes section directly addresses the need for visitors to explore the DJ's work before making a decision. |
| As a new site user, I want to clearly understand what makes the DJ unique, so that I can decide if their style and services match my event needs. | The combination of narrative (About Page) featuring the DJ's story and tangible proof of their work and style (Mixes Section) allows the user to decide what makes the DJ unique. |
| As a new site user, I want to fill out a booking inquiry form with event details, so I can get a response with availability and pricing. | The booking form reinforces the DJ's adaptability and ability to tailor sets to event needs, complementing the user’s decision-making process. |
| As a new site user, I want to see links to the DJ’s social media profiles so I can follow and engage with the DJ on different platforms. | The site provides the user with the opportunity to connect with the DJ on social media using the links in both the navbar, footer amd mixes section. |

`Returning Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| As a returning site user, I want quick access to the DJ’s contact details so that I can reach out directly for repeat bookings. | The site provides a link to the booking page in both the header and footer for easy access to the user. |
| As a returning site user, I want to share a link to share the site with friends, family, or colleagues who might need a DJ. | The user is able to bookmark or share the link to the site, or social media links, with their contacts you might require a DJ. |
| As a returning site user, I want to access the social media profiles or any other content tied to the DJ's professional presence. | The DJ's social media links are displayed on the navbar, footer and mixes section for easy access to the user. |
| As a returning site user, I want to revisit the site for inspiration, such as reading about the DJs style or listening to the latest mixes. | New content can be accessed by the user in the social media links or mixes section. |

---

### Full Testing

Full testing was performed on the following devices:

* Desktop:
  * Mac Studio 2022 LG HDR 4k screen
* Laptop:
  * Macbook Pro 2023 16 inch screen
* Mobile Devices:
  * iPhone 11
  * iPhone 12 pro
  * iPhone XR

  Additional testing was taken by friends and family on a variety of devices and screen sizes.

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Silver Soul logo in navbar | Link directs user back to home page | Clicked on logo | Home page reloads | Pass |
| Home page link in navbar | Link directs user back to home page | Clicked on link | Home page reloads | Pass |
| About page link in navbar | Link directs user to About page | Clicked on link | About page loads | Pass |
| Mixes link in navbar | Link directs user to Mixes section on home page | Clicked on link | Page scrolls to Mixes section | Pass |
| Booking link in navbar | Link directs user to Booking page | Clicked on link | Booking page loads | Pass |
| Instagram link in navbar | Link directs user to Instagram page in new tab | Clicked on link | Instagram page loads in new tab | Pass |
| Facebook link in navbar | Link directs user to Facebook page in new tab | Clicked on link | Facebook page loads in new tab | Pass |
| X(Twitter) link in navbar | Link directs user to X(Twitter) page in new tab | Clicked on link | X(Twitter) page loads in new tab | Pass |
| YouTube link in navbar | Link directs user to YouTube page in new tab | Clicked on link | YouTube page loads in new tab | Pass |
| Spotify link in navbar | Link directs user to Spotify page in new tab | Clicked on link | Spotify page loads in new tab | Pass |
| Soundcloud link in navbar | Link directs user to Soundcloud page in new tab | Clicked on link | Soundcloud page loads in new tab | Pass |
| Mixcloud link in navbar | Link directs user to Mixcloud page in new tab | Clicked on link | Mixcloud page loads in new tab | Pass |
| Book Your Event Now button on hero | Link directs user to booking page | Clicked on link | Booking page loads | Pass |
| 'Read more about me' link on first USP card | Link directs user to About page | Clicked on link | About page loads | Pass |
| 'Listen to my mixes' link on second USP card | Link directs user to Mixes section on home page | Clicked on link | Page scrolls to Mixes section | Pass |
| 'Book now with confidence' link on third USP card | Link directs user to Booking page | Clicked on link | Booking page loads | Pass |
| 'Read more about DJ Silver Soul' link in About section | Link directs user to About page | Clicked on link | About page loads | Pass |
| Mixcloud link in Mixes section | Link directs user to Mixcloud page in new tab | Clicked on link | Mixcloud page loads in new tab | Pass |
| Soundcloud link in Mixes section | Link directs user to Soundcloud page in new tab | Clicked on link | Soundcloud page loads in new tab | Pass |
| Spotify link in Mixes section | Link directs user to Spotify page in new tab | Clicked on link | Spotify page loads in new tab | Pass |
| YouTube link in Mixes section | Link directs user to YouTube page in new tab | Clicked on link | YouTube page loads in new tab | Pass |
| Book Your Event Now button on CTA section | Link directs user to booking page | Clicked on link | Booking page loads | Pass |
| Instagram link in footer | Link directs user to Instagram page in new tab | Clicked on link | Instagram page loads in new tab | Pass |
| Facebook link in footer | Link directs user to Facebook page in new tab | Clicked on link | Facebook page loads in new tab | Pass |
| X(Twitter) link in footer | Link directs user to X(Twitter) page in new tab | Clicked on link | X(Twitter) page loads in new tab | Pass |
| YouTube link in footer | Link directs user to YouTube page in new tab | Clicked on link | YouTube page loads in new tab | Pass |
| Spotify link in footer | Link directs user to Spotify page in new tab | Clicked on link | Spotify page loads in new tab | Pass |
| Soundcloud link in footer | Link directs user to Soundcloud page in new tab | Clicked on link | Soundcloud page loads in new tab | Pass |
| Mixcloud link in footer | Link directs user to Mixcloud page in new tab | Clicked on link | Mixcloud page loads in new tab | Pass |
| Home page link in footer | Link directs user back to home page | Clicked on link | Home page reloads | Pass |
| About page link in footer | Link directs user to About page | Clicked on link | About page loads | Pass |
| Mixes link in footer | Link directs user to Mixes section on home page | Clicked on link | Page scrolls to Mixes section | Pass |
| Contact link in footer | Link directs user to Booking page | Clicked on link | Booking page loads | Pass |

`About Page`

To avoid repetition, I have listed common links to the home page below as a summary. All links were fully tested and the outcome as as expected above.

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| All navbar links listed above | Link directs user to specified page/section | Clicked on link | Expected page/section loads | Pass |
| Mixcloud link in Mixes section | Link directs user to Mixcloud page in new tab | Clicked on link | Mixcloud page loads in new tab | Pass |
| Soundcloud link in Mixes section | Link directs user to Soundcloud page in new tab | Clicked on link | Soundcloud page loads in new tab | Pass |
| Spotify link in Mixes section | Link directs user to Spotify page in new tab | Clicked on link | Spotify page loads in new tab | Pass |
| YouTube link in Mixes section | Link directs user to YouTube page in new tab | Clicked on link | YouTube page loads in new tab | Pass |
| Book Your Event Now button on CTA section | Link directs user to booking page | Clicked on link | Booking page loads | Pass |
| All footer links listed above | Link directs user to specified page/section | Clicked on link | Expected page/section loads | Pass |

`Booking Page`

To avoid repetition, I have listed common links to the home page below as a summary. All links were fully tested and the outcome as as expected above.

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| All navbar links listed above | Link directs user to specified page/section | Clicked on link | Expected page/section loads | Pass |
| Click submit on form with no content entered | Validation displays alert to enter information in name field | Clicked on submit | Alert is shown on name field | Pass |
| Submit form with white space in name field | Validation displays alert to match the format requested | Clicked on submit | Alert is shown on name field | Pass |
| Enter text in name field and leave email field blank | Validation displays alert to enter information in email field | Clicked on submit | Alert is shown on email field | Pass |
| Enter text in email field with no @ symbol | Validation displays alert to enter @ symbol in email field | Clicked on submit | Alert is shown on email field | Pass |
| Submit form with white space in email field | Validation displays alert to match the format requested | Clicked on submit | Alert is shown on email field | Pass |
| Complete form and leave date field blank | Validation displays alert to enter information in date field | Clicked on submit | Alert is shown on date field | Pass |
| Complete form and leave message field blank | Validation displays alert to enter information in message field | Clicked on submit | Alert is shown on message field | Pass |
| Complete form with correct information | User is redirected to success page | Clicked on submit | Success page is loaded | Pass
| All footer links listed above | Link directs user to specified page/section | Clicked on link | Expected page/section loads | Pass |

`Success Page`

To avoid repetition, I have listed common links to the home page below as a summary. All links were fully tested and the outcome as as expected above.

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| All navbar links listed above | Link directs user to specified page/section | Clicked on link | Expected page/section loads | Pass |
| 'Return to the home page' button on Success page | User is redirected to home page | Clicked on button | Home page is loaded | Pass |
| All footer links listed above | Link directs user to specified page/section | Clicked on link | Expected page/section loads | Pass |