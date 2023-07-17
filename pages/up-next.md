---
title: Up Next
layout: content
image: hand-paid-cans-36464-pxh2.jpg
---

 To launch Talon notes server: `launch start`, start Talon notes.  For scripting: `talon open log`

#### Now

- `go line end/start`
- `grave`: \`, `hash`: # 

<br/>

#### Up Next
- NEA: easily jump to Support, Word dashboard
- visual studio code commands (built in), basic cursorless
  - example: command for settings
- copy paste
- edit global/code/etcetera: equivalent of edit command in Vocola 
  
#### Soon
- Add formatter that adds a space before, plus one for a sentence with a space before it
- How to capitalize an existing word?

### Outlook: Command Chunk
1) Create simple command to send an email to  propose times
- NOTE: because this is frustrating, do In small bursts

- in clients.py,  create list w one value, make sure it works: I can read it in  outlook.talon

- create list of dictionaries,  try to extract name or emails 

- in outlook.talon: (client) time:
new mail 
(clients)emails
(client) cc emails
subject: Potential Meeting Times

Clean this up

- go right, go right fifth, the word right, go line end/start, escape Backspace, go way up
- sentence hello world
- go up fifth, select up third
- If I wanted to write the number 1000, I would say one zero third, to repeat the 0 character 3 times.
- copy all, delete = backspace, clear line, clear word left
-  Generic [editing commands](https://github.com/knausj85/knausj_talon/blob/main/core/edit/edit.talon), space [practice basics](https://chaosparrot.github.io/talon_practice/)
- put in Basics:


[Vision](where-next/vision.html)

### Adding Words, Editing Words
- To add words:  You can toss AUV in additional_words.csv if you're using it often
- To edit words:
-  custom vocabulary: in common file, settings/additional-words.CSV
-  I believe that is "words_to_replace.csv" in knausj. If you're using knausj, just say "customize words to replace" and the csv file will pop up
-  [My notes](https://aschneiderman.github.io/talon-notes/pages/basics-write/writing.html) on replacing etc, plus [these notes](https://aschneiderman.github.io/talon-notes/pages/basics-write/correct-that.html)
- **Create commands** to back up add, edit words, etc 
- if I say "check out my site", do I mean site or sight? Or possibly cite?? To resolve these ambiguities, Talon includes a phones command
- i don't know if it is The Right Way, but I added mine to alternate_keys in keys.py: "do it": "enter"
- help context” This pop-up will show all the modules Talon has loaded. It will show both active and inactive, but the active ones will be marked. help active This pop-up will show only the active modules,
- help <module name>”, e.g., “help git” This view shows commands for a given module. It can be accessed either via “help context” then “help <module name>”, or directly by “help <module name>”.



### GitHub Desktop
- Any other Vocola commands?

### Windows Explorer, Windows Management
- App name
	- app: windows_explorer
	- app: windows_file_browser
- Built in commands: [talon](https://github.com/knausj85/knausj_talon/blob/main/apps/windows_explorer/windows_explorer.talon), [python](https://github.com/knausj85/knausj_talon/blob/main/apps/windows_explorer/windows_explorer.py)
- Vocola commands
- To get a list of all the commands you can use with focus/launch, from Talon's menu, choose Scripting, Console
- Type `registry.lists['user.running'] `
- running list         (see all active applications),  running hide 
-  super sun: search bar
-  say ‘snap internet explorer left” it will snap the internet explorer window to the left half of the screen. And if I say ‘snap right’ wit will snap whatever window I have selected to the right half of the screen. Knausj_talon has 25 knausj_talon snap positions that you can snap windows, and there isn’t a way to look them up short of looking at them on line 119 of file window_snap.py in the knausj talon source code. I personally use only five of them of them. “snap left” “snap right” “snap top” “snap bottom” “snap fullscreen”
-  Snap commands: [talon](https://github.com/knausj85/knausj_talon/blob/main/core/windows_and_tabs/window_management.talon), [python](https://github.com/knausj85/knausj_talon/blob/main/core/windows_and_tabs/window_snap.py)
-  The shortcut I use most commonly is ‘minimize all windows’, which I can do with the command “super drum” to press the keyboard shortcut ‘windows d’ Then I use ‘ctrl-alt-tab’ to maximize the apps I want to work with again

### Global commands
- Vocola: copy switch, save reload, any others?

### Mouse
- [Dense Mouse Grid](https://github.com/tararoys/dense-mouse-grid), [Video](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi71e-axf7_AhUYGFkFHRHcCeUQwqsBegQIDRAG&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DpaWx7bF_IH8&usg=AOvVaw0x_KpiDIbmwRWTkdw9kdN9&opi=89978449)
- [Flex mouse grid](https://github.com/brollin/flex-mouse-grid)



### Outlook: Level Up
- Store clients in ____
- Being able to pick names with a word
	- Email: email addresses, hi
	- Calendar: Title, email addresses


### Cursorless: Basics
- Explore better colors
- **Focus on learning it**: using client notes, notes
- block or <language> block for creating a new md code block
- Delete several lines -- equiv of grab lines and kill 1

### Scripting: Basics
- visual studio code: terminal commands
- Builtin visual studio code commands: save as?
- Wiki
	-  [getting started w scripting](https://talon.wiki/unofficial_talon_docs/)
	-  Using [key command](https://talon.wiki/key_action/)
	-  Official [scripting docs](https://talonvoice.com/docs/index.html#document-talon_files)
- Vocola commands 
- "copy address" in Rango copies the url. I would check how it's implemented there

### Rango
- [Documentation](https://github.com/david-tejada/rango)
- "copy address" in Rango copies the url
- with knausj you can save websites in a file and then open them with "open website name". You can open the file with customize websites

### Home Stretch
- next window n
- commands for starting outlook, GitHub; it can't be using  launch
- incorporate: [https://www.joshwcomeau.com/blog/hands-free-coding/](https://www.joshwcomeau.com/blog/hands-free-coding/)
- Check out:
	- Multidimensional [clipboard](https://github.com/FireChickenProductivity/Talon-Voice-multidimensional-clipboard) Lets you store and retrieve multiple text snippets from a Talon maintained clipboard
