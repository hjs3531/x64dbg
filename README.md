# x64dbg

[![BountySource](https://www.bountysource.com/badge/team?team_id=18188&style=raised)](https://www.bountysource.com/teams/x64dbg?utm_source=x64dbg&utm_medium=shield&utm_campaign=raised) [![Join the chat at Gitter](https://badges.gitter.im/x64dbg/x64dbg.svg)](https://gitter.im/x64dbg/x64dbg?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Jenkins](http://jenkins.x64dbg.com/job/vs13/badge/icon)](http://jenkins.x64dbg.com) [![Stories in Ready](https://badge.waffle.io/x64dbg/x64dbg.png?label=ready&title=Ready)](http://waffle.io/x64dbg/x64dbg)



## Note

Please run `install.bat` before you start committing code, this ensures your code is auto-formatted to the *x64dbg* [standards](https://github.com/x64dbg/x64dbg/wiki/Coding-Guidelines).

## Compiling

For a complete guide on compiling *x64dbg* read [this](https://github.com/x64dbg/x64dbg/wiki/Compiling the whole project).

## Downloads

Releases of *x64dbg* can be found [here](http://releases.x64dbg.com).

Jenkins build server can be found [here](http://jenkins.x64dbg.com).

## Overview

*x64dbg* is an open-source x32/x64 debugger for Windows.

## Features

- Open-source
- Intuitive and familiar, yet new user interface
- C-like expression parser
- Full-featured debugging of DLL and EXE files (TitanEngine)
- IDA-like sidebar with jump arrows
- IDA-like instruction token highlighter (highlight registers, etc.)
- Memory map
- Symbol view
- Thread view
- Source code view
- Content-sensitive register view
- Fully customizable color scheme
- Dynamically recognize modules and strings
- Import reconstructor integrated (Scylla)
- Fast disassembler (Capstone)
- User database (JSON) for comments, labels, bookmarks, etc.
- Plugin support with growing API
- Extendable, debuggable scripting language for automation
- Multi-datatype memory dump
- Basic debug symbol (PDB) support
- Dynamic stack view
- Built-in assembler (XEDParse)
- Executable patching
- Yara Pattern Matching
- Decompiler (Snowman)
- Analysis

## License

*x64dbg* is licensed under GPLv3, which means you can freely distribute and/or modify the source of *x64dbg*, as long as you share your changes with us. The only exception is that plugins you write do not have to comply with the GPLv3 license. They do not have to be open-source and they can be commercial and/or private. The only exception to this is when your plugin uses code copied from *x64dbg*. In that case you would still have to share the changes to *x64dbg* with us.

## Credits

- Debugger core by [TitanEngine Community Edition](https://bitbucket.org/mrexodia/titanengine-update)
- Disassembly powered by [Capstone](http://capstone-engine.org)
- Assembly powered by [XEDParse](https://bitbucket.org/mrexodia/xedparse)
- Import reconstruction powered by [Scylla](https://github.com/NtQuery/Scylla)
- JSON powered by [Jansson](http://www.digip.org/jansson)
- Database compression powered by [lz4](https://bitbucket.org/mrexodia/lz4)
- Bug icon by [VisualPharm](http://www.visualpharm.com)
- Interface icons by [Fugue](http://p.yusukekamiyamane.com)
- Website by [tr4ceflow](http://tr4ceflow.com)

## Special Thanks (in no particular order)

- [EXETools community](http://forum.exetools.com)
- [Tuts4You community](http://forum.tuts4you.com)
- acidflash
- cyberbob
- Teddy Rogers
- TEAM DVT
- DMichael
- Artic
- ahmadmansoor

## Developers (in order of joining)

- [Mr. eXoDia](http://mrexodia.cf)
- Sigma
- [tr4ceflow](http://blog.tr4ceflow.com)
- [Dreg](http://www.fr33project.org)
- [Nukem](https://github.com/Nukem9)
- [Herz3h](https://github.com/Herz3h)
