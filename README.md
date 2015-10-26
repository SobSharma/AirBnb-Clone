AirBnB clone using Model View Controller design pattern

Write all the user-stories of your airbnb MVP. Example:

- as a visitor, I can search for a flat in a city for given checkin/checkout dates
- as a visitor, I can signup
- as a user, I can login/logout
- as a user, I can book an available flat
- as a owner, I can add a flat announce
- etc..

Tasks organization

Here is a list of different things to do on the Airbnb project

navbar with working links (signin/signout, "My bookings", "Publish an announce", etc..)
flat's booking
add pictures to flat
add reviews to flat
add geocoding to flat and Gmaps in views
Facebook connect
Mailing between owner / user

Specification of Features

Model: I will create the Booking model and migration, with good associations and validations (crash-tested on rails console).
Routing: I will add bookings routes in routes.rb
Controller: I will create a new BookingsController
New Views: I will create views/bookings/new.html.erb for booking form and views/bookings/index.html.erb for listing current user's bookings.
Existing Views: I will connect the "book it" button of a flat's show view to my booking form and I will connect the "My bookings" link in the navbar to my bookings index view.
