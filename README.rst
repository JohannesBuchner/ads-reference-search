Firefox Keyword Search by Reference for ADS
=============================================

Background
-----------

The old Astronomy Database System (ADS) supported searching by reference strings, such as

 * Buchner (2014)
 * Buchner et al (2017)
 * Buchner & Bauer (2018)

This was neat because you could copy this from a paper, put it into the field and get matching papers. Even faster, making a Firefox search keyword for the page, you could enter into the location bar "ads Buchner (2014)" and go directly to the results page.

Alas, the new ADS does not support this (yet). 

What is it?
------------

**This project provides "Lastname (year)" searches for ADS**

Usage
======

Enter your reference at https://johannesbuchner.github.io/ads-reference-search/ 
It translates it into a ADS query and redirects you to ADS.

Licence
=========

BSD 2-clause. Code here: https://github.com/JohannesBuchner/ads-reference-search/blob/gh-pages/index.html

How does it work?
==================

Javascript parses the input and redirects you to the proper ADS search query. No data is stored on any servers, code is executed in your browser.

