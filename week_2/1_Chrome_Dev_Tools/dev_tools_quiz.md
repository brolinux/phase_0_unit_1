#### Include an inline screenshot of your codeschool's points from the profile page:

<!-- Modify the Markdown to include your answers. Don't delete the questions! -->

##QUIZ
* Explain which tabs support the following actions and how.
  * Realtime editing of HTML and CSS 
  * Javascript Debugging
  * Performance Optimization 

* What's the quick key for your OS to spawn the Dev Tools inspector?

* Go to http://www.postmachina.com/ and analyze and tweak this nicely designed page.
  * What is the current background color for the page?  (Surprisingly, it's not just black!)
  * Tweak the background color to white.
  * Tweak the height of the side bar that contains the logo.  Shrink it down to 85px.
  * Roll over the navigation links.  When you hover over them, they dissapear.  Let's change the hover color to black instead.
  * Now take a screenshot of your new (and maybe not so improved) design.  It should match this screenshot: http://postimg.org/image/5ak1jkpl5/
  * Upload your own image to the imgs directory in the `1_Chrome_Dev_Tools` directory.  It should match the image above. The last nav link in the image above is black because the mouse was hovering there when the screenshot was taken. Do the same, and don't take a screenshot of your whole desktop, just the browser window. (This is part of the challenge.)

* For the postmachina website, why can't you tweak the color of the text "The most important things are not things"?  Please explain.

* Go to www.ticketswizard.com and analyze the page.  
  * What is the largest image on the website? 
  * Explain how you would find out this information, and list the URL of offending image here and how big it is.

* Test the www.ticketswizard.com website with google's [PageSpeed Insights](http://www.ticketswizard.com/).  (You can also download the chrome plugin).  What is the easiest thing to change to optimize the website?  How many kilobytes of data can be eliminated?
* 



* Explain which tabs support the following actions and how.

To edit the HTML we would open our Dev Tools and Elements panel. By clicking on magnifying glass in Chrome we can hover the page and see different parts of the page become highlighted and simultaneously see the corresponding HTML become highlighted.
When in Elements panel it opens a side panel called styles. This allows us to see the corresponding CSS for that element.
To inspect Javascript on the page  we would look to the right of the Elements panel for Console. 

Debugging JS
The Dev Tools panel can show us, in red type, that we have an error with a JS script on our page. Inside the console we can call function names and see what value they return and whether it's the value we were expecting. 

Performance Optimization
There is a panel called Network, that allows us to re-upload the file. This time the Dev Tool displays the number of files that the page linked to, be it JS or CSS files or image files. Along side its display of the files, it reads the weight of each file and how many seconds it took the server to fetch them in order for the page to display as one complete entity. If we see a great gap open between one file to others we can take time to see if there is a way to load that file last on the page (lazy load) or make that file smaller, if it's too slow to load due to size.


* What is the current background color for the page? (Surprisingly, it's not just black!)
 
Background-color is #0B0F11


* For the postmachina website, why can't you tweak the color of the text "The most important things are not things"? Please explain.

It appears to be an image. Images are external to the HTML page, they are files that are linked to by the tags on the page. Any editing on these files will have to be in a photo editing program outside the Dev Tools ability.


* What is the largest image on the website? 

2624182-c482-4a35-8da2-4fbf2f502e94_Large_Large.png appears to be the largest coming in at  421.26kb it took 93ms to load.
The way I found this out was I went into google and searched keywords "Dev Tool image upload size." 
I then clicked on https://developer.chrome.com/devtools/docs/network?hl=zh-CN. In the Network panel I clicked on the images part of the pie chart that appeared, when I did a page reload. This took me specifically to a list of all the image files that were requested by the server, and I could order the list by greatest to smallest.

* What is the easiest thing to change to optimize the website?  How many kilobytes of data can be eliminated?

It looks the first place developers need to look at to optimize the page speed is the image size and optimize the images for fast web viewing. If the site had optimized correctly it would reduce its size to 885.9KiB (39% reduction).
