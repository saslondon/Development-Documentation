Development Documentation
=========================

####A collection of documents used to guide a project

The aim of this respository is to house a collection of files that can be added and expanded to assist in producing the best possible end result for our clients. 

#####The initial project is the Deployment Process.

The aim of this process is to ensure, given the time constraints of a large number of projects we work on, that the final deliverable to the client is of the highest possible quality. 
With this in mind here are the initial two task lists for each new build. 

###Continuous Development Tasks

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


###Deployment

##Umbraco
- If using Umbraco Contour 
  - remove all test data is deleted
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

##General
- Make sure SMTP server details are correct and functioning
- If using Brightcove
  - Ensure Brightcove domains are set
  - Make sure any links to skins are pointing to the live server
  - Make sure any links to captions are pointing to the live server
- Remove SVN bindings/files from 'live package'
- Finalise Labs Documentation
- Make sure any API keys (Google maps, Twitter etc.) are created for the live domain.
- Link check for any dev or staging url's.
