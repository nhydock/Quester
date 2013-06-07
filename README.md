#Quester

####A student/student, student/teacher, employee/employer gamified Task-Tracker


Inspired by a Theories and Approaches class offered at Shippensburg University on Gamification of Reality, Quester is another form of Alternate Reality Gaming to help make doing things for others more fun.

##Why are you doing this?
One of the issues with the class that we had was the idea that students could create quests for each other to do.  While the idea was great and fun, tracking progress was a bit difficult for some students.  Not only did we have to worry about keeping track of what quests we completed, but when we completed them and if the person in charge of the quest remembered to report that we completed the quest.  When a student has a lot to do with other classes, it's easy to forget all of this kind of information.  Quester is a website intended to streamline and automate this entire process.  

##How is it designed?
By using a combination of modern web technologies, making use of Javascript/ASP and an easy to setup CMS, any member registered is capable of creating quests as well as taking on quests.

Quests consist of 5 main components:
  1.  A Title
  2.  An overall description/plot (yes, you can be as creative as you want)
  3.  A list of steps/tasks with description of what each step requires
  4.  An expiration date
  5.  How many times the quest may be completed by the community

The quest tracker will keep track of all quests that you have decided to take on and show your progress.

To advance your progress, you must submit a request to the quest giver to confirm your progress.  Upon submission, the quest giver will recieve an email notifying them that you are requesting progress approval.  If you do not complete the quest by the time of expiration, you will only recieve credit for how much of the quest you have completed by expiration.  If you have requests awaiting confirmation by the time the quest expiration date occurs, the quest will only expire or be completed upon response.  If a response has not be recieved within 15 days, it is automatically rejected (similar to a pocket veto).

##What are the rewards?

Ranking and achievements are rewarded both for quest givers and those who complete quests.  Server leaderboards will also be present for users to compete against each other within their work environment.

XP is rewarded for each task of a quest completed, with an addition bonus for full completion, and a small portion of which is also rewarded to the quest giver for each time a person completes their quest.  This is to reward both the user for their hard work as well as the quest giver for creating an enjoyable and well recieved quest.

All quests can also allow users to work together to complete them.  Quests can recommend an amount of users to work together.  The more users working on it, the less each user will be rewarded in XP.  On the plus side, it lessens the amount of requests the quest giver must confirm because requests are sent for the group.  Also, the teamwork to get the task done faster can be worth a lot more than just some XP.

If your request for completion confirmation is rejected, you are dropped down to whatever your xp was before the request.  This encourages students to not check everything off and go for 100% with every single request.  Creating smaller requests are tactically intellegent 

Some examples of Achievements would be:

* First Quest Made
* A True Adventurer (50 quests completed)
* A Helping Hand (1 Shared Quest Completed)
* Words of Importance (Have a quest of yours completed 50 times)
* Suck-up (Complete 10 quests created by a moderator that weren't mandatory)

Achievements can be defined by the server maintainers to give a different feel for each gamified work environment.

##How do you intend to keep the system balanced?

It's obvious one of the big issues to quests is people creating simple quests that give a lot of XP with a long expiration date.  There are a few counter-measures planned to prevent these kinds of issues.  These counter-measures are all server-based options customizable for every workplace

* Maximum Quest Age (30 Days)
* Maximum XP per Task Reward (50 XP)
* Minimum-Maximum Task Limit (1-10 Tasks)
* Moderators (Default is 1 moderator: the one who registers the Server, but moderators are not required)
-- can require approval before a quest may be visible to other users 
-- can create Required Quests which take up an active quest and will remove cost the user XP if not completed
* Maximum Active Quest Limit (3 Quests, prevents students from doing only each others quests instead of actually worrying about class work)

##What are all the values that a user can be ranked by?

* Total XP earned
* Number of quests completed
* Number of shared quests completed
* Number of quests attempted
* Number of people served
* Number of quests created
* Most played quest created
* Number of people who served you
* Number of times your quests have been completed

##What inspired you to design this?

Aside from the class, there were plenty of other influences.  I was already working on a video game for teachers and students that was going to incorporate this kind of quest system to allow real life intercommunication with the virtual world.  Stack Exchange with it's Question/Answer system with voting and achievements, plus competitive nature with results of helping others was also a large influence in this idea.  In the end, though, I wanted something less like an online forum and instead just an online quest log so then users would have to interact and help out in the outside world to be able to be competitive online.

In my analysis of gamer psych, a lot of people are naturally competitive, and one of the best feedback for a person to show that they're better than another is through numbers.  We see it everywhere, from exam grades where students compare their scores with one another, to things like racing where the fastest wins.  Even people who are shy tend to find thrill in it, and those who are always losing take immense amounts of joy upon surpassing a collegue.  For some the competitiveness found through numbers is enough to spark outrage or even spark an adreneline rush.  

The leaderboard system in plenty of games reflect this competitiveness, and rising through the ranks also improves the mentality of the person succeeding.  Furthermore, when one falls down the rank, normally they are not discouraged.  Instead the person is motivated to get back up to where they were.  The only people who tend not to have motivation are those just getting started and are at the bottom of the ladder.  However, as soon as they start climbing, it's hard to want to go back down.
