# Changelog
At Infomundi, we believe in transparency. That's why we are thrilled to introduce our Public Changelog - a dedicated space where you, our users, can witness the ongoing evolution of our website.

# Summary

| Version | Date       | Brief Description      | Authors        |
| ------ | ---------- | ----------------------------- | ------------- |
| 1.2.5 | 2024/02/15 | Version 1.2.5 introduces a comprehensive set of enhancements focused on improving the aesthetic, functionality, and user experience across the website. Notable updates include revamped authentication interfaces, enhanced form validations, and interactive features such as password strength indicators and profile picture uploads. The update also introduces important community-focused features like community policies and a fully functional comments section. Performance and usability have been further optimized through the bundling of resources and interface improvements. Additionally, this version takes significant strides in security with the enforcement of stricter encryption protocols and the remediation of critical vulnerabilities, ensuring a safer and more reliable platform for users. | @InfomundiTeam |
| 1.2.4 | 2023/01/29 | The 1.2.4 update brings significant enhancements aimed at improving user experience and website performance. Noteworthy are the transition to WebP format for images, the introduction of essential website pages, and a more interactive news page with comment functionality. Navigation has been streamlined with a sticky search bar and an intuitive country search feature. Additionally, the update focuses on mobile user experience and performance optimization by redesigning the home page layout and pruning unnecessary elements. Security has been bolstered with the implementation of a CSP and CSRF protection, enhancing the platform's overall security posture. | @InfomundiTeam |
| 1.2.3 | 2023/01/10 | Version 1.2.3 introduces significant enhancements to user experience, notably in the news page presentation and search functionality. It features a more dynamic news layout, advanced search accuracy with auto-translation, and a more visually appealing interface with an updated logo. The release also includes a crucial security fix for the search feature and improvements in site navigation and data access through a new API endpoint. | @InfomundiTeam |
| 1.2.2 | 2023/12/22 | Implemented lazy loading for news page images, improved cache script for more images, and enhanced navbar. Changed comments page cooldown to 5 seconds and accordion look. Enhanced session cookie security. No removals or fixes. | @InfomundiTeam |
| 1.2.1 | 2023/12/21 | Added session remember option, light mode for homepage, authenticated user badge, country area ranking, and logout button. Removed old logo images. Fixed index display and comments page entry bugs. Implemented cooldown for comments form. | @InfomundiTeam |
| 1.2.0 | 2023/12/19 | Introduced light mode, improved ticker functionality, added geopolitical placeholder. Removed unused resources. Fixed ticker and display issues. Enhanced password change page security. | @InfomundiTeam |
| 1.1.9 | 2023/12/13 | Improved mobile compatibility for the ticker. Added crypto, currency, and index information to the homepage. Changed display of country stocks. Removed navbar return button for mobile users. Enhanced account creation spam prevention. Reduced password complexity. | @InfomundiTeam |
| 1.1.8 | 2023/12/05 | Added login system. Fixed news ticker. No other changes or security updates. | @InfomundiTeam |
| 1.1.7 | 2023/12/04 | Added nation statistics, click removal for inactive news, and main stock display. Removed unnecessary scripts. Fixed error page and UTC-related bug. Improved captcha security. No other changes. | @InfomundiTeam |
| 1.1.6 | 2023/11/24 | Implemented sleek accordion design with mobile detection, enriched news item details on comments page, streamlined navbar, and improved CLS. Changed source color, added placeholder text, revamped logo font, and relocated search bar. Removed outdated images, and fixed card height for mobile users. | @InfomundiTeam |
| 1.1.5 | 2023/11/20 | Added error pages, code refactoring, email support, and comment blacklist. Changed theme color to black. Fixed return button on comments page. No removals or security changes.  | @InfomundiTeam |
| 1.1.4 | 2023/11/17 | Revamped homepage layout. Added click tracking, user session stats, icons in comments. Improved cache script and added view count badges. Changed search bar and subtitle colors. Adjusted news page layout for smaller screens. Fixed search bug. No removals or security changes.  | @InfomundiTeam |

---


## Changelog 1.2.5 (2024/02/15)

