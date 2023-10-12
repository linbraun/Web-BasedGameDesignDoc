# Web-Based Game Design Document
### Design document covering scenario requirements and recommendations for operating platform, storage, memory management, and distributed systems/networks for a web-based game
CS 230 - Operating Platforms | November 2022 

### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room company has requested we develop a web-based version of the Android only game Draw It or Lose It. The software design must include the ability to have one or more teams, each team having multiple players assigned to it, only one instance of the game in memory at any given time, and that each game and team name are unique from one another.

### What did you do particularly well in developing this documentation?
I feel I was quite thorough in developing this document by making sure all options were displayed objectively before openly voicing my recommendations. I also was sure to not give too many options and stick to the most important information, making it easier to digest at any skill level.

### What about the process of working through a design document did you find helpful when developing the code?
The design document helped me plan the direction I would take in developing the code, saving time and resources on avoidable mistakes. This was especically helpful when deciding on the operating platform, storage and memory management, and distributed systems and networks. It was important these systems worked well together and offered all the necessary requirements of the client before beginning development in a system that may have been incompatible if not fully addressed before development.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
The design constraints section of this document was one of the first I completed, so I think it would benefit most from a revision. I had a much better understanding of the design contraints by the end of the project due to the amount of new information I had collected, so I think I could provide a more detailed description of these constraints now then I could initially. For instance, I introduced the idea of server constraints but only scratched the surface. Memory, storage, security, and networks are all constraints within this topic that are important to consider upfront, as it will directly impact the overall design.

### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
The user's need to have only one instance of the game in memory at any given time lent me to recommend a singleton design pattern. To implement this design pattern, it is important the software is designed with this in mind from the bottom up, since it impacts much of how the rest of the code works together. Security was another important need of the client, which was important to address early on in the design process, since security options rely heavily on the choice of operating platfrom, making it quite difficult to change down the line.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
The use of a game design document helped me approach the software design with a more informed and comprehensive plan. The strategy of breaking down each design constraint and requirement, and the options available to best address them, before jumping into development is certainly one I will use regularly in the future to analyze and design most any software application. When designing similiar software, the information and techniques I've learned about web-based client-server pattern software will be tools I reference often, like their compatibility with one another and the pros, cons, and traits of each.
