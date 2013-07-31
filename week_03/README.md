http://flightrising.com/
Flight Rising

I decided to pull apart a new site that recently got a 38k kick start, not because  
of how flawless it is but instead of how freaking faulty it is! Now while I adore 
the site and find it quite fun to play around on I've been slowly picking it apart 
and finding more and more bugs, which with that big of a budget you'd assume 
wouldn't exist - at least not in the numbers they do. 

The site itself has XHTML 1.0 Transitional as the doctype which means that its using 
HTML4 the precursor to HTML5. This means the site doesn't always play nice with all 
browsers even though after checking this particular site on Chrome, Firefox, and IE 
it did work but I didn't explore too deeply. Also within the structure are oh-so 
many divs piled on top of each other that makes it look kind of messy. However it 
was pointed out that they did use HTML5 canvas on the fairgrounds but the buttons 
below it are using imgs as an interactive point which is incorrect because img files 
are content not interactive pieces. 

As for the CSS there is quite a bit of separate style sheets with tons of CSS to 
make the site look alright. Now after pulling the site apart in class I'm lead to 
believe their dev person really likes CSS but doesn't exactly know much back end 
coding, but hey I don't either so I can't make too much of a fuss (but I'm trying to 
learn more!). There is some jQuery plugins on the site, mainly used to make images 
pop up or for gallery type elements. But overall the site is a mess and after 
highlighting some of the issues in class I think I have a better idea of just why 
it's so buggy!