# Challenge One

## Description

This was an odd-numbered week, which means we got an on-the-job ticket assignment with starter code. The assignment wasn't to change the look of the website itself, but to make some internal changes in the code to make the page more accessible to people who use screen readers. Additionally, the assignment asked us to fix the header links to navigate to different sections of the page, and to make the code itself more semantic for future coders who look at it. 

Accessiblity is very important...everyone should be able to use and benefit from the same websites as anyone else, no matter if they have a disability or not. As a developer in training myself, semantic code that's more specific is much easier for me to read than code with all the same tags. But you don't have to be new to want code to be easier to read. 

While working on cleaning the CSS, I managed to get the paragraphs for the SEO section and the Social Media section to go below the photos and couldn't figure out how to fix it. With my tutor, we discovered that I had two different classes set for left-floating images: one before the file name and one after the file name. The one after the file name (float-left) was not being read. 

I learned that having elements in more than one class is fine, but you should label the classes in the same quotation marks (before the file name) separated by a space between each name. Once I moved the float-left label to the beginning, my page was immediately fixed.

To get the links in the header to go to each section,  I added id tags to each of the section h2 tags. The id labels were exactly what was already written in the header, but before, nothing happened (except the URL changed). This was something I didn't know how to do and learned while working on this project.

Additionally, I learned about how <div> tags used to be way people divided their HTML into different sections, and how when HTML5 was introduced, new elements were brought in to replace it to make the code easier to break down.

## Installation

N/A

## Usage

The website is for a digital marketing company called Horiseon. It's a single page website that gives potential clients an introduction to their services, and why their services are important in a digital world. 

## Credits

I was able to do most of this project on my own, but my tutor, Corrado Alfano, helped me get the task all the way home. 

