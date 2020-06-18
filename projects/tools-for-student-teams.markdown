# Purchase Management for Student Teams

## The Problem
As a junior, I started UC Irvine's CanSat team. The CanSat Competition allows up to 10 students per team, and we were short-staffed trying to meet both university requirements and competition goals. We relied on software to free students of administrative tasks.


### Purchase management is difficult for humans
* It was difficult to train new students to use the School of Engineering order forms.
* Each order had to be logged in a spreadsheet.
* When purchase orders got edited or returned due to errors, the log had to be updated.
* Errors often caused procurement delays. Students forgot to update the log when they modified their purchase orders.


### We couldn't find existing software to fit our team.
* To ensure everyone can access the software, it should be web-based.
* Most students don't have access to web hosting or the know-how to make it work.
* Students are reluctant to pay for expensive commercial-grade software they don't really need.


## The Solution
We developed a lightweight [purchase management system](https://github.com/elsoroka/MAE-Purchase-Automation) for student teams.


The system is implemented using only Google Scripts, Spreadsheets, and Forms. Anyone can access these tools for free.

### How it works:
* The student fills out a Google Form to make a purchase. The form provides error-checking and instructions for each field.
* The departmental order form is automatically generated and emailed to the team purchase manager for approval.
* The order is automatically posted in Slack.
* Finally, the order is automatically logged. Manual intervention is only required if the order is modified or canceled.
* The system can be configured as a plugin associated with a Google spreadsheet.

## Results
* Procurement delays due to incorrectly-filled-out forms were eliminated.
* Project spending was automatically and accurately tracked.
* Another senior design team adopted our system!