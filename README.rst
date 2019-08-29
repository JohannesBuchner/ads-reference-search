Search by Reference for ADS in Firefox & Chrome
=================================================

**This project provides "Lastname (year)" searches for ADS**

Background
-----------

The old Astronomy Database System (ADS) supported searching by reference strings, such as

* Buchner (2014)
* Buchner et al (2017)
* Buchner & Bauer (2018)
* Buchner+15
* Buchner+2015

This was neat because you could copy this from a paper, put it into the field and get matching papers. Even faster, making a Firefox search keyword for the page, you could enter into the location bar "ads Buchner (2014)" and go directly to the results page.

Alas, the new ADS does not support this (yet). 

Usage
======

Set up search engine keyword
------------------------------

In Firefox: 

* Right-click the text field in https://johannesbuchner.github.io/ads-reference-search/
* "Add a Keyword for this Search"
* Set the keyword to "ads"
* Done! Enter into your search bar "ads Lastname et al. (2017)" (without quotes)

In Chrome:

* go to Settings -> Manage search engines or chrome://settings/searchEngines
* url: https://johannesbuchner.github.io/ads-reference-search/?q=%s
* keyword: ads
* Done! Enter into your search bar "ads Lastname et al. (2017)" (without quotes)

Manually:

Enter your reference at https://johannesbuchner.github.io/ads-reference-search/ 

How does it work?
==================

Javascript parses the input and redirects you to the proper ADS search query. No data is stored on any servers, code is executed in your browser.

Licence
=========

BSD 2-clause. Code here: https://github.com/JohannesBuchner/ads-reference-search/blob/gh-pages/index.html

