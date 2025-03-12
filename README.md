Project Description

  For this project, we were tasked with an assignment to create a travel destination website where the user can select from a small assortment of "destination cards", each a different location. When the user clicks on one of the travel destination cards, they will be taken to another page for that location/destination in particular. Inside each detailed travel destination card will include an enlarged picture of the preview that was seen when the user could see all destination options on the homepage, an extended/alternate description, as well as three main sections: One section being a recommended itinerary for what the user should do at that particular destination, another showing the destination on a map imported from the Leaflet library, and a third section acting as a booking form for if the user would like to travel to the destination. 

Functionality

  Clicking on the button at the bottom of any specific destination card will redirect the user to a new page that, as previously mentioned, displays more comprehensive and detailed information about that destination. The image will be larger, and data will be pulled from an existing JSON string within the script. The booking form within each destination card checks to see if all fields have been filled out by the user upon them clicking the submit button at the bottom of the form. If any of the input fields are not filled out OR filled out in a way that does not make sense (the booking date being in the past, 0 travelers, etc.), the form will notify the user. If every input is valid, though, the website will send a simple alert to the user that a tour has been booked. Both the homepage and the destinations pages adjust to the size of the screen as well through flexboxes, becoming more vertically arranged the smaller the screen is. Additionally, there is a search feature on the homepage that filters through all available destinations depending on what letters the user types into the search bar. If a location/destination contains what is in the search bar, it will remain on the screen. If the name of the destination does not contain what is being typed into the search bar, then the destination will be removed from the user's view and hidden away. 

Languages and Tools Used

  - HTML
  - JavaScript
  - JSON Strings
  - Leaflet Library (for the map)
  - CSS within the files
