# HoriseonMarketingHW1

## INTRODUCTION:

This project was to take an existing page and make it accessible by implementing semantic HTML and to make sure the code follows a logical structure. The code should have alt tags, coding for the headers should be in sequential order, and the title is concise and descriptive. This will provide any person with a visual impairment to be able to access the site because they can see what is on the screen or there is code for a screen reader to understand and deliver. 

## FIRST IMPRESSION

Upon going into this, I really felt like I was driving blind. I know the feel of the car but have no idea where the car is going. Coding this, I felt I knew certain things, but had no idea what those things would do. I made so many wrong turns that I would start over completely. 

Essentially, there were a TON of <div> tags, a link that would not work, some contrasting issues on the benefits section, no alt tags for the images, some extra tags hanging around (like one closing img tag).
  
Prior to this project, I didn't really understand accessibility standards, and really didn't know it was a big thing to work with in web development. Once I felt like I understood what it meant, I dove into the coding and completely got lost. First attempt all I did was add alt tags and clean it up a bit. I failed to read "semantic html" in our criteria, didn't know what that meant either, and thought I was done with my homework. Only, I found out that I was completely NOT done with the project.

I went back in and this time tried multiple times to change out the divs. I was using tags for aside, header, main, section, etc. My "boxes" kept getting all wonky... meaning they would not stay aligned. So then I spent hours looking at clears and floats. This did not help. I adjusted the widths, percentages, positions, etc. Still the page would not line up properly. Scrap it all and start over. I did this about 6 times before I reached out for some guidance. Turns out I was making it super confusing for myself. 

I would do this: <header>, <header class="header">, </header>. Or I would put <section> tags around all the different classes in addition to <section class="content">. Basically, I was adding an "opening tag" twice. 
  
Turns out, I just needed to rename all the "div" to something more descriptive so that if a person who is visually impaired would be able to access the site with their screen reader, etc.

## CODING

To start, I changed the <title>website</title> to <title>Horiseon</title>. This is consice and descriptive enough to where the user is. 
I adjusted the first link in the top navigation section so that if you were to click on "search engine optimization" it would bring you to that point on the page. In the tag, it was missing an "id". I added <section id="search-engine-optimization" to the code (section class="search-engine-optimization">) that was already there. This fixed the link.

<span> was in the logo as "Hori<span>seo</span>n" however the <span> tag is not semantic html. I chose to go with "Hori<em>seo</em>n". It gave the same appearance as the original code, however it is more semantic friendly and thus more accessible.
  
Another thing to think about is CONTRAST. If there isn't enough contrast between the background and the text, a person who is visually impaired may not be able to read it. The "benefits" section that is to the right of the page had a slightly lighter background than the "content" section, which created a contrast error when checking accessibility. I changed the "benefits" section background from #2589bd to match the "content" section background color of #0072bb. This change eliminated the contrast error. 

<div> tags are also not semantic html friendly - they are not descriptive enough for something like a screen reader to follow. I changed all the div tags to correspond with their content.
For the "content" section, I chose to go with the <section> tag because the content all related. And for the "benefits" section, I chose to go with the <aside> tag because although it is somewhat related to the whole content, it is more of an extra to the main content. And being off to the side, it made sense to put it there.
    
I removed any superfluous tags or code, such as an </img>tag, empty tags, etc. 

## SUPPORT USED

I visited W3Schools, Stackoverflow, YouTube, and CSS-tricks in addition to my TA Nathan. 



