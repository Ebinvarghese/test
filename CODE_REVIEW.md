Task1 :
Step 2 :

-->Create a new observable (resultListBooks) and use aync pipe to subscribes to the observable
File : book-searchComponent async pipe (fixed)
-> Use pipe operaters for the Date rather than calling custom function . (fixed)
File : book-search.component.html line 25 use date pipe instead of formatDate  
--> Error Messaging needs to be improved/added when the API fail eg in BooksEffects when we fail get data .
-> Implemnt service Worker to cache response which will prevent mutiple hits to the API

Step 3 :
Light House Report Data :
Buttons do not have an accessible name (fixed)
Background and foreground colors do not have a sufficient contrast ratio. (fixed)

Manual :
Image with no alt attribute for the results of the Searched Item and the close CTA in Reading List Nav
Ensuring that a contrast ratio of at least 4.5:1 exists between text (and images of text) and background behind the text
Field label is not visible for search Icon
