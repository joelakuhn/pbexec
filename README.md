# pbexec

This utility dumps the contents of the Mac OS clipboard into a temp file and passes that file as an argument to bash or a specified executable. This simple tool has become a pretty integral part of my workflow since I produce a lot of ephemeral scripts that I don't always feel like saving to a file and executing. I realize this is not a great contribution to the world of open source software, but I'm putting it here so don't have to keep rewriting it on every computer I use.

# Uses

Run the clipboard as a bash script:

```
pbexec
```

Run the clipboard as a nodes script:
```
pbexec node
```

The world's your oyster in terms of what you can run your clipboard as, as long as the world you're considering is interpretters that take a script file as an argument like node, python, php, crystal, ruby, lua, elixir, whatever.
