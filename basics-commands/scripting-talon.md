


Adding list into insert:
> some_command <user.text>: insert("command {text}\n")

- swap: key(alt-tab)

- start with sim("say function round") in the repl to see which rule is matching

I see now I added them to textnavigation.talon  eg:

```# Navigation
up <number_small>:
    edit.up()
    repeat(number_small - 1)
down <number_small>:
    edit.down()
    repeat(number_small - 1)

left <number_small>:
    edit.left()
    repeat(number_small - 1)

right <number_small>:
    edit.right()
    repeat(number_small - 1)
    ```
