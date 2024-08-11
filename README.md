# Chess Giant

## Background
Jim Sotheby, a successful entrepreneur and master chess player, plans to launch a platform called "Chess Giants" for elite chess players with a rating of 2200 or higher. The site will require members to pay $1500 annual membership fee. To become a member, players must go through an approval process by the administrator until an automated integration with US Chess (www.uschess.org) is developed later.

The site will enable members to:

* Play chess with other members online.
* Challenge other members via email.
* View the top 10 players and challenge them to a game.
* Post and discuss game strategies and results, with moderation by administrator for content management.

## Project Detail
### Stakeholder interview and Requirement Gathering

  Through an interview with Jim, we gained a better understanding of the business and gathered requirements which we later used to define scopes of the project.

  Some of the questions asked during the initial stakeholder interview includes

  ** What are you trying to achieve by building Chess Giants?

  ** How do you envision your players using your website? What can players do and cannot do?

  ** How much budget do we have to build this system?

  ** How does your schedule look like for us to go over the document of the process?

### Requirement Gathering

  Next, we would translate these business needs into project's scopes and defined functional and non-functional requirements and generate the Business Requirement Document (BRD).

### Identify Functional Areas and Build Decomposition Diagram
  There are 5 Functional Areas highlighted in this project which are Registration, Payment, Game, Admin and Forum.
  
  * Registration: processes player sign-up, email verfication, player rank verification, and account establishment.
  * Payment: processes payment and sends payment confirmation email.
  * Game: covers game related processes on the site, including search for and challenge players, the actual game played, and save player's record of winning or losing the games.
  * Admin: manages Membership application and its approval as well as review contents posted/uploaded by members and remove unappropriate contents.
  * Forum: Forum allows players to create and publish a thread/post, and post comments on selected post.

### Designs: 
* Activity Diagram

  The Activity Diagram uses UML Diagram and provides a visulization on how activities flow from one onto the next, including how the system responds to prompts given by the player on the site. There are 2 Activity Diagrams designed on this project. 
    * The first Activity Diagram showcases step by step journey a player takes to search and challenge other players on the site. 
    * The second Activity Diagram shows the steps when a player posts their game on the forum.
    
    
* Data Model and Wireframes

  * Data Model:
    * We use the Crowsfeet Diagram for the Game and Forum Functional Areas.
    * This Logical Data Model represents the organization's data and shows the relationships between different entities in the identified Functional Areas.

  * Wireframes
    * Taking the Activity Diagrams above, we designed the Wireframes on Microsoft Visio. The Wireframes visualize the steps taken by player in searching and challenge players, and when the player wants to post a thread orpost comments on an existing thread on the Forum. Additionlly, we provide the Use Case statements for each case that show how the system responds to actions taken by users.
