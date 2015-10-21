# Command Line Fu

## Objectives:
- Practice with the command line.  
- Increase knowledge of what is available

Your community has shared the command line snippets that help them. Read through the [All Time Greats]( http://www.commandlinefu.com/commands/browse/sort-by-votes).  Play with them.  Be careful with `rm` and `sudo`.

## Deliverable:
Create an issue in this repository, containing 3 interesting commands that you learned about.



##CLI Snippet: reset
Functions: reset
Salvage a borked terminal
If you bork your terminal by sending binary data to STDOUT or similar, you can get your terminal back using this command rather than killing and restarting the session. Note that you often won't be able to see the characters as you type them.

##CLI Snippet: ctrl-l
Clear the terminal screen

##CLI Snippet: ctrl-x e
Rapidly invoke an editor to write a long, complex, or tricky command
Next time you are using your shell, try typing ctrl-x e (that is holding control key press x and then e). The shell will take what you've written on the command line thus far and paste it into the editor specified by $EDITOR. Then you can edit at leisure using all the powerful macros and commands of vi, emacs, nano, or whatever.
