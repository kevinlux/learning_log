<hr>

### Use international keyboard for French (Linux, Gnome)

Add international keyboard: In keyboard settings add input source. Click English(US) then select "English(US, Intl., with dead keys)"

Switch between input sources: `Super+Space`

| Character          | Key     |
|--------------------|---------|
| «                  | AltGr+[ |
| »                  | AltGr+] |
| ç                  | AltGr+, |
| accent aigu        | 'e      |
| accent grave       | `e      |
| accent circonflexe | ^o      |
| tréma              | "e      |



<hr>

### Create a numbered list in Vim

Say you want a bullet list with 12 items:

1. ` 12i0<enter><esc>` to get:

```
0
0
0
0
0
0
0
0
0
0
0
0

```

2. Select every line in the list and `g<Ctrl-a>` to get:

```
1
2
3
4
5
6
7
8
9
10
11
12
```

<hr>

### Spellchecking in Vim

Enable `:set spell`

Disable `:set nospell`

Set language to French `:set spelllang=fr`

Set language to British English `:set spelllang=en_us`

Set language to US English `:set spelllang=en_gb`

Next misspelled word `]s`

Previous misspelled word `[s`

Show alternatives `z=`

Good word (add to dictionary) `zg`

Bad word (remove from dictionary) `zb`


