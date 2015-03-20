# Google-Maps-Project
A simple google maps api project for school demonstrating various map functions including:
  • Loading Maps with Buttons
  • Placing Markers on Maps
  • Giving Markers Info Windows
  • Using Custom Marker Icons
  • Drawing on Maps With Lines and Shapes
  • Customizing the Map Controls
  • Changing Map Colours e.g. Roads, Terrain, etc.
  • Changing Settings on a Map After it's Created

For fun I decided to make the project look like the map was placed on a desk as if you were looking at a real map. Sticking with that theme, I decided to make the buttons to load other maps be real-world items as well such as postcards and boarding passes.

By default a map centered near Oslo, Norway is loaded. My family is from Norwary but I'm not sure where so I googled my last name on google maps and it gave me a place near Oslo called Skretteberg, so I went with it. I don't know how accurate it is but that's why the marker is placed there on the map. When my family lived in Norway they worked on a farm so the custom icon I chose for the marker was a farm icon. It then has an info window attached to it describing a bit about my family's name. 

There is then 3 buttons on the page, made to try to "blend" in with the other items that are already part of the background. The three buttons are:
  • A postcard of Ireland that changes the map to Ireland
  • A postcard of Norway that changes the map to the default map loaded
  • An Air Canada boarding pass that changes the map to show an air canada flight path from Edmonton to Norway.
When the Ireland map is loaded it is centered around Blarney and it displays a castle icon which when clicked displays an info window about blarney castle. The shapes drawn on the map are two rough estimates as to the layout/size of Blarney. The polygon is a rough guess based on roads and the circle is a rough guess based on population. The map also has different colours than the defaults chosen for roads and the like.

When the boarding pass is clicked it uses the same map as the Norway one and just changes settings such as the center and the map type rather than loading a whole new map. It is now zoomed further out and displays the flight path from Edmonton to Norway with airplane markers placed on each connecting city. When the markers are clicked they display the name and airport code of each airport the flight stops at.
