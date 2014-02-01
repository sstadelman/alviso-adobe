#Mobile App for Alviso Adobe Park
##Proposal
As a frequent attendee of the Alviso Adobe park, I would like to volunteer some development effort to contribute a mobile app for iPhones, which allows community members to instantly view today's events and weather at the park, the calendar, and information on the park and its history.  In the future, it could potentially also display information on the collection pieces, contain audio guides, etc.

The concept is to make information important to patrons' decision to visit the park (weather, calendar) immediately available on their mobile devices, and then enhance their experience once in the park, with info and a map.

##App Design
The application will be implemented according to Apple iOS7 user interface standards.  This means that screens will adhere to a 'content-first' design principle which prefers text, images, and effects to concrete user interface elements like buttons and tabs.

The initial concept is that there is a series of screens laid out horizontally, ordered according to the end-user's current location and tasks.  Users swipe horizontally with their thumb between the pages.  

The entry to the app is a "Today" page, which lists the events on today's calendar, and the current park weather.  The next page is the calendar view, which shows a table of upcoming calendar events.  Users can tap on events to go the event detail page, where they can see the full event info, and click a link to jump to On-line registration (this would link to the main website, and launch in Safari).  The third page is a park overview, which includes text and images from the website.  The fourth page is a pdf of the park map, which a park visitor on-foot would use within the park, to find out about where the main attractions are located.

<img src="https://raw2.github.com/sstadelman/alviso-adobe/master/page1.png">

##Required Resources

1.  In order to implement the app according to this design, the city events calendar should be made available as a read-only REST API for GET requests.  The format of the service should be JSON.  

2.  High-res images (~640 x 1200) of the park would be needed for the screen background images.  These will be partially covered by text & blur effects, so they should more along the lines of "landscape"-style of the park, rather than action shots.  (It might be ok to have people in the photo used for the "Today" page.

3.  A pdf of the park map would be needed.

