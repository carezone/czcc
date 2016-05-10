# Introduction

Thanks for your interest in working with us at CareZone! This is the first step
in our interview process.

You have as much time as you'd like to complete this project. Please e-mail your
CareZone contact with any questions you may have.

## Submission Instructions

1. First, fork this project on GitHub. You will need to create an account if you
   don't already have one. If you'd prefer to submit via e-mail, clone the repo.
2. Next, complete the project as described below within your fork. Be sure to
   make small commits as you go along!
3. Finally, push all of your changes to your fork on GitHub and submit a pull
   request, or send the compressed archive of your repo to your CareZone
   contact, if submitting by e-mail.

## Project Description

Imagine your company has just acquired another company. Unfortunately, they
never used a database, and instead stored all of their data in a tab-delimited
file. *Yes, we know this is ridiculous.* We need to create a way for the
company to import their data into a database. Your task is to create a web
application (using Ruby on Rails) that accepts file uploads and stores it in a
relational database.

Here's what your application must do:

1.  Your app must accept (via a form) a tab-delimited file with the following
    columns:

    * purchaser name
    * item description
    * item price
    * purchase count
    * merchant address
    * merchant name

    You may assume the columns will always be in that order, that there will
    always be data in each column, and that there will always be a header line.
    An example input file (`example_input.tab`) is included in this repo.

2. Your app must parse the given file and store the information in a relational
   database.

3. After upload, your application should display the total amount gross revenue
   represented by the uploaded file.

Your application does not need to:

1. handle authentication or authorization (but if it does, all the better!)
2. be aesthetically pleasing

Your application should be easy to set up and should run on either Linux or Mac
OS X. It should not require any for-pay software.
