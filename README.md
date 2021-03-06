My Sommelier Personal Wine Cellar Management
======================================

This application uses Kartik Yii 2 Practical-B Application Template

History
======================================
MySommelier was born from a personal need to manage my library of wine accumulated over many years.  
As a private wine collector, after you get beyond 30-40 bottles is difficult to remember off the top 
of your head how much of which variety/vintage/winemaker you may have on hand.

When I looked around, I found 2 types of apps available (web apps and phone apps).  There were 
several web applications that offered to allow their registered users to manage their cellars.  
In addition to all the advertising clutter, none of these sites had a good user experience for 
actually entering your wine data.  They focused on data normalization (to support marketing and 
analysis) over usability.  They were clunky, hard to navigate and confused with all kinds of 
data that most of us just don't care about. I did find some very good phone apps out there, 
but those with the best UI and features were phone-only.  There was no web browser interface.  
At one point, I sat down for several evenings and went through adding my inventory to the app 
one bottle at a time.  Then, after I had it all loaded, I thought I'd like to see how many 
bottles of zinfandel I had.  Well, there were no "reports" nor was there and easy export option.
The phone is a good way to manage 1 bottle at a time, but not a good device to manage your entire 
inventory.

This all got me to thinking:  What I'd really like is a web based wine cellar inventory management 
system that had an easy to use web browser front end that I could access from anywhere AND a mobile 
application version that provided a subset of features that I wanted to access "while on the 
road".  I looked around quite a bit and found nothing that really met my needs.

So enter MySommelier.  After building most of the needed functionality, I made the decision to 
refactor the entire application into the much more modern Yii2 framework.  I am using the v1 as
a functionality guide, but I will be fixing all the user experience and DB issues I ran across 
during my first go-round.  


It's a pretty standard PHP/MySQL web application built on the Yii2 Framework v2.0.5 and 
includes RESTful interfaces for selected data objects/functionality.  With the Yii2 Framework, 
I've added 3 themes to support normal PC or laptop, tablet and mobile phone formats.  It's just 
1 application with auto device detection and themes to customize the view to the device.  
Not all functionality is available in all views.

The RESTful interface provides a external interface opening access to your own cellar data and 
all the reference data. 

I've focused the mobile features around 3 primary use cases:

"I'm at my cellar, managing my wine inventory"

- I'd like to quickly add, delete, increment or decrement a wine
- I'd like to know how many bottles I have, of what varietal and what region
- I'd like to add/delete/update wineries, regions, appellations and varietals
- I'd like to add/delete/update users and user permissions


"I'm wine tasting at a winery"

- I'd like to see what I have in my cellar
- I'd like to capture notes/comments about what I'm tasting tasting
- I'd like to take a few pictures (of wine and the winery) and attach them appropriately
- I'd like to capture a purchase of a wine

"I'm at a store"

- I'd like scan a barcode and see if that wine is in my cellar (or has been)
- I'd like to record a price for the wine
- I'd like to capture a purchase of a wine

The Team</h2>

	Jim Kreth - all in one
