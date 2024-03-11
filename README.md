# worklog.sh

*Log your work, write better reviews*

It's hard to remember what you work on all quarter. Write it down so you don't have to!

# Setup

1. Install `worklog` in your path
2. Set up a [dedicated hotkey window](https://iterm2.com/documentation-hotkey.html) in iTerm2
3. Edit the hotkey window profile
    * Settings -> Profiles -> Hotkey Window
    * Set the `Command` to "Custom Shell" with the value of the path to `worklog`

If you did everything right, you can run your iTerm2 hotkey to pull up an iTerm2 window running `worklog`, prompting you for a new worklog entry.

# Usage:

```
Usage:
    worklog [edit|new|show] [date]

Examples:
    Show today's worklog:
        worklog show

    Show specific worklog:
        worklog show 20240131

    Edit today's worklog in your default editor:
        worklog edit

    Edit specific worklog:
        worklog edit 20240131

    New entry prompt:
        worklog new

    New entry in-line:
        worklog this is an entry

    Read new entry from stdin (prepends timestamp):
        echo "this is an entry" | worklog
```
