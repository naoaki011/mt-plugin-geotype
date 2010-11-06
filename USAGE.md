This document is for Movable Type Editors who regularly author or manage content.


# Creating a Map

In one blog, go to Create->Location, and, in the new dialog box, type an address. It gets submitted to GoogleMaps when you click "Geocode", so it's pretty good at mapping nontraditional addresses like these:
    21st Street and 6th Avenue, New York, NY
    Central Park
  
If GoogleMaps doesn't recognize your address, the preview will just show a map of the whole earth.  


# Editing Maps

Manage -> Assets lists all the assets (images, locations, etc) you're using in the blog.  Click "Locations" Quickfilter in the right sidebar to list only the map assets, then click on the Title of any of them to edit.

To update the address of the location, modify the <b>Description</b> field.  Modify the <b>Label</b> field if you want to change its name.


# Putting a Map in your Entry

Once you've created a Location, associating it with an entry is easy.  A new "Locations" heading should appear in the right sidebar of the Edit Entry page.  Clicking (+) Add will list the Locations from most recently created to least.  Choose one here, and <b>save your entry</b> to associate the Location to your entry.




# Good Things To Know

* If there are multiple Locations in a entry, they'll appear in the same map with distinct pincushions.  Googlemaps centers the map the best it can to include both points within the zoom level configured in that blog.

* The "skeleton" zoom controls are present by default.

* Clicking on any of the pincushions will show the Name of the location and the Address on the next line.  

* There isn't a limit in the plugin to how many locations you can have in one map, but once you have more than 20 or so, it's slow for GoogleMaps to load it all, and users usually get impatient about it.

* All the maps in a blog have the same default zoom level.  They can be changed in the Plugin settings for GeoType in that blog, and require a rebuild of affected entries to take place.  


# Tips

* Just like image assets, you can reuse Location assets in several entries.

* And, just like image assets, you can tag Location assets for easy discovery in the future.  In this example, I have a Location asset for Central Park that I tagged "@map-landmark" not for the extra publishing logic, but so I can look it up in MT quickly to reuse it later.  Find tagged images in the Manage->Assets page 

