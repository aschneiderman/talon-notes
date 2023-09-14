---
title: Up Next
layout: content
image: hand-paid-cans-36464-pxh2.jpg
---

 To launch Talon notes: `launch start`, start Talon notes.  For scripting: `talon open log`. To memorize:
- `customize additional words`, `customize words to replace` (learn about abbreviations?)(copy to writing)
- `go line end/start`
- `grave`: \`, `hash`: # 

##  Next Tasks
- out look: sent items, deleted items
- get hub: ad customize word for get hub, commands for commit to main, wich also does equivalent of push it
- client info

- add command to backup customized words,: `launch start`, `start copy words`

hud:
https://github.com/chaosparrot/talon_hud

for hud: head up show 
toolkit options


### Accuracy

https://jacobegner.blogspot.com/2023/02/talon-voice-and-cursorless-notes.html

https://whalequench.club/blog/2019/09/03/learning-to-speak-code.html

https://tararoys.github.io/Getting-Started-With-Dictation-Mode.html


what pokey and I do is to give it a new name that is easier to recognize. “van cake” -> vscode in additional_words.csv. this works with commands like “say”
  


Any word/phrase in additional_words will be highly ranked in recognition.


You can add the names to additional_words.csv so they will be recognized by the engine. There are also commands for doing that automatically, just select the word and say "copy to vocab"



For example, I created a command for Outlook, “delete mail.” Dragon nails it every time, but unless I very clearly articulate the words, Talon gets it wrong reasonably often.

you can do "talon open log" to open the talon log, then do "talon test expanding this" (with vscode focused) and see which command it recognizes


is it possible your outlook context is not properly activating? help active would let you know if it is active or not

is your speech timeout set very low and the pause between "delete" and "mail" is long enough to split it?

what does it get it wrong as? have you tried "save recordings" from the speech recognition menu to ensure the audio sounds sensible?

Enable Save recordings and share an example of talon getting it wrong

Increase Talon’s wait time. This has the disadvantage of making all commands react slower, but it can eliminate the cutoffs. Do this by adding a settings.talon file to your user directory with the following content:

settings():
    # minimum silence time (in seconds) before speech is cut off, default 0.3
    speech.timeout = 0.4
Start with the value of 0.4, just slightly higher than the default, and increase only if necessary.


google:

talon additional-words.CSV

homophones:

To resolve these ambiguities, Talon includes a phones command:

I select the last word, "sight", and say the word "phones". A menu pops up, with a numbered list containing 3 possible spellings: cite, sight, and site. The third option is the one I want, so I say "pick 3"

option shift left phones

For example, if there were a hat on the h in where, you could say "phones harp" to change it to wear.

"phones <TARGET>"
eg:

"phones air"
"phones first word air"

### Prose

- Adding words
- Adding pronounciation
- Do a bit of writing -- maybe responses to emails? -- at the end of each day?
-  Try writing primarily in cursorless -- and "dictate a whole bunch, then error correct, instead of doing error correction after every sentence. just don't dictate so much you forget what the text was supposed to be when it's wrong"

### Groups
- requests
-  time zone 
- hi
- meeting invite 
- emails 

topic links 

### NEA support tickets 
- committees
- report manager
- searching help

- status reports

- searching help from a list of topics 

- client notes (one doc)(prep for today tasks?)

- markdown -- eg, converting lines to bullets

- fix vs code so last window works 

### zoom recordings 
- extract from email?
- (first test that pwd email contains works)

### todays tasks
simplest to do daily via talon 

### Slack

writing 
add words, fix words (nea, fyi)
sassy 
How to capitalize an existing word?
convert markdown to Word

https://github.com/talonhub/community/blob/main/apps/vscode/vscode.talon

https://github.com/talonhub/community/blob/main/apps/windows_explorer/windows_explorer.talon

https://github.com/talonhub/community/blob/main/apps/outlook/outlook_win.talon

https://github.com/talonhub/community/blob/main/apps/slack/slack_win.talon

https://github.com/talonhub/community/tree/main/core/vocabulary

https://github.com/talonhub/community/blob/main/core/windows_and_tabs/window_management.talon

For how to do csv files:
https://github.com/talonhub/community/tree/main/core/app_switcher







### jira tickets 

- [Flexible Mouse Grid](https://github.com/brollin/flex-mouse-grid) -- best mouse.  video demo of dense: https://youtu.be/paWx7bF_IH8
-  dense mouse grid:  on:`dense grid`, off: `grid close`  {doesn't seem to be working}
- Rango: https://github.com/david-tejada/rango
- My notes on issues caused by [bootstrap websites](https://github.com/aschneiderman/Voice-chrome-extensions/blob/main/understanding-websites/js-manipulate-bootstrap.txt)


### Voice Health
- easier on vocal chords
- doing the exercises

### Advanced writing 
- convert Word to markdown?
- convert markdown to Word / Google docs?

### Windows management
Steal ideas from here:
- https://github.com/lunixbochs/talon_wm
- https://github.com/codecat555/talon-window-tweak







### Web Automation
- My notes on issues caused by [bootstrap websites](https://github.com/aschneiderman/Voice-chrome-extensions/blob/main/understanding-websites/js-manipulate-bootstrap.txt)





https://tararoys.github.io/small_cheatsheet.html

Assume I want to write the following: This is hello-world. What do I say?
 `sentence this is over space kebab hello world`



[talon hud](https://github.com/chaosparrot/talon_hud): can turn mic off

- figure out how to make last window work the way you would expect in would in Visual Studio Code


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
