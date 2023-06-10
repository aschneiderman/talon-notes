---
title: cursorless
layout: content
# image: hand-paid-cans-36464-pxh2.jpg
---

cursorless is Talon's killer app: a stunningly good editing package via VS Code.  

Getting Started:
- [Install](https://www.cursorless.org/docs/user/installation/) cursorless
- Read the official [documentation](https://www.cursorless.org/docs/) and the [GitHub repo](https://github.com/cursorless-dev/cursorless)
- Watch [video tutorials](https://www.youtube.com/watch?v=5mAzHGM2M0k&list=PLXv2sppxeoQZz49evjy4T0QJRIgc_JPqs)
- Say `cursorless cheatsheet` for a list of commands, options, etc
- Learn by practicing cursorless [katas](https://github.com/Will-Sommers/cursorless-katas)

And with the draft commands, you can essentially turn cursorless into your DragonPad -- your test editor for Slack, email, etc.
```

draft (this | dis):
    user.draft_editor_open()
draft (all | file):
    edit.select_all()
    user.draft_editor_open()
draft line:
    edit.select_line()
    user.draft_editor_open()
draft top:
    edit.extend_file_start()
    user.draft_editor_open()
draft bottom:
    edit.extend_file_end()
    user.draft_editor_open()

draft submit:
    user.draft_editor_paste_last()
```
    
- [Short video](https://www.youtube.com/watch?v=U6Q9qjSIVQg) and [meetup](https://www.youtube.com/watch?v=w-LxcO4Er0c) of drafts in action


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

