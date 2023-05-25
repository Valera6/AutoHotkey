# Setup
download AutoHotkey, create .ahk file, add shortcut to shell:startup

Copy-paste wanted blocks in there
## Recommended Headers:
#SingleInstance force
#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
#Persistent
#InstallKeybdHook
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.
