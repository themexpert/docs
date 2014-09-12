---
title: Version Information 
taxonomy:
    category: docs
visible: true
---

The problems happen when we use open source (OS) software. And of course, the OS software will be upgraded to a version in every so often.

Our discussion now about two points: adopt a "stable trunk" practice and do time-based releases.



##Stable Trunk
----------

In software version control parlance, the trunk (think tree) is the working code used for releasing versions of the program. Developers can create branches (copies of the trunk's code) to work on major changes, like adding a new feature. By working in a branch, a group of developers can make all the changes they like without affecting either the main program or other developers working in other branches. When a feature is tested and ready, the branch for that feature is merged back into trunk and becomes part of the next release.

##Time-Based Release Cycle
----------

With Joomla, we don't know who might work on something or how many hours or days they might have available, let alone when they might finish it. So it is impossible to accurately predict when new features will be ready for release. On the other hand, there are great benefits to the community to have a predictable release cycle. The PLT's solution was to release on a planned time schedule.


##STS and LTS Releases
----------

With this background in mind, let's look at the specifics of the current Joomla release cycle. In that same 2009 meeting, the PLT decided on an ambitious goal – to release a new Joomla version every six months. Why such frequent releases? One important consideration is to motivate developers. Volunteers who contribute code to the project want to see their code or feature get used. If the time between releases is too long, we lose this motivating factor. Releasing more frequently also makes it easier to keep up with versions of software that Joomla relies on – things like PHP, MySQL, and TinyMCE. All of these programs are under constant development and change, and we need to be able to keep pace.

The choice is entirely yours. The only condition is this: if you go with an STS release (say 3.0 or 3.1), you need to understand that these have a short lifespan and that you are in effect committing to updating every six months until you get to the next LTS release (for example, 3.5). At that point, you can decide whether to stay on the STS path (and go for 4.0 / 4.1 / 4.5) or switch to the LTS path (and wait for version 4.5).

##Why did Joomla skip from version 1.7 to 2.5?
----------

In a meeting on July 2011, the PLT decided it would make things simpler if all of the LTS releases were X.5 releases (1.5, 2.5, 3.5, and so on). To get on that plan, we could either (a) call the January 2012 release 1.8 as planned and start the X.5 numbering with version 2; or (b) we could skip from 1.7 to 2.5 and have 2.5 as the next LTS release. We decided to put this to a vote in the community and the community chose to do (b). So the January 2012 release was called 2.5 and is the current LTS release.