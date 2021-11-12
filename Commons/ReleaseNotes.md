## 5.10.0

**ADDED**
- Email notifications for playbooks. Users can opt in/out of playbooks updates, including:
   - Any changes to an existing playbook
   - Notifications on newly published playbook
- A confirmation page notifying a user of their change in preferences
- Revert link to undo unintentional subscribe/unsubscribe actions
- A collapsible section component to hide/show parts of a page. Applied to the playbook edit screen

**CHANGED**
- Disable the policy priorities filter on the search page when content that cannot be tagged with policy priority is not included in the search criteria

## 5.9.1

**FIXED**
- Login from Okta Dashboard

## 5.9.0

**ADDED**
- Additional filter to the Search page to allow narrowing down search results by policy priority

**FIXED**
- Playbooks duplicate title error message now displays the link to the package with the same title

## 5.8.0

**ADDED**

- “Current Topics”, “Holidays & Events” and “Secretary Travel” categories to the taxonomy
- “Additional Messaging Effort” section to the policy playbooks landing page to highlight selected categories
- Category archive page accessed via a custom category url to display playbooks tagged with a specific category. This will improve user experience, organization of content, and bookmarking
- Country drop-down field to the Playbook edit page to search Playbooks by country
- Cache static content to improve performance

**CHANGED**

- Remove “Alliances and Partnerships” policy priority
- Remove “Afghanistan” policy priority 
- Standardize all categories and policies to use “&” instead of “and”

**FIXED**

- Gradient background on “Climate Change” priority on Policies page

## 5.7.1

**ADDED**

- A ContentGrid component for eventual use in displaying rich content in playbooks

**CHANGED**

- Enforce unique titles for playbooks
- Update the playbook edit form validation to ensure titles are unique
- Add error states to notify the user when they need to alter the title
- Improve mobile responsiveness for playbooks and switch to a true sticky footer
- Add the GPA Front Office as a producer of policy priorities to the priorities page description

**FIXED**

- Flash of incorrect content before the search page was fully loaded

## 5.7.0

**ADDED**

- Created a landing page for Policy Priorities : commons.america.gov/playbooks
- Created landing pages for playbooks in each Policy Priority to improve user experience in searching, sharing, and bookmarking
- Created a vanity link for each Playback to make sharing easier
- Added Afghanistan as a new Policy Priority
- Standardized usage of AWS Cognito authentication between various parts of the system

**CHANGED**

- Renamed Playbook section “Available Resources” to “Additional Resources”
- Limit access to the public endpoint to only the application domain
- Restructured application pages to remove older libraries

**FIXED**

- Formatting issues when text is pasted from One Drive Word files into the text editor
- Pasting a specific URL into search will now take a user to the correct search result

## 5.6.1

**ADDED**

- Added the Playbook content type.  Playbooks can be uploaded and managed by any team with the appropriate permissions. Playbooks can be viewed and shared by users logged into the system.
- Added a rich text editor to allow for more robust authoring capabilities
- Added the Global Campaigns Strategy Unit team
- Added Priority Policies to tag, track and better display administration policies
- Added an initially published state to reflect a package’s first publish and to serve as a reference point for future package updates
- Added Skip to content link for improved accessibility
- Added New Relic application performance monitoring
 
**CHANGED**

- Created a single workflow to handle both Press Guidance and Playbook creation.
- Added the Playbook priority section to the homepage for all logged in users. Surface playbooks in search
- Removed the list view from the Browse All page for all content types
- Improved accessibility across the client frontend system
- Redesigned recent/relevance dropdown
- Converted various components to use CSS modules
- Replaced a number of Semantic UI components with native HTML elements
- Labelled the “Additional Resources” file types in a user friendly manner on the front end (eg. Word Document vs. docx)

**FIXED**

- Fixed scrolling arrows on the Dashboard to only display when columns do not fit on screen
- Fixed issue that caused the search filters to be removed when the "CLEAR ALL" button lost focus

