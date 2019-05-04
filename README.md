# Development workspace for the libra project

## Setup

In order to get started with **libra** project development, you need to follow the steps below.

### Install leaf

**leaf** is a development workspace management tool.
If you don't have it installed already, what you just need to do is to run these commands:

* `wget -O /tmp/leaf_latest.deb https://downloads.sierrawireless.com/tools/leaf/leaf_latest.deb`
* `sudo apt install /tmp/leaf_latest.deb`

### Clone this repository

Eventually create and go into a folder that will contain your **librawks** folder, then run:

* `git clone git@github.com:libra-net/librawks.git`

(Assuming that you have your private key configured for Github access)

### Synchronize the workspace

The last step is to select the development profile you want to work with; this will trigger
the workspace synchronization (including requirements install if not done already).

If you don't know which profile to select, just run:

* `cd librawks`
* `leaf select default`

## Visual Studio Code

This workspace is designed to be used with **Visual Studio Code** (https://code.visualstudio.com/)

Recommended extensions and settings will be automatically applied as soon as you open this folder in the IDE.
