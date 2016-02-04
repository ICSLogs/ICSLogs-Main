ICSLogs Library
===
A repository for relevant details related to log aggregation from multiple application environments related to Industrial Control Systems.

## Motivation

One of the most critical aspects of operating any complex system in a reliable and secure manner is to maintain constant awareness of the activities within the system.  In traditional IT systems this awareness can take many forms; application logs, event logs, performance counters, SNMP traps, etc.  Making this task even easier is the fact that many of the major monitoring applications have out of the box awareness for most of the typical environments present in typical IT systems.

While most ICS application servers and client software runs on Windows, the out of the box knowledge of log locations and formats is sorely lacking.  There have been efforts in the past to remedy this gap in knowledge. One of these was [Project Portaledge](http://www.digitalbond.com/tools/portaledge/) from Digital Bond.  Unfortunately as this project was primarily owned by a single organization there has been no substantial work since 2011.  Another concern is that the aggregation point, OSI PI, is an expensive and complex entry point for many asset owners.  While many organizations might own a license for OSI PI there are many more that do not.  It is our intent with this effort to borrow from any previous work, such as Portaledge, expand on that work, and most importantly create a vibrant community of contributors to maintain the project.

##Theme - It's  A Start
The overarching theme for this project will be "It's a Start".  While some outside the community of contributors may discount the direction and/or ultimate value the simple fact remains that any movement towards better log and event aggregation for Industrial Control Systems will have real tangible value.  An ideal end point would be log aggregation from heterogeneous platforms with sophisticated correlations and analysis.  However, the simple act of cataloging all available log files for a given application and possibly collecting these logs in near real time might might make a huge difference should an unwelcome event occur some time in the future.


## Organization
A unique repository will be created for each unique application.  For situations where there might be two major applications from a single vendor, Emerson DeltaV and Ovation for example, a unique repository should be created for each.

##Steps
To allow for a common understanding and sequence for building the tool set for each application we propose a common series of steps and organization for each repository.


1. Create an Issue in this repository to indicate you would like to create a new repository for a particular application.  If the project owners agree they will create a new repository and for the application and then notify the issue owner that the repo has been created along with closing the issue.
2. All repositories will utilize a standard initial structure to promote a common organization.
3.  Once the repository is created you can fork, modify, and issue pull requests to update the repository under this organization.
4.  If it appears a particular user has taken "ownership" of a particular repository we will be more than happy to assign contributor status.

##Chat Room

[![Join the chat at https://gitter.im/ICSLogs/ICSLogs-Main](https://badges.gitter.im/ICSLogs/ICSLogs-Main.svg)](https://gitter.im/ICSLogs/ICSLogs-Main?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## TODO List
Check out the [Issues](/../../issues) List

##Contributing
Check out the [Contributing](/CONTRIBUTING.MD) file

## Contributors
* [Andy Robinson](mailto:andy@phase2automation.com), Principal of [Phase 2 Automation](http://phase2automation.com).
* See list of [Contributors](/../../graphs/contributors) on the repo for others

## License

APACHE License. See the [LICENSE file](/LICENSE) for details.


