# Meteor Bash Completion

[Bash shell completions](http://www.tldp.org/LDP/abs/html/tabexpansion.html)
for the [Meteor](https://www.meteor.com) command-line utility.

Installing this script makes it possible to use the Tab key to fill in possible
completions.

For example: `meteor ad[Tab]` completes to `meteor add`.

# Installation

    sudo wget https://gitlab.com/meonkeys/meteor-bash-completion/raw/master/meteor -O /etc/bash_completion.d/meteor

# Known bugs

Amazon Linux is missing the `_parse_usage` and `__parse_options` helpers.

# Copyright, License

Copyright (C)2014 Adam Monsen.

License: AGPL v3. See LICENSE for details.
