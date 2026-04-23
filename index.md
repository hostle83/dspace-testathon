---
layout: page
title: DSpace Release 10.0 Testathon Page
---

# Welcome to Testathon 10.0!
DSpace Development never stops! DSpace 10.0 is almost here, and with it arrive new features, improvements, bug-fixes, changes, etc.

We ask that you take a few minutes of your time in these coming weeks to help us fully test this new release! We want to ensure we are maintaining the same level of quality that you come to expect out of a new DSpace release. We'd also love to hear your early feedback on 10.0!

**WHO**: You! Everyone is invited to take part. Whether you manage multiple instances, or are interested in trying it out, we welcome your feedback.

**WHAT**: Help beta-test DSpace 10.0 to ensure that it passes its ultimate test: that it does what users expect it to. We've added new features that could use more eyes, browsers, and mouse-clicks to make sure that things aren't missing, that they don't break, that they don't lose your data, and that they easily do what one expects them to do. So if any features have issues while your testing it.

**WHEN**: Monday, April 6 through Friday, April 24, 2026. You can keep visiting the site and post your feedback, as part of continual improvement.

**WHY**: The sooner we find and fix bugs, the higher quality the software will be when it comes time to upgrade or install DSpace 10.0.

**HOW**: Go to [https://sandbox.dspace.org/](https://sandbox.dspace.org/) and test-drive the new user interface. We're looking for feedback on the DSpace software, as well as feedback on our unreleased [DSpace 10.x](https://wiki.lyrasis.org/display/DSDOC10x/DSpace+10.x+Documentation) Documentation.

Optionally, you can also run and test DSpace 10 locally.
Download and install 10.0-rc1 (See [Installing DSpace](https://wiki.lyrasis.org/display/DSDOC10x/Installing+DSpace) or Upgrading DSpace)
Frontend/UI download: https://github.com/DSpace/dspace-angular/releases/tag/dspace-10.0-rc1
Backend/REST API download: https://github.com/DSpace/DSpace/releases/tag/dspace-10.0-rc1
Or, use Docker to quickly install DSpace 10 locally (see Try out DSpace 10)

**WHERE**: Results from the test made on https://sandbox.dspace.org/ should be recorded in the (DSpace 10.0 Test Plan) worksheet.

Questions?  Ask them on our DSpace Tech Support list (https://groups.google.com/d/forum/dspace-tech) or Slack

## Updated Documentation for 10.0
There are upgrades to the DSpace documentation for version 10.0. Volunteers are needed to review it for clarity and accuracy. Visit the DSpace 10.x Documentation page for more info.

# Test Plan and Instructions

We are testing by means of **user stories**: 

* [GENERAL TESTS](https://github.com/hostle83/dspace-testathon/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22USER%20STORY%3A%20GENERAL%22)
* [SUBMISSION WORFLOW](https://github.com/hostle83/dspace-testathon/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22USER%20STORY%3A%20SUBMISSION%20WORKFLOW%22)

# Slack
We have a dedicated #testathon channel in Slack! Use this channel freely to ask questions, post comments, or share ideas on how to improve the process. 

**Note**: Please use this channel for Testathon-related comments only. For general questions about DSpace, please use the #general channel, and for anything related to technical questions, please use #tech-support

# Co-working sessions
New to testing? Do you have questions? Want to test with others? We're offering Testathon coworking sessions at the following dates/times. Use the Zoom link listed in the table for the specific day you intend to join:

See the world clock to determine the meeting time for your location.

| Date        | Time              | Zoom Link | Host
|Monday, April 6|5:00pm-6:00pm EDT 21:00-22:00 UTC| https://umn.zoom.us/j/95455262817?pwd=Z3o5BexR7gsspIzDiP7beexkthKR4i.1 | Kent |
|Tuesday, April 7 | 9:00am - 10:00am EDT 13:00-14:00 UTC | https://lyrasis.zoom.us/my/holgerlenz | Lia, Holger |
|Wednesday, April 8	| 12:00pm - 1:00pm EDT 16:00-17:00 UTC | https://umn.zoom.us/j/95455262817?pwd=Z3o5BexR7gsspIzDiP7beexkthKR4i.1	| Kent |
|Thursday, April 9 | 3:00pm - 4:00pm EDT 19:00-20:00 UTC | https://lyrasis.zoom.us/my/holgerlenz | Lia, Holger |
|Monday, April 13 | 5:00pm - 6:00pm EDT | https://umn.zoom.us/j/95455262817?pwd=Z3o5BexR7gsspIzDiP7beexkthKR4i.1 | Kent |
|Tuesday, April 14 | 9:00am - 10:00am EDT | https://lyrasis.zoom.us/my/holgerlenz | Holger|
|Wednesday, April 15	|12:00pm - 1:00pm EDT|	https://umn.zoom.us/j/95455262817?pwd=Z3o5BexR7gsspIzDiP7beexkthKR4i.1	|Kent|
|Friday, April 17|	9:00am - 10:00am EDT|	https://lyrasis.zoom.us/my/lgeggleston	|Lia
|Monday, April 20|	5:00pm - 6:00pm EDT|	https://umn.zoom.us/j/95455262817?pwd=Z3o5BexR7gsspIzDiP7beexkthKR4i.1	|Kent|
|Tuesday, April 21|	9:00am - 10:00am EDT|	https://lyrasis.zoom.us/my/holgerlenz	|Holger
|Wednesday, April 22|	12:00pm - 1:00pm EDT|	https://umn.zoom.us/j/95455262817?pwd=Z3o5BexR7gsspIzDiP7beexkthKR4i.1	|Kent|
|Friday, April 24	|9:00am - 10:00am EDT|	https://lyrasis.zoom.us/my/lgeggleston|	Lia|


# Reporting Bugs that you find
If you find something that looks like unexpected behavior, or a definite bug, we encourage you to report it in a new bug ticket in our GitHub Issues:

Visit https://github.com/DSpace/dspace-angular/issues while logged in via GitHub
Click on "New Issue" button
Click on "Get started" in the "Bug report" section
Describe the bug you found and the steps that a developer can take to reproduce the bug. (It is VERY important that a developer can reproduce the bug, otherwise it will be more difficult for us to solve it.)
If you cannot reliably reproduce the bug, ask someone else on Slack or our Mailing Lists to see if they have seen similar behavior.  If multiple people see the same behavior, please report it!
Don't worry if you accidentally report the same bug as someone else.  In that scenario we'll just close one of the tickets & link everyone to a single ticket.

# Reporting Security issues
Even though DSpace 10 is still in beta, it cannot be excluded that institutions are already running it on publicly accessible (test) servers right now.

Please report security issues to security@dspace.org according to the DSpace Software Support Policy. This way, investigation and resolution of security issues can be fast tracked, after which they can be publicly disclosed.

[def]: https://github.com/hostle83/dspace-testathon/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22USER%20STORY%3A%20GENERAL%22