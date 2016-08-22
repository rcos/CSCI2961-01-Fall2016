## Week 6 Lab 10/9/2015 Friday - Continuous Integration

- Please present a pitch slide for your proposed project - include the technology you are planning to use, users of the project, license, language of implementation, hardware used (mobile (ios, android), web application, computational, chrome extension) , project partners

- Please look at the page https://github.com/mskmoorthy/collinear for an example for unit tests. This just for your practice - no submission is needed.  This page https://github.com/mskmoorthy/CITest  contains an example with Continuous Integration (using Travis CI) and testing - Again no submission needed - Just for practice

- The following project is suggested by Aaron Gunderson '17 and Severin Ibarluzea '17 This is the project you are going to do in this lab - **You have to work in groups of two**

For this lab we will be exploring continuous integration in the context of an open source project. Continuous integration is a popular development practice where developers integrate code changes frequently. These changes are verified using automated tests run against the code before merging and against the main branch on any changes. An important part of making this work is having automation and effective tests in place to verify these changes don't break any existing functionality. 


For this lab we will be working in **pairs**  using a normal developer work flow to make changes to RCOS's Observatory to see continuous integration in action. 
[Observatory](https://github.com/rcos/Observatory3/) uses the following model for development and what you will do today:

1. Fork the repo on Github. Follow along [here](https://help.github.com/articles/fork-a-repo/) if you need help!
2. Once you have the repo locally you can get Observatory running locally if you want though it isn't necessary for the lab.
3. Have everything ready to go? Now you are going to pick what you are working on with your partner for the lab. Checkout https://github.com/rcos/Observatory3/labels/help%20wanted where you can find a bunch of detailed issues that should direct you on what files you need to change. Please comment on the issue that you are working on so someone else doesn't take it.
4. Now that you found your issues you should make the changes needed to the code as needed and commit your changes. 
5. Once you have committed your changes you can make a pull request. Follow along [here](https://help.github.com/articles/creating-a-pull-request/) if you need help making a pull request to the repo.
6. With a pull request made you will start to see the continuous integration in action. Immediately after the pull request is made you will see a [Travis CI](https://travis-ci.org/) field show up on the page. This automated continuous integration service runs our tests against the project and makes sure nothing has broken. You can click there to see output of your tests and real time. You can also check out https://travis-ci.org/rcos/Observatory3 where you can see the past history of all tests that have run. 
7. Now we have two paths:
  a. Build finished running successfully? Great! You are good to go and your changes can be merged once a mentor or someone on the project reviews it. 
  b. Build failed? Don't distress! Check the output of the build and you should see what went wrong and may point you in the right direction on how to fix it? Don't know what went wrong? Work with your partner and comment on the pull request that it's broken and you don't know why. We would love to help out!
