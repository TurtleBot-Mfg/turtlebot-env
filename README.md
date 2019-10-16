# turtlebot-env
[![Build Status](https://travis-ci.org/TurtleBot-Mfg/turtlebot-env.svg?branch=master)](https://travis-ci.org/TurtleBot-Mfg/turtlebot-env)

[This package](https://github.com/TurtleBot-Mfg/turtlebot-env) configures the
Ubuntu environment for operation as a TurtleBot.

## Primary Features
- Adds `source /opt/ros/kinetic/setup.bash` to /etc/skel/.config/bashrc.d/50_ros_kinetic
- Change power settings to prevent the laptop from entering suspend/hibernate when lid is closed.
- Pulls in frequently used dependencies

## PPA
[Stable](https://code.launchpad.net/~hxr-io/+archive/ubuntu/turtlebot)·
`sudo add-apt-repository ppa:hxr-io/turtlebot`

[Testing](https://code.launchpad.net/~hxr-io/+archive/ubuntu/turtlebot-testing)·
`sudo add-apt-repository ppa:hxr-io/turtlebot-testing`
