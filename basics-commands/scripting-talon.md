# Scripting Talon

- error log

-  zap: key(backspace), killed: key(delete), zoom: pageup/pagedown

- Adding list into insert: some_command <user.text>: insert("command {text}\n")
- curl Tab 3: key("tab:3")
- go tab <number>: key(number)
- select all: key(ctrl-a)
-  sleep(100ms)
- (pace |  paste) all
-  press <user.key>:  key(keys)  # NOTE: is it key or keys?
- <User.letter>
- NOTE: knausj tends not to use a key directly, since different platforms use different keys; if you are doing it for yourself you can just use whatever works for you



Sample keys:
- swap: key(alt-tab)


one way, from  textnavigation.talon  
```
up <number_small>:
    edit.up()
    repeat(number_small - 1)
```

 ## Context

- app: Outlook
-  other Common apps: Slack
- App names:  I think registry.decls.apps, but please do not use that in business logic in code, the registry is only available for debugging purposes
- App names:  I think registry.decls.apps, but please do not use that in business logic in code, the registry is only available for debugging purposes
- title: /gmail/


## Troubleshooting
- start with sim("say function round") in the repl to see which rule is matching