## 5.2.0

**ADDED**

- Provide the option the make video project internal only
- Regional Media Hubs added as a team
- Ability to provide clean video downloads

**CHANGED**

- The verbiage regarding subtitles when adding a videos
- Disable the 'Delete Project' button should on the Project Details screen for published projects
- Make article feed and embed components compatible with signed URLs for images
- Prioritize title in document searches
- Rename of the Editorial team "GPA Design & Editorial"
- Automatically set video style to clean when the word clean is present in the title
- Automatically set file language when the a language or locale is present in the title
- Show all content types in results when clicking "browse all" from a priority section on the homepage

**FIXED**

- Unpublishing from Dashboard is not working on all sites
- Text overflow in result preview modal
- Videos are incorrectly labeled on "Videos in Project" screen
- Deletions initiated in the middle of an upload does not process
- Hover styling obscures the file name in the download file button

## 5.1.2

**ADDED**

- Added the following tags: `Michael R. Pompeo`, `Secretary of State`, `Donald J. Trump`, and `POTUS`

## 5.1.1

**FIXED**

- Downloads of non-English video files not working under certain conditions

## 5.1.0

**ADDED**

- Users can search packages by "most relevant" or "most recent"
- Prompt on homepage suggesting that users log in to see more content

**CHANGED**

- Sort press package items by document type
- Sort press guidance packages by date created (rather than updated)

**FIXED**

- Handle special characters in file names so the that API does not crash

## 5.0.0

**ADDED**

- Ability to create, publish, and unpublish graphics projects
- Graphics projects appear in the search and on the homepage
- GPA Global Social Media added as a team
- A search filter on the homepage to limit search by content type
- Pagination of the projects list of projects in the Dashboard
- Add the extensions .otf, .lst, and .gifs to the allowed file types
- A China priorities section
- Scripts to seed styles and platforms

**CHANGED**

- Use signed URLs for accessing documents and images
- Update footer email address from design@america.gov to gpadigitalhelp@state.gov
- Update FAQ page with expired session notes
- Populate the countries drop down by pulling from the database (to keep it up to date)

**FIXED**

- Properly populate author column in the graphics dashboard
- Make .vtt files downloadable
- Show the ShareAmerica logo when the source is set to ShareAmerica
- Do not show 'Changes Saved' message on initial load of the video project details page
- Text overflow issues in mobile view

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
- Replaced GTM implementation with React app
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
- Store full path to elastic search asset to accommodate sharing on external sites
- Update help text on project details screen

**FIXED**

- Bulk project unpublish now removes assets for S3
- SRT filename adjusted to support Facebook upload
- Turned server side render off for user queries to fix cache issue

## 3.0.0

#### Version 3 is a complete rewrite with focus on the authoring platform. A jump is made to version 3 from 1.8.4 as v2 was an extension of v1 that did not include Server Side rendering (SSR).

**ADDED**

- Next.js integration and code restructure for Server Side rendering (SSR)
- React apollo integration for communication with the server and database
- AWS integration for secure uploads to S3 via signed urls
- Websocket integration for automatic page updates
- User Authentication for logging in and logging out
- User account creation and registration
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

- Updated styles to accommodate and feature the Department Priority section.
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

- Embed code to display to embed both YouTube and Vimeo videos now active
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
- Added Browse all [type] link above each Recents section on Landing page
- Updated help text for video downloads
- Source action creator now accepts an array of owners and not a string as it's search key
- Created owners mappings in source action to (1) support inconsistent owner names and (2) assign a custom name

## 1.0.0

**ADDED**

- Global search bar
- Feedback form
- About, Help, Privacy Policy pages
- Filter search by Date, Format, Source, Language and Category
- Display search results in either gallery or list formats
- Closable filter selections bubbles
- Contextual number of results
- Video and Article content types search
- Modal window that houses selected item
- Video modal
- Article modal
- Result pagination
