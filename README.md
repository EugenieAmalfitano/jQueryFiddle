This is a project for practice with jQuery that is based on the fiddle tunes in Laura Ingalls Wilder's "Little House on the Prairie" books. 

There is a web site at http://www.liwfrontiergirl.com/fiddle.html that has many of Pa's tunes, together with the literary context in which they are referenced in the book series, as well as the corresponding .mid audio files. 

I wanted to extract just the tune names without all the additional text and links. 

jQuery is the perfect tool for the job. 

The file "ExtractPa'sTunes.html" embeds the downloaded page from http://www.liwfrontiergirl.com/fiddle.html, and adds the jQuery script which creates an ordered list. 
The script locates all links on the page and inserts the text of each link as a new list item. 

Note: minimal changes to the original HTML were made:
```
 1. <P> tags were changed to <P /> for compatibility with VS Code
 2. A <P /> tag was inserted after the line <H2>Pa's Fiddle Music </h2> to allow
    the subsequent text to be hidden in the output. 
 3. Format on Save is enabled in VS Code which may have made minor HTML formatting changes.
 ```
 
To run, just download ExtractPa'sTunes.html and open in a browser. The original content is suppressed, and the concise list of tunes is displayed. 
