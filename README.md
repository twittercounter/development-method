# SCRUM Documentation #

In this document you'll find all the basic rules and guidelines we have set up to ensure an efficient workflow within the Twitter Counter dev-team.

### Index ###
* [General](#general)
* [Sprints](#sprints)
* [Standups](#standups)
* [Stories](#stories)
    * [Adding Stories](#addingstories)
    * [Scheduling Stories](#schedulingstories)
    * [Accepting/Denying Stories](#aodstories)
    * [Taking Ownership](#takingownership)
* [Points](#points)
* [Velocity](#velocity)
* [Development](#development)
	* [Choosing Stories](#choosingstories)
	* [Prioritisation](#prioritisation)

* * *

### General <a name="general"></a>###

We assume members of the dev-team have 6 hour days, taking into account for breaks and waking up.

Product Backlog contains all possible items for the sprint, even if they will not be completed during this period.

Overview of general data:

* __Team members:__ 3
* __Sprint Length:__ 5 days
* __Sprint-Hour Capacity (Team):__ 90
* __Sprint-Hour Capacity (Member):__ 30


* __Last Sprint Velocity:__ --
* __Average Velocity:__ --


* __Sprint meetings:__ Every monday
* __Stand-up meetings:__ Daily, except on Monday, 11 AM, 15 min
* __Cool-down meetings:__ Every friday, ~4 PM

### Sprints <a name="sprints"></a>###

Each sprint lasts for __5 days, from monday to friday__, and will consist of 90 accumulative hours.
At the beginning of each sprint the scrum-master will address this sprint's general topic, and each developer explains their tasks and stories for this wee.
The product owner will talk about blocks and the focus of the sprint.

The sprint meeting will last __45 minutes__.

The marketing & sales team will also be present at this meeting to give everyone a weekly update.
This ensures that all members of the team are on the same page when it comes to goals in terms of both development, and marketing & sales.

Every friday there will be a pre-meeting between the product owner and the scrum-master.
During this meeting the topic and the stories will be chosen for the coming sprint.

At the end of every sprint, after the pre-meeting, there will be a show-and-tell session. This will happen __every other friday at ~4 PM, Amsterdam time__.
During this meeting all team members will show what they've been working on and talk about their progress.

After the show-and-tell sessions, the scrum-master will have a meeting with all the developers to discuss the stories and topic chosen during the pre-meeting.

### Stand-ups <a name="standups"></a>###

Stand-ups are short meetings to determine the status of the sprint and to get everyone on the same page.

These meetings happen __daily (except on monday) at 10 AM, Amsterdam time__, and will take place near the coffee-machine in the kitchen or at the coffee-bar, near the entrance of the office.
They will take __no longer than 15 minutes__, and everything regarding solving specific issues or helping with a bug will take place separately and won't be part of the stand-up.

Before every stand-up, all members of the Twitter Counter team need to update Pivotal Tracker.

Stand-ups can also be referred to as cofee-time.

### Stories <a name="stories"></a>###

##### Adding stories <a name="addingstories"></a>#####
All members of the development team, including members of the marketing & sales team, are allowed (and encouraged) to add their own stories.
They will then be the __requester__ of the story and responsible for adding __a clear description__ and a __screenshot, if applicable__.
All new stories will be added to the icebox.

Members of the dev team can assign ownership of the ticket themselves and, if they are able, should __add sufficient tasks__ to the story as well.
Other members of the team can leave the ownership blank. Upon scheduling the story, the scrum-master will assign an owner to the story.

##### Scheduling stories <a name="schedulingstories"></a>#####
The scrum-master will put all stories for the coming sprint in the backlog on monday.
Only the scrum-master is allowed to schedule stories.

##### Accepting/Denying stories <a name="aodstories"></a>#####
Only requesters of the story are allowed to accept or deny a story.
This is to prevent miscommunication and to ensure that the requester has seen the desired results.

On some occasions, the scrum-master will be allowed to accept or deny stories, in communication with the requester and clear understanding of the story.

##### Taking Ownership <a name="takingownership"></a>#####
When story is assigned to a developer, the developer is in charge of [assigning points to the story](#points).

### Points <a name="points"></a>###

Every developer is responsible for assigning points to the tickets they own, based on the amount of effort they estimate they need to complete the story.
Preferably this is done as soon as the story is added, so that the scrum-master can use it for sprints to come.

We use a Fibonacci sequence point system that looks this:
* __0 points:__ Quick fixes or implementations, everything from 1 minute to 15 minutes
* __1 points:__ Quick fixes or implementations, everything from 15 minutes to 45 minutes
* __2 points:__ Small features, everything from 45 minutes to 2 hours
* __3 points:__ Medium, everything from 2 hours to 6 hours
* __4 points:__ Large, everything from 6 hours to 18 hours

It's important to note that the points do not have a direct link to time, but rather effort.

### Velocity <a name="velocity"></a>###

Velocity calculation is kept simple: The amount of points the team delivers during a sprint.
The average velocity will be calculated by the total number of points delivered, divided by the amount of sprints it took.

The scrum-master uses the average velocity to plan in the stories for the next week.

### Development <a name="development"></a>###

##### Choosing stories <a name="choosingstories"></a>#####
In order to meet planning and work towards a common goal, developers are discouraged to add and then start their own stories.
They should focus on the stories in the backlog, rather than adding or working on other stories.

However, there are exceptions. If the need is dire, ask the scrum-master about the proper course of action.

##### Prioritisation <a name="prioritisation"></a>#####
The priority of the story is decided by the scrum-master and will be labeled with a priority tag.
All other stories have equal priority. Of course all stories in the backlog have priority over those in the icebox.
