This Sublime package provides:

* integration with [ament](https://github.com/ament/ament_tools) as a Sublime build system

* highlighting of the build output and linking to referenced filenames with line numbers


# How to install the package?

Clone the repository into your Sublime folder `Packages/User` and name the checked out folder `ament` (instead of `sublime-ament`).


# How to use the ament build system?

Create a Sublime *project* pointing to the source space of the workspace.
Select `ament_build` under *Tools -> Build System*.

Beside the default build configuration (triggered by Ctrl+B | Cmd+B) you can select different configuration form the command palette: all starting with `Build: ament build:`.

The build output will be highlighted and you can click on CMake / compiler error messages containing filenames with linenumbers to open them in a tab.
