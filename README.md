# Sublime Text Build Systems

Sublime Text [build systems](http://docs.sublimetext.info/en/latest/file_processing/build_systems.html) can be considered simplistic, but highly customizable. The basic idea is that each type of Build profile is powered by a `.sublime-build` file - a JSON representations of the commands, paths and configuration needed to build a project using a specific tool or set of tools.

See the unofficial Sublime Text documentation for [detailed information on Sublime Text build systems](http://docs.sublimetext.info/en/latest/reference/build_systems.html).

## Installation

Sublime populates its `Tools > Build System` menu based on the `.sublime-build` files stored in the Sublime `Packages` directory. Should one need to locate this, it can be found in `~/Library/Application Support/Sublime Text 2/Packages/User` (if using OS X) or the corresponding Packages/User directory on other platforms.

**NOTE:** Subdirectories will also be traversed, so a `Build Systems` directory may be used to organize build systems.

## Environment Considerations

Note that depending upon the environment specific configurations some binary tools may be located at different locations.

If using OS X, it may be useful to install [the FixMacPath package](https://github.com/int3h/SublimeFixMacPath/) which will allow Sublime Text to use shell configurations to set the `PATH`.
