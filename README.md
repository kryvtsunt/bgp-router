Project2
TEAM: doesnt_matter
TEAM MEMBERS: Tymofii Kryvtsun, Carter Codell

This is a submission of the BGP Router (CS 3700 project2).
For this submission we've implemented basic functionality to pass all levels of tests and the extra credit.

###Our high-level approach was:
1. Scratch our heads for an hour before paying attention to the "Implementing your router" section.
2. Add the most basic support for update/data messages.
3. Be able to reply to dump messages with table messages.
4. Follow the steps listed in "Implementing your router" to correctly implement our router.

We implemented some of the "helper" functions we thought would be included in the Python `ipaddress` module. These included `mask_2_cidr()`, `cidr_2_mask()`, `apply_netmask()`, `in_subnet()`, `aggregate()`, and all of the functions for comparing routes. It was nice to make these functions first because once we knew they worked we did not have to worry about doing that math again.

###Our biggest challenge was overcomplicating things.
For the milestone we needed to only provide basic support for update and data messages, we ignored this at first and tried to do everything for the update and data messages. We had some trouble aggregating the routes as we would add the aggregation and the initial two routes to our routing table.

###For testing, we compared handwritten messages with carefully placed print statements telling us what was being sent to whom.