### Enhancements (12)
1. **IME01:** Revamped the aesthetics of the sign in, sign up, and password change processes for a more visually appealing experience.
2. **IME02:** Introduced client-side validation for sign up and sign in forms to improve user experience by providing immediate feedback.
3. **IME03:** Implemented password strength indicators on sign up and password change forms to encourage the use of strong, secure passwords.
4. **IME04:** Added a 'show password' option in forms, allowing users to check their input for accuracy.
5. **IME05:** Fully activated the comments section, enabling interactive user discussions.
6. **IME06:** Enabled registered users to upload personal profile pictures, enhancing user personalization.
7. **IME07:** Launched a maintenance page feature to notify users of temporarily inaccessible pages or services.
8. **IME08:** Introduced a cookie consent modal in compliance with privacy regulations.
9. **IME09:** Established community policies to guide user interactions and ensure a respectful and safe online environment.
10. **IME10:** Made significant improvements to the website's navigation bar for a more intuitive and user-friendly experience.
11. **IME11:** Optimized website loading times by serving JavaScript and CSS files in a bundled, minified format.
12. **IME12:** Added an account recovery feature, providing users with a secure method to regain access to their accounts.

### Changes (1)
1. **IMC01:** Streamlined the user experience by automatically logging in users upon successful account verification.

### Removed (1)
1. **IMR01:** Removed redundant icons from the ticker to enhance site performance and reduce the Document Object Model (DOM) size, continuing the effort from the previous update.

### Fixed (2)
1. **IMF01:** Corrected a navigation issue in the comments page breadcrumb, ensuring the accurate display of the previously visited country.
2. **IMF02:** Addressed several usability issues within the comments section to enhance user interaction and feedback.

### Security (2)
1. **IMS01:** Upgraded the minimum supported Transport Layer Security (TLS) version to 1.2, enhancing the encryption standard for user data protection.
2. **IMS02:** Remedied a high-severity Cross-Site Scripting (XSS) vulnerability in the comments section, fortifying the website against malicious script injections.


---

## Changelog 1.2.4 (2024/01/29)

### Enhancements (6)
1. **IME01:** Introduced a comprehensive footer section to the website for better navigation and information access.
2. **IME02:** Upgraded news image delivery to next-gen WebP format with an optimized caching policy, significantly boosting site performance.
3. **IME03:** Launched new informational pages: About Us, Our Team, Contact Us, and Policies, enhancing transparency and user engagement.
4. **IME04:** Added functionality for users to preview and post comments specific to news stories directly on the news page, fostering community interaction.
5. **IME05:** Enhanced the news page search bar by making it sticky in the navbar on desktop devices, improving user experience while scrolling.
6. **IME06:** Refined country search on the home page for instant and more accurate results, even with minor typos (e.g., 'canda' leads to Canada).

### Changes (1)
1. **IMC01:** Redesigned the mobile view of the home page, positioning the statistics tab below the globe for a streamlined experience.

### Removed (1)
1. **IMR01:** Eliminated superfluous icons from the ticker to boost performance and reduce the website's DOM size.

### Fixed (1)
1. **IMF01:** Corrected a defect in the news page's search-with-translation feature, ensuring seamless functionality.

### Security (2)
1. **IMS01:** Instituted a Content Security Policy (CSP) to fortify website security against various types of attacks.
2. **IMS02:** Integrated Cross-Site Request Forgery (CSRF) protection measures.

---

## 1.2.3 2024/01/10

### Enhancements (8)
- IME01: Improved user engagement by randomizing news content display on each page reload.
- IME02: Enhanced search function accuracy, offering more relevant results.
- IME03: Integrated auto-translation into the search feature, enhancing accessibility on the news page.
- IME04: Redesigned news page layout for better clarity and conciseness.
- IME05: Added descriptive headers to news stories, improving user navigation and quick access to story details.
- IME06: Enhanced image display algorithm, resulting in more news stories featuring images.
- IME07: Upgraded Infomundi logo design for better brand representation.
- IME08: Launched new API endpoint (/api) for serving static data and managing actions like adding comments to stories.

### Changed (4)
- IMC01: Maintained visibility of older news posts during new cache updates.
- IMC02: Implemented a new pagination system for countries with extensive news coverage.
- IMC03: Relocated the theme change option to the account dropdown menu for improved accessibility.
- IMC04: Updated the lazy load script for better performance.

### Removed (0)
- No items removed in this update.

### Fixed (1)
- IMF01: Several bug fixes.

### Security (1)
- IMS01: Addressed a vulnerability in the search function that could lead to Denial of Service (DoS) under certain conditions.


## 1.2.2 2023/12/22

### Enhancements (3)
- IME01: Added lazy loading to images in the news page.
- IME02: Enhanced cache script capabilities (you'll see more images in the feed now).
- IME03: Big enhancement to the navbar. 

### Changed (2)
- IMC01: Changed cooldown from 10 to 5 seconds in the comments page.
- IMC02: Changed the accordion look in the home page (dark theme).

### Removed ()

### Fixed ()

### Security (1)
- IMS01: Enhanced session cookie security.


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
