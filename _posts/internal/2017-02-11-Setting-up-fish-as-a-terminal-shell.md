---
title: Setting up fish as a terminal shell
layout: gdoc
author: superkideric
permalink: /internal/fish-setup/
source-id: 1L7ACxiYN9MkjqLQLTXi-tZjoIodmHrTWZVBq9AiTCqI
published: true
---
Fish is "Finally, a command line shell for the 90s". Here is how I set it up as my default terminal.

This worked on Ubuntu 16.04 with ROS kinetic

# Installing fish

	sudo apt-add-repository ppa:fish-shell/release-2

	sudo apt-get update

	sudo apt-get install fish

# Making ros work inside fish

The magical parts of this are taken from [this repo](https://github.com/aclough/dotfiles).

	cd ~/catkin_ws/devel

	wget https://raw.githubusercontent.com/aclough/dotfiles/master/rosfish

	nano rosfish

Comment out the second-to-last line by adding a `#`.

	nano config.fish

Paste the following two lines into your fish config file:

	set ROS_WORKSPACE ~/catkin_ws

	. ~/catkin_ws/devel/rosfish

# Setting fish as your default Terminator shell

I use Terminator as my terminal, instructions may be different for you.

1. Right click any open Terminator window and select Preferences.

2. Under Profiles -> Command, check "Custom command"

3. Set the custom command to be `bash -ic /usr/bin/fish`. This tells bash to run your bashrc and then call fish inside itself, such that ROS things can work.

