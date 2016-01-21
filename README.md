## What is Hammerspoon?

This is a tool for powerful automation of OS X. At its core, Hammerspoon is just a bridge between the operating system and a Lua scripting engine.

What gives Hammerspoon its power is a set of extensions that expose specific pieces of system functionality, to the user. With these, you can write Lua scripts to control many aspects of your OS X environment.

## Why fork?

A previous update to Hammerspoon broke my hinting workflow, as the hinting
interface by default now disables other hotkeys. This fork fixes that bug
by adding a command to dismiss all current pop-ups when hinting is exited.
