# Changelog
At Infomundi, we believe in transparency. That's why we are thrilled to introduce our Public Changelog - a dedicated space where you, our users, can witness the ongoing evolution of our website.

# Summary

| Version | Date       | Brief Description      | Authors        |
| ------ | ---------- | ----------------------------- | ------------- |
| 1.2.1 | 2023/12/21 | Added session remember option, light mode for homepage, authenticated user badge, country area ranking, and logout button. Removed old logo images. Fixed index display and comments page entry bugs. Implemented cooldown for comments form. | @InfomundiTeam |
| 1.2.0 | 2023/12/19 | Introduced light mode, improved ticker functionality, added geopolitical placeholder. Removed unused resources. Fixed ticker and display issues. Enhanced password change page security. | @InfomundiTeam |
| 1.1.9 | 2023/12/13 | Improved mobile compatibility for the ticker. Added crypto, currency, and index information to the homepage. Changed display of country stocks. Removed navbar return button for mobile users. Enhanced account creation spam prevention. Reduced password complexity. | @InfomundiTeam |
| 1.1.8 | 2023/12/05 | Added login system. Fixed news ticker. No other changes or security updates. | @InfomundiTeam |
| 1.1.7 | 2023/12/04 | Added nation statistics, click removal for inactive news, and main stock display. Removed unnecessary scripts. Fixed error page and UTC-related bug. Improved captcha security. No other changes. | @InfomundiTeam |
| 1.1.6 | 2023/11/24 | Implemented sleek accordion design with mobile detection, enriched news item details on comments page, streamlined navbar, and improved CLS. Changed source color, added placeholder text, revamped logo font, and relocated search bar. Removed outdated images, and fixed card height for mobile users. | @InfomundiTeam |
| 1.1.5 | 2023/11/20 | Added error pages, code refactoring, email support, and comment blacklist. Changed theme color to black. Fixed return button on comments page. No removals or security changes.  | @InfomundiTeam |
| 1.1.4 | 2023/11/17 | Revamped homepage layout. Added click tracking, user session stats, icons in comments. Improved cache script and added view count badges. Changed search bar and subtitle colors. Adjusted news page layout for smaller screens. Fixed search bug. No removals or security changes.  | @InfomundiTeam |


## 1.2.1 2023/12/21

### Enhancements (6)
- IME01: Users can now choose if they want their session to be remembered by checking the checkbox in the log in page.
- IME02: Added light mode compatibility to the home page.
- IME03: Authenticated users now receive a badge before their name in the comments page.
- IME04: Added country area ranking.
- IME05: The "current time" of a country is now based on their capital time.
- IME06: Added logout button to the home page (appears when the user is logged in).

### Changed (0)

### Removed (1)
- IMF01: Removed former logo images from /static.

### Fixed (2)
- IMF01: Fixed bug where specific country indexes not showing up properly in the news page.
- IMF02: Fixed bug that was stopping users from entering the comments page for specific news. 

### Security (1)
- IMS01: Added a 10 seconds cooldown for the comments form.


## 1.2.0 2023/12/19

### Enhancements (3)
- IME01: Introducing light mode! Users can now switch between light and dark mode with a click of a button.
- IME02: General improvements to the ticker (speed functionality, fixes and new information being displayed).
- IME03: Added geopolitical placeholder when no information is available.

### Changed ()

### Removed (1)
- IMR01: Removed flags.css and flags.png as they were no longer being used.

### Fixed (4)
- IMF01: Fixed ticker not displaying the entire text on smaller screens.
- IMF02: Fixed globe not showing properly on mobile.
- IMF03: Fixed world stock data not showing in countries that don't have national stock data.
- IMF04: Fixed GDP data not displaying accordingly.

### Security (1)
- IMS01: Enhanced security on password change page.


## 1.1.9 2023/12/13

### Enhancements (2)
- IME01: Enhanced mobile compatibility (ticker).
- IME02: Crypto, countries currency and indexes information are now collected and displayed in the home page. 

### Changed (1)
- IMC01: Changed the way country stocks are displayed.

