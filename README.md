# Gimmick for Visual Studio Code

This extension adds support for the [Gimmick][gimmick] programming language to VS Code, 
including:

* Syntax highlighting
* REPL interaction

Besides basic syntax highlighting, the key feature is being able to interact
with a running [Gimmick][gimmick] REPL.

\!\[RuseInteraction\]\(images/vs-gimmick.gif\)


## Configuration

By default `vs-gimmick` will attempt to find a running ruse server on `localhost`
at port `4005`. This can be changed by supplying the following configuration items:

* `gimmick.ruseHostname`
* `gimmick.rusePort`


## Requirements

The only additional npm dependency should be `web-request` if building from source.


## Release Notes

This is the first prototype release for the extension. Please contact me if you
have any questions or comments!


[gimmick]: https://github.com/tbogdala/gimmick