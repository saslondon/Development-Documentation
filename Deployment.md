Development Documentation
=========================

####A collection of documents used to guide a project

The aim of this respository is to house a collection of files that can be added and expanded to assist in producing the best possible end result for our clients. 

#####The initial project is the Deployment Process.

The aim of this process is to ensure, given the time constraints of a large number of projects we work on, that the final deliverable to the client is of the highest possible quality. 
With this in mind here are the initial two task lists for each new build. 

##Continuous Development Tasks

- Cross browser testing
- Print style sheet
- Accessability
- Removal of unused CSS selectors
- Basic SEO (meta tags and headings)
- SQL injecton checking
- Favicon
- No-js test
- Error pages (40x and 50x)
- W3C Validation
- Brightcove integration
- Image optimisation
- Abide to html/css/javascript/c#/xslt/umbraco style guide (needs to be defined explicitely)
- SVN
  - Commit at least once a day during the build phase
  - Commit after every fix during bug fix phase
  - Use good commit comments (see CommitMessages file)
- Complete weekly code review with a peer

##Deployment

- Clear logs table
- Backup & Clear SQL Database
- Publish Entire Site
- Rebuild Umbraco Index
- Rebuild Search Index
- Delete Unused Admins
- Performance Testing
- Site Certificate
- Rebuild Site Cache
- Recycle Bin empty
- Folders Clean Up
- Cull Historical Versions
- Umbraco Check Error Log
- 301 Redirect
- Vanity Url Setup

###Umbraco
- If using Umbraco Contour 
  - remove all test data
  - make sure the correct email addresses are in the Contour workflow
  - send final test emails
- Change umbracoSettings.config 'from' email address - for generated emails
- Make sure the 'install' folder has been removed
- Make sure the 'templates' folder has been removed
- Make sure RSS feeds are functioning
- Make sure Google Sitemap is functioning
- Make sure an Umbraco Licence for the live domain has been created
- If Multi-language
  - Ensure live url's are added to the 'Manage hostname's' dialog
- Change web.config -> system.web -> customErrors mode to "On"
- Change web.config -> remove compilation debug attribute

###General
- Make sure SMTP server details are correct and functioning
- If using Brightcove
  - Ensure Brightcove domains are set
  - Make sure any links to skins are pointing to the live server
  - Make sure any links to captions are pointing to the live server
- Remove SVN bindings/files from 'live package'
- Make sure any API keys (Google maps, Twitter etc.) are created for the live domain.
- Link check for any dev or staging url's.
- Setup Google Webmasters account for the live url and add verification file.
- Robots.txt file generated and accurate
- Google Analytics installed and working
- Webfont domain permissions correct for live site
- CSS and JS compression
- Bug tracker complete
- Speedcheck the site
- Finalise Labs Documentation

##Finally
After all this has been completed email the project manager to say that the site has been signed off as complete and built to the best of our ability.