The Selenium-Flex API allows automation of Flex applications using the popular test automation tool Selenium. The API is easy to set up and can be done with only basic working knowledge of either Flex or Selenium.

# News #

| **Date** | **News** |
|:---------|:---------|
| 25 Feb 2010 | Added a public Maven repository for sfapi at:http://sfapi.googlecode.com/svn/maven/ |
| 21 Oct 2009 | Sample projects added to download section |
| 20 Oct 2009 | Version 0.2.6 released |

# Quick Start #

Getting started with using the API with Selenium IDE is relatively easy. Just follow these steps:
### Get the API ###
  * Download the latest version of the Selenium-Flex API from our [downloads section](http://code.google.com/p/sfapi/downloads/list) and extract the contents to a directory on your machine
### Get Firefox ###
  * Make sure you have the latest version of [Firefox](http://www.mozilla.com/firefox) installed
### Setup Selenium IDE ###
  * Get the latest version of the [Selenium IDE](http://seleniumhq.org/download) plugin for Firefox
  * In the options window for the Selenium IDE, add the file `user-extensions.js` (which is packaged with our API) to the **Selenium Core extensions**. This file allows Selenium to call the API.
### Include The API in Your Flex Application ###
  * Copy the file sfapi.swc into the 'libs' folder of your Flex application
  * In Flexbuilder/Eclipse:
    * Right click on the project and go to the project properties
    * Click on the `Flex compiler` to bring up the compiler options
    * Add the following to the **Additional compiler arguments**: `-include-libraries "..\libs\sfapi.swc"` (for Windows) or `-include-libraries "../libs/sfapi.swc"` (for Mac or Linux)
### Ready To Go ###
The API will now be compiled with your project and your Flex application file will be open to Selenium to make calls. For more in-dept articles on setting up the API as well as scripting tests and more advanced topics, go to our [Wiki](http://code.google.com/p/sfapi/w/list).

# Support #
To get help and support on using the Selenium-Flex API, join sfapi-support on Google Groups. Go to http://groups.google.com.au/group/sfapi-support to join up and get posting queries to the group.

# Development #
If you want to get involved with development on the project or even if you just want to keep tabs on development activities, join the sfapi-dev group here: http://groups.google.com.au/group/sfapi-dev
