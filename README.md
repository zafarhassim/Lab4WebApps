# Lab4WebApps

Lab 4

The purpose of this lab was to demonstrate some of the location-based features regarding the Mapbox api. These features are the ability to export a map designed in Mapbox studio (an online map editing web app), the ability to make a marker on the map from a small geoJSON format and the directions map api.

Mapbox studio enables the user to create both 3d and 2d maps, show elevation and other traditional map features. Using Mapbox studio, I enabled a 3d terrain with the 3d buildings being the color brown. This went best with the opacity level because the map directions api does not enable the user to view the map from anything other than a top-down perspective. One of the key features of this is to point out specific points in a map. I did this with 3 specific areas; being Brooklyn College, Coney Island and Bush Terminal Park. The landmarks are denoted by a white flower with a black circle for a center and a green outline.

The second ability was the ability to make a map maker from a geoJSON format located within the script tags. While I was able to get this to work with the default values provided by Mapbox’s documentation, the process proved to be highly inaccurate using other longitude and latitude values. I used Brooklyn College’s coordinates and the results were highly inaccurate. The results were from values on the other side of the Earth. Other values did the same thing. Thus, I used the default values provided, San Francisco and Washington D.C. . Looking at how points in a map were created in Mapbox Studio compared to the geoJSON method; I feel had there more accurate coordinates provided that the geJSON method would have worked. In Mapbox the coordinates went 7 decimal places past 0.

The last feature added was part of the directions api. This provides the user to directions from a beginning point to an endpoint.

This site was deployed on Netlify. https://adoring-keller-d4a7bd.netlify.app

video demo here https://youtu.be/BixyC88k6kI