### Removed (1)
- IMR01: Removed navbar 'Return' button for mobile users.

### Fixed (0)

### Security (2)
- IMS01: Implemented measures to prevent spam upon account creation.
- IMS02: Decreased password policy complexity (current: 8 characters minimum, with at least 1 number).


## 1.1.8: 2023/12/05

### Enhancements (1)
- IME01: Introducing: Login System!

### Changed (0)

### Removed (0)

### Fixed (1)
- IMF01: Fixed news ticker.

### Security (0)


## 1.1.7: 2023/12/04

### Enhancements (3)
- IME01: Added nation statistics, including population, area, capital, languages and more.
- IME02: News with no clicks for 7 days will now get its clicks removed entirely.
- IME03: Main stocks from countries are collected and displayed in the news page.

### Changed (0)

### Removed (1)
- IMR01: Removed unecessary scripts.

### Fixed (2)
- IMF01: Fixed error page not adapting to the user's viewport.
- IMF02: Fixed bug that was provoking internal server error when the user visits a country with UTC time.

### Security (1)
- IMS01: Changed captcha system from hcaptcha to cloudflare turnstile.


## 1.1.6: 2023/11/24

### Enhancements (4)
- IME01: Implemented a sleek accordion design for statistics display. Added a script to detect mobile users and, if applicable, automatically closes the accordion for a quick view of the globe.
- IME02: Enriched the comments page with additional details, including the publisher, publication date, total views, and comment count for each news item.
- IME03: Streamlined and refined the navbar for a cleaner and more concise appearance.
- IME04: Improved Cumulative Layout Shift (CLS) by setting explicit width and height for image elements on the home and comments pages.

### Changed (4)
- IMC01: Infused a vibrant touch by updating the source color from gray to a cool blue (news page).
- IMC02: Introduced a placeholder text "There's nothing here yet..." in the session tab on the home page.
- IMC03: Revamped the logo font for a fresh look.
- IMC04: Relocated the search bar on the news page, now positioned just below the country's name.

### Removed (1)
- IMR01: Eliminated outdated images from static.

### Fixed (1)
- IMF01: Addressed mobile user experience by fixing card height on smaller screens.

### Security (0)


## 1.1.5: 2023/11/20

### Enhancements (4)
- IME01: Introduced a user-friendly error page for not found or internal server errors.
- IME02: Conducted a thorough code refactoring for improved efficiency.
- IME03: Enabled email support, gearing up for the upcoming launch of the contact form.
- IME04: Implemented a badlist to filter out potentially harmful comments.

### Changed (1)
- IMC01: Transformed the theme color (Discord preview link) from white to a sleek black.

### Removed (0)

### Fixed (1)
- IMF01: Rectified the return button on the comments page, now smoothly redirects users to their previous country view.

### Security (0)


## 1.1.4: 2023/11/19

### Enhancements (5)
- IME01: The homepage has undergone a comprehensive aesthetic overhaul, resulting in a more refined appearance with significant layout modifications.
- IME02: Implemented a click tracking feature for news articles, ensuring each user interaction is recorded when clicking on a story.
- IME03: Enhanced statistical reporting to include click metrics and pertinent user session details such as the last visited news and country.
- IME04: Augmented the comments page with iconography, affording a visually enriched experience for users interacting with informative text.
- IME05: Introduced an informative badge to display view counts for all news articles directly on the news page.

### Changed (3)
- IMC01: Reconfigured the search bar with a light blue hue and replaced the 'Search' button with a magnifying glass icon for a more streamlined visual presentation.
- IMC02: Altered subtitle color schemes within the comments page to enhance readability and visual coherence.
- IMC03: Modified the layout column configuration for the news page on smaller screens, opting for a two-column structure (col-xxl-3) instead of the previous four.

### Removed (0)

### Fixed (2)
- IMF01: Resolved a bug that erroneously redirected users to non-existent story comment pages after utilizing the search functionality. Additionally,
- IMF02: Rectified script issues pertaining to cache creation, ensuring optimal functionality and system stability.

### Security (0)
