# Miscellaneous

### Random Color Generator
```
function getRandomColor() {
  let letters = '0123456789ABCDEF'
  let color = '#'
  for (let i = 0; i < 6; i++) {
    color += letters[Math.floor(Math.random() * 16)]
  }
  return color;
}
```

### Updating VS Code in Ubuntu
```
sudo dpkg -r code
sudo dpkg -i code_downloaded_package.deb
```

### Reading Mails in Mac Terminal

Open Mailbox
```
mail
```

To view the first mail
```
t
```

To select the **n**th mail
```
n (integer)
```

To view the next part of the mail
```
spacebar
```

To abort viewing the message
```
q
```

To view the next message in the queue
```
n
```

### VS Code Configuration
```
{
    "window.zoomLevel": 0.25,
    "workbench.startupEditor": "newUntitledFile",
    "git.autofetch": true,
    "workbench.colorTheme": "Cobalt2",
    "editor.fontFamily": "Operator Mono Book, Menlo, Monaco, 'Courier New', monospace",
    "editor.fontSize": 16,
    "editor.lineHeight": 24,
    "editor.letterSpacing": 0.5,
    "editor.tabSize": 2,
    "editor.detectIndentation": true,
    "git.enableSmartCommit": true,
    "terminal.integrated.fontFamily": "Operator Mono Book, monospace",
    "terminal.integrated.enableBold": false,
    "terminal.integrated.fontSize": 16
}
```