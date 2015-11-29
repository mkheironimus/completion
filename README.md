# completion

A place to store my own programmable completions.

## kitchen

Auto-complete commands and instance names for [Test
Kitchen](http://kitchen.ci). "kitchen list" sometimes takes a little time to
run, so its results are cached in a variable and refreshed if you're in a
different directory or if the YAML file modification times have changed.

It's (slightly) tested on Linux and OS X. It should be easy enough to make it
work elsewhere by updating the case statement where the stat command is
defined.

This is not implemented for zsh because a completion already exists in the
[zsh-completions](https://github.com/zsh-users/zsh-completions) project. Too
bad I wrote most of my own before I noticed that, but it was a learning
experience so that's OK. Now we know! And knowing is half the battle!
