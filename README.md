Background Terminal Notifier
============================

![icon](icon.png)

Ever start a long-running process, like a build or something, and then switch to another window, to, ummm read some documentation, and then forget about it for a long time?

This will trigger a notification if a process that you've left running in a vscode terminal completes.

If you don't want it to run in a certain workspace, you can disable the extension in that workspace.

If there's popular demand, I'd consider adding some configuration like "don't notify for commands matching this regex" or something.


## To build/install:

```
git clone https://github.com/gerardqueralt-wke/vscode-background-terminal-notifier
git checkout windows-compatible
npm i vscode@latest
npm ci
npm i -g vsce
vsce package
code --install-extension .\background-terminal-notifier-1.0.5.vsix
reload
```

More info: [https://github.com/jaredly/vscode-background-terminal-notifier/pull/9](https://github.com/jaredly/vscode-background-terminal-notifier/pull/9)
