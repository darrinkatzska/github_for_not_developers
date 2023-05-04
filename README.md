# Preamble

## Prerequisites
- participants have been added as collaborators to a sample private repo that will get destroyed
	- create an account at https://github.com/ if necessary

## Policies
- facilitator doesn't share their screen, ask a different participant to share their screen for each lesson

# Introduction
- this workshop will give you a better understanding of an important part of every developer's job: code review
- you will gain enough familiarity with GitHub that you could see for yourself the conversations developers have about their code

# Lesson One: Intro to Markdown
- everyone edits a different .md file in the browser as assigned by the facilitator
	- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
- commit directly to the main branch (FOR NOW)
- notice the changes to the rendered blob (vs source blob)
- notice the latest commit and time is listed next to the file name
	- commit "SHA" stands for the Simple Hashing Algorithm that generates the checksum used to uniquely identify a commit
	- view a commit
		- split/unified changes
		- source/rich diff
- view repo's commit history, click around

## Question One: Why would anyone edit files on their own computer when they could just edit files directly in GitHub?

# Lesson Two: Merge Conflicts
- everyone edits the same .md in the browser
- see what happens when you try to commit to the main branch

## Question Two: Why does GitHub prevent us from merging when there is a conflict?

# Lesson Three: Creating Branches and Starting Pull Requests
- everyone edits a different .md file in the browser
- "create a new branch for this commit and start a pull request"
	- use a meaningful branch name
- "create pull request"
	- use a meaningful title and description
- view pull request details, click around
	- conversation
		- reviewers
	- commits
	- files changed
- go back to the repo's main page
	- branch drop-down now includes your new branches
	- what happens when you view your file while on the main branch?
	- what happens when you view your file while on your new branch?
- switch to your branch
	- edit your .md file in the browser
	- notice that you can either commit to your new branch or create a sub-branch
	- commit to your branch instead of creating a sub-branch
- go back to the repo's main page
	- notice "This branch is 2 commits ahead of main."
	- click on that, notice the existing pull request
	- click on the pull request, notice your latest changes

## Question Three: Why do we create new branches instead of committing directly to the main branch?

# Lesson Four: Peer Review
- go to "Pull requests" from the repo's navigation
- click on someone else's pull request
	- notice that it says "USER wants to merge X commits into main from BRANCH"
	- click on "Files changed"
		- add a single comment to a line, tagging someone else
- click on "Conversation" for the pull request you created
	- resolve the conversation

## Question Four: Why do we require peer review on pull requests?

# Lesson Five: Merging Without Conflicts
- go to "Pull requests" from the repo's navigation
- click on the pull request you created
	- notice that it says "USER wants to merge X commits into main from BRANCH"
	- review your changes under "Files changed"
	- review the conversation (ideally waiting for approval from your colleagues)
- click "Merge pull request"
	- leave default title and comment
	- "Confirm merge"
	- "Delete branch"
- go back to the repo's main page
	- look at branch dropdown
	- look at commit history
- go to "Pull requests" from the repo's navigation
	- toggle between "Closed" and "Open"

## Question Five: Why do we delete branches after they have been merged?

# Lesson Six: Merging With Conflicts
- two people go to the main branch and edit the same .md in the browser
	- make a changes to several different lines (change formatting, naming conventions, etc.)
- both people create a new branch for their commits and start a pull request
- open up one pull request, and we're going to merge them one at a time
- share your screen when a pull request says "This branch has conflicts that must be resolved"
	- click "Resolve conflicts"
	- actually resolve conflicts
	- "Mark as resolved" and "Commit merge"
- notice the "Files changed" in your pull request
- "Merge pull request" and delete branch

## Question Six: What can be done to prevent merge conflicts?
