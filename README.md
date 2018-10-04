Project2 (Milestone)
TEAM: doesnt_matter
TEAM MEMBERS: Tymofii Kryvtsun, Carter Codell

This is a milestone submission of the BGP Router (CS 3700 project2).
For this submission we've implemented basic functionality to pass first 2 tests.
At this point, our router can update it's routing table and do simple forwarding of data.

Our high-level approach was:
1. Scratch our heads for an hour before paying attention to the "Implementing your router" section.
2. Add the most basic support for update/data messages
3. Be able to reply to dump messages with table messages

Our biggest challenge was overcomplicating things.
For the milestone we needed to only provide basic support for update and data messages,
we ignored this at first and tried to do everything for the update and data messages.

For testing, we compared handwritten messages with carefully placed print statements
telling us what was being sent to whom.