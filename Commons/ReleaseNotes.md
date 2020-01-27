## 1.8.4
**ADDED**
- Added a '5G' department priority section to the front page

## 1.8.3
**ADDED**
- Added a logo for VOA Editorial content

**Changed**
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

**Changed**
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