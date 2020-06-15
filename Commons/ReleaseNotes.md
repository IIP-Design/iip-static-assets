## 4.2.0
**ADDED**
- Functionality to download all documents in a package to a single zip file

**CHANGED**
- Documents Format filter label to "Press Releases and Guidance” to better reflect type
- Searching by Package now includes documents so Package search returns results

**REMOVED**
- Guidance Packages as an option in Format filter options

## 4.1.1
**ADDED**
- Google Tag Manager Containers for production and development environments

**CHANGED**
- Videos with subtitles now display by default if available

**FIXED**
- Login now properly redirects to CloudFlare on mobile
- Escape special characters when setting AWS S3 key for upload to address issues with download and display
- Added 'name' property to Elastic tag to ensure 'Coronavirus' surfaces in search

## 4.1.0
**CHANGED**
- Packages on landing page now sort by created date
- Removed Facebook and Twitter sharing options for video

## 4.0.0
**ADDED**
- Add redirect to previous url on successful login
- Add ability for subscriber to see restricted content
- Add uploading documentation for press guidance
- Add Document content type
- Add Press Guidance Package content type
- Add Press Guidance upload capability
- Logged in users can access Press Guidance
- Add link to the press guidance archive at the bottom of the featured packages box and conditionally add a similar link to the footer while only displaying the link if the user is logged in
- Add Countries dropdown
- Add Bureaus dropdown
- Add Packages to priorities section
- Add country filter search for documents

**CHANGED**
- Replaced h1 elements in the footer with divs in the interest of improved accessibility
- Replaced GTM implemenation with React app
- Google authentication through CloudFlare access
- State.gov authentication through CloudFlare access using one time pin

**FIXED**

- Fixed the broken feedback link in the user profile dropdown and added feedback link as variable in config file

## 3.1.5
**ADDED**
Coronavirus (COVID-19) priorities section to homepage

## 3.1.4
**FIXED**
- Hide internal-only visibility option for videos until that view is made available.

## 3.1.3
**FIXED**
- Re-order priorities sections on homepage

## 3.1.2
**ADDED**
- Venezuela priorities section to Home page

**FIXED**
- Registration issue throwing a type error on form submission
- Twitter share did not automatically populate with applicable video or post

## 3.1.1
**FIXED**
- Suppress mock data

## 3.1.0
**ADDED**
- Add "Create New Package" button to upload screen to be used by Press Guidance team
- Activate content type buttons on upload screen based on user's team permissions
- Update Dashboard component to support Press Office packages
- Created UserAdmin component to allow team switching for testing purposes
- Allow upload of caption .vtt files
- Set visibility flag on each asset to track internal only assets

**CHANGED**
- Code libraries were updated
- Store full path to elastic search asset to accomodate sharing on external sites
- Update help text on project detials screen

**FIXED**
- Bulk project Unpublish now removes assets for S3
- SRT filename adjusted to support Facebook upload
- Turned server side render off for user queries to fix cache issue

## 3.0.0
#### Version 3 is a complete rewrite with focus on the authoring platform. A jump is made to version 3 from 1.8.4 as v2 was an extension of v1 that did not include Server Side rendering (SSR).

**ADDED**
- Next.js integration and code restructure for Server Side rendering (SSR)
- React apollo intergation for communication with the server and database
- AWS integration for secure uploads to S3 via signed urls
- Websocket integration for automatic page updates
- User Authentication for logging in and logging out
- User account creation annd registration
- Authoring interface to create, update, delete, publish and unpublish video projects
- Formik form validation
- Ability to share search results
- Numerous test files for various functionality
- Documentation updated to include help with video upload and publishing

**CHANGED**
- Copy and share link for a video now lives in the 'Share' tab

**REMOVED**
- Language detection on search keystroke

## 1.8.4
**ADDED**
- Added a '5G' department priority section to the front page

## 1.8.3
**ADDED**
- Added a logo for VOA Editorial content

**CHANGED**
- Updated IIP Properties to GPA

## 1.8.2
**FIXED**
- Limited categories to three items in the Latest and Priority sections to resolve a display issue.

## 1.8.1
**FIXED**
- Resolved bug with Recents sections not sorting properly.

## 1.8.0
**ADDED**
- We added a new Department Priority section to be featured on the front page.
- We then configured that Department Priority section to display the topic: Iran.

**CHANGED**
- Updated styles to accomodate and feature the Department Priority section.
- Updated text headings for the Recents section.

