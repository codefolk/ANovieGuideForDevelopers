# Introduction:
Accquiring Skills is important for getting a Job, suppose you worked hard learning a skill and you passed the interview.
You are hired but what's coming ahead, you're not aware of.
Here we'll look how a developer spends his day at workspace.

## A Day in developers Life:
Suppose you start your day at 6:00 AM in the morning and do all your chores and get ready for your work and be at office at 9:00 AM.
Following is the possible work flow at a workspace.
### AT 9:00 AM:
You go to your work desk and update all the packages and sofwares on your machines, a daily check for updates is important at the start of the day so everything is up-to-date and you don't encounter any bugs or update remainders while working on a projects.
Having everything up-to-date really improves the accuracy and outcome your work. After chechking
for updates now is time for getting started so in every workspace there is some kind of notice board or online software which keeps the track of work like To-Dos and completed work etc...
You need to look at it, so you'll know current status of the project like what other members have done while your where at home or sleeping.

Most of the projects uses github so that everyone can work as a team on a same project. You'll start by making sure that you have all the latest files of the projects by using command:

	git pull

this command will fetch all the up-to-date files on you pc.
if you're not familiar with github you can look here https://github.com/skills/introduction-to-github

### AT 10:00 AM:
After you have your workspace ready now is the time for a little briefing where everyone gives updates about the project. The meeting is organized by the Project Manager. Depending upon the project this meeting or briefing can be scheduled on daily or weekly basis. In this meeting everyone working on a project tells the project manager what we did yesterday and what we'll do tommorrow or if you're stuck at something you can ask help from other senior developers. This meeting also includes an PO (Project Owner) who is backing the project. A PO can be anyone maybe your employer or any potential employer.

### AT 10:30 AM:
The meeting usually last 00:30 mins if scheduled on daily basis and by the end of the meeting you return back to your workplace and start working.
As a developer you may work on:

*  Bugs
* New Features
* Updating old pieces of code
* Improving accessibility

These things can vary depending upon your skill set but everything you'll do is already decided on the To-do's list. Usually these include working on small updates or making any change according to user feedback.
You'll select something from To-do's and start working on. The work can also be assigned by the Project Manager. After you have selected or you're assigned with work you can make a new branch by using following git command:

	git branch newBranchName
	git checkout -b newBranchName

Now you can start working on the feature or bug depending upon your work.

### AT 2:00 PM
So, now you have done alot of work and probably it's time for lunch break or coffee break. They timing of this break can vary from wrokplace to workplace. After the lunch break you now return back to your workdesk and make a PR (Pull Request). Pull request can be made by updating the branch and using following commands:

	git status
	git add .
	git commit -m "Type here the about the status of your work"
	git push origin branchName


### AT 3:00 PM
Suppose you did everything good and changes are approved and merged into the main project now is the time for QA (Quality Analysis). This is an important part of the job where you or someone else checks whether the Project which can be an application or a web app works perfectly fine and changes you made will not affect the application and also make sure there isn't any bug left.

### AT 4:00 PM
After approval from the Project Manager and Passing the Quality Analysis you have marked your work as done someone who has ownership of the project which can be a senior developer or project manager will review your work or  changes you made in existing code. if the changes or feature you built is good He/She will approve the the pull request and merge the branch into main project. However if the changes or feature is not approved or it doesn't pass the Quality Analysis then you'll be given with a review about it which later you can work on and make another pull request untill it's approved and merged into the main project. After merging the into main project now you have to let know that you have made these changes and these changes are now a part of the project. You can do that by putting on the Completed Works on notice board or log it into the application which you're using to keep the track of your project.

If Somehow two developers started working on same feature and ended up making a two separate changes in same feature github will mark it as a conflict and ask you to resolve the conflict which is a nice feature of github.

### AT 5:00PM
After completing work you can now head back home and follow your daily routine and the cycle goes on.

## Final Words:
This is guide made for general developing workplace you schedule can vary in case of a night shift but the main purpose was to give you an idea about your first day at Job.
Hopefully this will help you get through your first day.

$$Author:Muhammad Zohaib
