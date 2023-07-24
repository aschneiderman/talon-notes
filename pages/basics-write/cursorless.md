---
title: cursorless
layout: content
# image: hand-paid-cans-36464-pxh2.jpg
---

cursorless is Talon's killer app: a stunningly good editing package via VS Code.  

Up Next:  draft this, all, file, line, top, bottom;  submit

### Selecting
- 

### Actions
- chuck: delete




### Getting Started:
[Install](https://www.cursorless.org/docs/user/installation/) cursorless, then read the  [documentation](https://www.cursorless.org/docs/), watch  [official](https://www.youtube.com/watch?v=5mAzHGM2M0k&list=PLXv2sppxeoQZz49evjy4T0QJRIgc_JPqs) and unofficial videos,  [practice]](https://github.com/Will-Sommers/cursorless-katas). `cursorless cheatsheet`  for more




And with the draft commands, you can essentially turn cursorless into your DragonPad -- your test editor for Slack, email, etc.


{taking between 2 targets}


    
- [Short video](https://www.youtube.com/watch?v=U6Q9qjSIVQg) and [meetup](https://www.youtube.com/watch?v=w-LxcO4Er0c) of drafts in action

change <TARGET>" eg: change blue air Deletes the token containing letter 'a' with a blue hat then places your cursor where the token had been

From docs, on rows:

The word "row" followed by a number can be used to refer to a line by its line number. Note that the line numbers are modulo 100, meaning that you only say the last two digits of the line number. Also note that the line must be visible within the viewport.

"chuck row twenty four"
"post row eighty nine"
"pour row eleven"
"up <number>" / "down <number>"​

The word "up" or "down" followed by a number can be used to refer to the line that is <number> lines above or below the cursor. The line may be outside of the viewport. In the case of multiple selections, this mark only refers to the line relative to the primary selection. You can turn on relative line numbers in the VSCode settings to make these marks easier to use.

"copy up one"

The word "line" can be used to expand a target to refer to entire lines rather than individual tokens:

eg: take line [blue] air Selects the line including the token containing letter 'a' with a blue hat.

"block"​

The "block" modifier expands to above and below the target to select lines until an empty line is reached.

"take block"
"take block <TARGET>"

eginning or end of the line, respectively.

"take head": select from the cursor the start of the line
"take tail": select from the cursor to the end of the line
"take head air": selects the mark through to start of the line
"take tail air": selects the mark through to the end of the line


The "phones" command can be used to cycle through homophones for a given target. For example, if there were a hat on the h in where, you could say "phones harp" to change it to wear.

"phones <TARGET>"
eg:

# "phones air"

Other stuff
- `please` word: search the command pallet for that word ￼
 - [https://jacobegner.blogspot.com/2023/02/talon-voice-and-cursorless-notes.html](https://jacobegner.blogspot.com/2023/02/talon-voice-and-cursorless-notes.html)
 - Re deleting parens, it’s “chuck bounds”, and there’s no doc for it because it’s just a combination of an action with a scope type
- to replace slashes w backslashes: use take blue/whatever slash to take the first one, cursor more tenth to select the next ten and then say backslash

Visual Studio Code tricks
- To run any vscode command, use user.vscode("some vs code cmd from cmd pallet")
- vscode Talon cmds: https://github.com/knausj85/knausj_talon/blob/mode_indicator/apps/vscode/vscode.talon

Tips
- At the beginning, if you are having trouble grabbing the right words, take a closer look at the colors. For example, I was very frustrated until I realized that I kept thinking some dots were green when in fact they were blue. As soon as I realized I was doing that, the problem went away.

To toggle the dots, add a command: confetti off: user.vscode("cursorless.toggleDecorations")

pre every line block


cursorless snippets: https://github.com/pokey/dotfiles/tree/develop/cursorless-snippets

