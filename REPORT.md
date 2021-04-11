# Report of the Mission

## Implementing The Design
For the initial columns, I used bootstrap to make it easier to navigate the sizing over multiple different types of screens as shown by the _results.pdf_.



For the styling and design, I went ahead with *@media* tag, to make the styling easier, most of the styles were relatively similiar across multiple devices but required different SVGs for mobile view, hence some rules were changed. 


## Constructing the HTML Document

The Javscript file ( *Emails.js* ) was the primary javascript file used which fills the empty lines in the HTML document. The document itself was pretty straight forward and empty since the javascript is doing most of the functions. 

## JAVASCRIPT AND jQuery LOGIC

I decided to go ahead with Vanilla JS and jQuery to display my skills at the best I can! 
Primarily the for loops iterates to go through the emails if the dates selected are in co existant with the dates on the emails. 
After this I decided to add a hidden div block to display the subject of emails which can be accessed or closed/opened via the onclick function. 

In case there were no emails found, Javascript would be used to display back the main logo and show that 0 results were found.  
After the initial for loop is iterated, another function is added with similar logic which sorts the emails according to date and from ( For mobile mode as displayed in the results . pdf ). 
This is run only if the date svg arrow has been clicked or from arrow.svg has been clicked.

