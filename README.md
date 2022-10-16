# GameMaker-string-match (better version in development)

A string format checker for GMS2

It works similarly to RegEx but it's nicer to look at(?)

# Syntax
string_match(string, match, show_error)

The match function has 3 options - allowed/not allowed characters, string length limits and character position checks
```
<|...|> - Allowed characters
<!|...|> - Not allowed characters

L(min-max) - Length limit

:(pos==<|...|>) - a char at this position must be equal to ...
:(pos!=<|...|>) - a char at this position must not be equal to ...
```
And then there is a string splitter which basically splits one string into smaller ones
```
$...$
```

### cheat sheet from gmlscripts.com
![img](https://i.imgur.com/txFF8nc.png)