## 1.7.1
**CHANGED**
- Updated IIP to GPA in the footer

## 1.7.0
**ADDED**
- Articles now have a direct page in Commons similar to videos
- The article display will utilize this direct link if the original source is content.america.gov

## 1.6.8
**FIXED**
- Resolved an issue wherein languages were not being loaded for the searchbar menu on certain pages

## 1.6.7
**ADDED**
- We added Open Graph tags to the site that will help generate previews when sharing a link to certain properties and applications.
- The DoS seal has been added for DoS properties that do not have a custom logo.

**UPDATED**
- Category and Source filters will now update based on the search results.
- You can now set your search language via a dropdown on the search bar.
- We've recently posted some content from VOA, specifically VOA Editorials within Content Commons, so we made sure to update their name to display correctly.

## 1.6.6
**UPDATED**
- Available downloaded Transcript files now follow a better naming convention to match Video and SRT in previous release.

## 1.6.5
**ADDED**
- We can now start tracking when users preview articles or videos, copy embed codes, and other click actions within our platform.

**UPDATED**
- In not so breaking news, Slack changed their logo. If you have not seen their new branding, take a look at our updated footer.
- Downloaded files for SRT and Video now follow a better naming convention when downloading a language other than English.

## 1.6.4
**ADDED**
- OpenNet users will now see a notification recommending that they use Chrome for the best Content Commons experience.

**UPDATED**
- Downloaded files now follow a filename and language code naming convention.
- Search results are now displayed by relevance. Result precedence has been given to the search term located in the title field of an article. A result boost is also given to more recently published items.
- Updated sub-heading text and some contact information.

**FIXED**
- Typing in odd number of double quotations within the search field no longer throws an error.

## 1.6.0
**ADDED**
- Integrated Google Translate API to provide language detection for better searching when using terms across languages.
- Redirects to 404 page when necessary.
- Help/notification messages for embedding articles, when a video has no files available for download, or when a search returns zero results.

**UPDATED**
- Enhanced search for relevance, recency, title, and description fields.
- We made some styling adjustments and changes to the front end.

**FIXED**
- Lots of fixes for how the site displays across different browsers and devices.
- Searching on various special characters or blank searches no longer creates an error.

## 1.5.2
**CHANGED**
- Replace DOS seal with svg version and remove multiple png instances.

## 1.5.1
**ADDED**
- Make search icon clickable.
- Remove site BETA tag and add the DOS Seal


## 1.5.0
**ADDED**
- Add captions and alt text to images in the search results modal.

**FIXED**
- Define images to a maximum width of 100% to prevent them from overflowing the embed container.

**CHANGED**
- Use locale rather than language code to maintain project-wide consistency.

## 1.4.3
**CHANGED**
- Set single article module portion of embed URL to an environmental variable

## 1.4.2
**FIXED**
- Show languages displayed in language dropdown if a source exists within the language unit

## 1.4.1
**FIXED**
- Fixed difficulty selecting icon links in popups

## 1.4.0
**ADDED**
- Enhanced footer to include additional links and information
- Added embed code generation to enable sharing of posts
- Updated direct link for posts to point to original source

**FIXED**
- Fixed tabbed underline on video popups

## 1.3.0
**ADDED**
- Embed code to display to embed both youtube and vimeo videos now active
- Share windows now are either a popup for desktop or a new page for mobile

**FIXED**
- Caption toggle now operates correctly and loads correct video based on caption selection
- Fixed direct link UI display

## 1.2.0
**ADDED**
- Added Vimeo support
- Provided a Vimeo/CloudFlare fallback option when YouTube is not available
- Provided a sharable, direct link to the video page
- Updated UI to provide "web" and "broadcast" video quality display
- Updated various UI styles

**UPDATED**
Sources dropdown now sorted alphabetically

## 1.1.0
**ADDED**
- Added Contact Us page
- Added Browse all [type] link above each recents section on Landing page
- Updated help text for video downloads
- Source action creator now accepts an array of owners and not a string as it's search key
- Created owners mappings in source action to (1) support inconsistent owner names and (2) assign a custom name

## 1.0.0
**ADDED**
- Global search bar
- Feedback form
- About, Help, Privacy Policy pages
- Filter search by Date, Forat, Source, Language and Category
- Display search results in either gallery or list formats
- Closable filter selections bubbles
- Contextual number of results
- Video and Article content types search
- Modal window that houses selected item
- Video modal
- Article modal
- Result pagination