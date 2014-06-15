###Overview

The University of Ghana Guest Centre has a reservation problem:
their reservation "system" consists of a binder, with forms filled
out for parties, desired accommodations, start and end dates, etc.

When a party checks in, they are moved onto a spreadsheet of room
occupancies.  When a party checks out, they are moved off said
spreadsheet.  Aside from the problem that people aren't required
to checkout when they say they will (apparently), it is...less
than straightforward to talk about availability using this system.

###Requirements

Computerizing the existing process into a useful scheduling system
should require relatively few components:

- be able to state occupancy *now*
- be able to state expected occupancy for some future date

in order to accomplish those, we need:

- data about the rooms (how many, what type)
- ability to add reservations
- ability to modify reservations
- ability to cancel reservations

reservations 
