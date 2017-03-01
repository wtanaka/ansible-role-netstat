[![Build Status](https://travis-ci.org/wtanaka/ansible-role-netstat.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-netstat)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-netstat.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-netstat)

wtanaka.netstat
===============

This ansible role installs netstat, a command-line tool that displays
network connections (both incoming and outgoing), routing tables, and
a number of network interface (network interface controller or
software-defined network interface) and network protocol statistics.
It is available on Unix-like operating systems including OS X, Linux,
Solaris, and BSD, and is available on Windows NT-based operating
systems including Windows XP, Windows Vista, Windows 7 and Windows 8.

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.netstat

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
