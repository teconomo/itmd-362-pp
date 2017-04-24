# Production Problem 10: A/B Testing on the Cheap

## The Problem

Locate an interface component on a website that you use frequently that you think could be improved. The improvement should be minor.

Take a screenshot of the interface on both a mobile and desktop device. Then, sketch or illustrate your alternate/"b" test. Finally, describe modification and the HTML, CSS, and JavaScript that you would need to write in order to conduct the test.

## Deliverables

* Screenshots of the interface component on mobile and desktop, placed in this directory (`pp-10/`)

* Sketch or illustrate (e.g., in Photoshop) your alternate/"b" test, placed in this directory (`pp-10/`)

* A text description of the modification, and a description of the HTML, CSS, and JavaScript that you would need to write for the test (you do *not* have to write the actual HTML, CSS, and JavaScript, however)


So I chose to fix up my Xsport Fitness Portal for my job. Trust me, there are SO many aspects I'd love to change on this site because whoever developed this website did one bland and lazy job.
I took screenshots of the Login screen for both Mobile and Desktop and then the Home screen for the mobile. 
The main aspect I'm choosing to renovate is the Login screen as a whole. As you can see from the screenshots, the Login page has a series of minor problems. First, I'd setup the form-box to be stationed in the center of the screen, regardless of which platform. There is too much empty space in this currently. I would alter the Form and its attributes a little to be slightly cleaner and modern to give a sense of up-to-date style and also for readibility. Color would also be changed to match and compliment the brand and logo which would be tints/accents of white, red, and black. 
Secondly, I'd also ACTUALLY add Media Queries for mobile and tablets.I know you said 1 component but I had to do this second one just because its sad that this was not implemented when they first brought this site to life. There are no media queries so whenever I use this portal (which is normally on my phone), it always requires me to zoom in and click on tiny little buttons and it strains my eyes.

For the code implementations, it would be pretty straight-forward. 
For HTML, I'd practically keep everything the same but I'm sure I'd need to add a variety of classes and ID's to certain attributes to then reflect them into the styling.
Most of the bulk of this renovation would be in CSS. I'd be dealing with a great amount of change towards padding and positioning for the Login page to somewhat center it and make it more appealing than seeing a great amount of emptiness. I'd put in some borders to show division between the Form area and the Full exterior page itself. Colors are pretty straight-forward. Lastly, I'd implement media queries for the platforms so that it is more user-friendly on other devices besides just Desktop.