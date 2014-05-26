---
layout: post
title:  Device Manager
date:   2014-05-26 14:55:00
categories: codeigniter
short_desc: FOSS mobile device management application running on Codeigniter 2.1.4
---

Small businesses face all sorts of problems, both big and small.  Device Manager was created in response to a common problem within small-medium sized businesses: who has the laptop with PowerPoint 2010 on it?  There are larger scale Mobile Device Management solutions provided by all the top tier technology companies, but these can be expensive and enforce requirements which may not align with your current business goals.

Enter: Device Manager (DM).

## Why DM?

DM takes a more manual approach to managing multiple devices, and as such is intended for businesses with < 50 employees.  Staff would be required to ensure they check out devices when they get it and check them back in (to a central location, likely the IT department) when they're done.  They can file tickets on their devices if something goes wrong, track who has what laptop/phone/desktop PC and even see how their support requests stack up against their fellow coworkers (a high number of WONTFIX tickets results in a lower ranking, more COMPLETED tickets increases it).

Also, it's free.

## Features in point form

* Per-device task tracking with many basic task management functions
* Check devices in or out
* Reserve devices checked out by other users
* Full device history which tracks all actions performed on a device (check in's/out's, tasks updated, applications installed, etc.)
* Easy administration of devices, users, tasks and tracked applications.

## Requirements

* PHP >= 5.3.28
* MySQL > 5.5

## Planned Features

* 1.1
	* Usergroup Management. 
	* Documentation for all classes and functions
* 1.2
	* Device Watchlist.  Users choose any number of already tracked applications from a list and are presented with a list of devices which have those applications installed.
	* More flexibility in what DM can track.  Currently there are 4 types: laptops, desktops, servers and peripherals.  The plan is to make this a dynamic list of devices or items that you've chosen.

## Disclaimer

This is project is still under development and should be treated as a beta-level product.  Please use the provided issue tracker to raise issues.

## Contribute

Contributions are welcome, just submit a pull request.  Just a friendly note, this application is used internally and is subject to our product and business goals.  Pull requests that do not align with those goals will not be accepted, even if they are technically valid contributions, but you are free to fork the project and build it into whatever you want.

<a href="https://github.com/FreeAdvertising/devicemanager"><img style="position: fixed; top: 0; right: 0; border: 0;" src="https://camo.githubusercontent.com/652c5b9acfaddf3a9c326fa6bde407b87f7be0f4/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6769746875622f726962626f6e732f666f726b6d655f72696768745f6f72616e67655f6666373630302e706e67" alt="Fork me on GitHub" data-canonical-src="https://s3.amazonaws.com/github/ribbons/forkme_right_orange_ff7600.png"></a>