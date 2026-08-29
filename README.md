```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
███████╗██╗  ██╗███████╗██╗     ██╗
██╔════╝██║  ██║██╔════╝██║     ██║
███████╗███████║█████╗  ██║     ██║
╚════██║██╔══██║██╔══╝  ██║     ██║
███████║██║  ██║███████╗███████╗███████╗
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝
```

# Awesome Shell with stars

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu).

* [Shells](#shells)
* [Command-Line Productivity](#command-line-productivity)
  * [Directory Navigation](#directory-navigation)
* [Customization](#customization)
* [For Developers](#for-developers)
* [System Utilities](#system-utilities)
* [Downloading and Serving](#downloading-and-serving)
* [Multimedia and File Formats](#multimedia-and-file-formats)
* [Applications](#applications)
* [Games](#games)
* [Shell Package Management](#shell-package-management)
* [Shell Script Development](#shell-script-development)
* [Guides](#guides)
* [**Awesome Zsh**][awesome-zsh]  [![Awesome][awesome-badge]][awesome-zsh]
* [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
* [**Awesome Bash**][awesome-bash] [![Awesome][awesome-badge]][awesome-bash]
* [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

* [nushell](https://github.com/nushell/nushell) ⭐ 40,360 | 🐛 1,433 | 🌐 Rust | 📅 2026-08-28 - A modern shell written in Rust
* [murex](https://github.com/lmorg/murex) ⭐ 1,910 | 🐛 85 | 🌐 Go | 📅 2026-08-26 - A smarter shell and scripting environment with advanced features designed for usability, safety and productivity (eg smarter DevOps tooling)
* [ion](https://github.com/redox-os/ion) ⭐ 1,656 | 🐛 60 | 🌐 Rust | 📅 2026-05-02 - A modern system shell that features a simple, yet powerful, syntax. It is written entirely in Rust.
* [ngs](https://github.com/ngs-lang/ngs) ⭐ 1,521 | 🐛 303 | 🌐 C | 📅 2026-08-28 - Fully featured scripting language created specifically for Ops. REPL is being developed.
* [ksh93](https://github.com/att/ast) ⚠️ Archived - Korn Shell
* [yash](https://github.com/magicant/yash) ⭐ 561 | 🐛 44 | 🌐 Shell | 📅 2026-08-22 - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
* [oksh](https://github.com/ibara/oksh) ⭐ 454 | 🐛 17 | 🌐 C | 📅 2026-06-10 - Portable OpenBSD ksh
* [es](https://wryun.github.io/es-shell/) - The extensible shell, based on Plan 9's [rc](https://github.com/rakitzis/rc) ⭐ 328 | 🐛 10 | 🌐 C | 📅 2026-04-24 shell
* [mksh](https://github.com/MirBSD/mksh) ⭐ 240 | 🐛 0 | 🌐 C | 📅 2026-02-19 - MirBSD Korn Shell
* [shell++](https://github.com/alexst07/shell-plus-plus) ⭐ 175 | 🐛 5 | 🌐 C++ | 📅 2025-11-21 - Friendly and modern functional and object oriented shell script language
* [shenv](https://github.com/shenv/shenv) ⭐ 49 | 🐛 11 | 🌐 Shell | 📅 2026-08-25 - Simple shell version management
* [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* [elvish](https://elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
* [fish](https://fishshell.com) - Smart and user-friendly command line shell
* [osh](https://www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
* [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
* [powershell](https://docs.microsoft.com/en-us/powershell/scripting/overview) a cross-platform task automation and configuration management framework, consisting of a command-line shell and scripting language
* [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing
* [xonsh](https://xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
* [zsh](https://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [fzf](https://github.com/junegunn/fzf) ⭐ 82,702 | 🐛 327 | 🌐 Go | 📅 2026-08-26 - A command-line fuzzy finder
* [rg](https://github.com/BurntSushi/ripgrep) ⭐ 67,677 | 🐛 183 | 🌐 Rust | 📅 2026-08-04 - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
* [fd](https://github.com/sharkdp/fd) ⭐ 44,236 | 🐛 196 | 🌐 Rust | 📅 2026-08-28 - A simple, fast and user-friendly alternative to find.
* [ag](https://github.com/ggreer/the_silver_searcher) ⭐ 27,109 | 🐛 564 | 🌐 C | 📅 2024-06-16 - Super fast string search through a directory hierarchy
* [nnn](https://github.com/jarun/nnn) ⭐ 21,842 | 🐛 4 | 🌐 C | 📅 2026-08-29 - File browser and disk usage analyzer with excellent desktop integration
* [browsh](https://github.com/browsh-org/browsh) ⭐ 19,010 | 🐛 241 | 🌐 JavaScript | 📅 2025-07-11 - The modern text-based browser
* [navi](https://github.com/denisidoro/navi) ⭐ 17,492 | 🐛 113 | 🌐 Rust | 📅 2026-07-28 - An interactive cheatsheet tool for the command-line
* [direnv](https://github.com/direnv/direnv) ⭐ 15,399 | 🐛 463 | 🌐 Go | 📅 2026-03-31 - An environment switcher for the shell, compare with autoenv
* [mackup](https://github.com/lra/mackup/) ⭐ 15,314 | 🐛 294 | 🌐 Python | 📅 2026-06-15 - Keep your application settings in sync (OS X/Linux)
* [broot](https://github.com/Canop/broot) ⭐ 12,921 | 🐛 231 | 🌐 Rust | 📅 2026-08-28 - A better way to navigate directories
* [lf](https://github.com/gokcehan/lf) ⭐ 9,481 | 🐛 81 | 🌐 Go | 📅 2026-08-25 - Terminal file manager written in Go, inspired by ranger
* [mcfly](https://github.com/cantino/mcfly) ⭐ 7,782 | 🐛 136 | 🌐 Rust | 📅 2026-08-26 - Fly through your shell history. Great Scot!
* [Buku](https://github.com/jarun/Buku) ⭐ 7,186 | 🐛 6 | 🌐 Python | 📅 2026-08-16 - Powerful command-line bookmark manager
* [googler](https://github.com/jarun/googler) ⚠️ Archived - Google Search, Google Site Search, Google News from the terminal
* [spark](https://github.com/holman/spark) ⭐ 6,067 | 🐛 17 | 🌐 Shell | 📅 2022-05-07 - ▁▂▃▅▂▇ in your shell
* [autoenv](https://github.com/hyperupcall/autoenv) ⭐ 6,047 | 🐛 14 | 🌐 Shell | 📅 2025-11-20 - Directory-based environments.
* [fasd](https://github.com/clvv/fasd) ⚠️ Archived - Command-line productivity booster, offers quick access to files and directories
* [how2](https://github.com/santinic/how2) ⭐ 5,772 | 🐛 6 | 🌐 JavaScript | 📅 2023-03-15 - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language.
* [pathpicker](https://github.com/facebook/PathPicker) ⭐ 5,224 | 🐛 26 | 🌐 Python | 📅 2024-09-05 - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
* [fselect](https://github.com/jhspetersson/fselect) ⭐ 4,458 | 🐛 6 | 🌐 Rust | 📅 2026-08-16 - Find files with SQL-like queries.
* [hstr](https://github.com/dvorka/hstr) ⭐ 4,454 | 🐛 185 | 🌐 C | 📅 2026-08-28 - Bash History Suggest Box
* [ddgr](https://github.com/jarun/ddgr) ⭐ 3,537 | 🐛 1 | 🌐 Python | 📅 2026-08-16 - DuckDuckGo from the terminal
* [percol](https://github.com/mooz/percol) ⭐ 3,326 | 🐛 51 | 🌐 Python | 📅 2023-12-30 - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
* [dnote](https://github.com/dnote/dnote) ⭐ 3,072 | 🐛 40 | 🌐 Go | 📅 2026-07-25 - A simple command line notebook with multi-device sync and web interface
* [desk](https://github.com/jamesob/desk) ⭐ 2,576 | 🐛 19 | 🌐 Shell | 📅 2022-07-07 - A lightweight workspace manager for the shell
* [marker](https://github.com/pindexis/marker) ⭐ 2,092 | 🐛 49 | 🌐 Python | 📅 2024-04-06 - Bookmark your shell commands
* [k](https://github.com/supercrabtree/k) ⭐ 1,804 | 🐛 38 | 🌐 Shell | 📅 2023-02-04 - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
* [boilr](https://github.com/tmrts/boilr) ⭐ 1,763 | 🐛 44 | 🌐 Go | 📅 2023-03-07 - A blazingly fast CLI tool for creating projects from boilerplate templates.
* [borg](https://github.com/ok-borg/borg) ⚠️ Archived - A terminal based search engine for bash commands
* [arttime](https://github.com/reportaman/arttime) ⭐ 1,380 | 🐛 6 | 🌐 Shell | 📅 2026-08-18 - Beauty of text art meets functionality of clock, timer, pomodoro++ time manager
* [boom](https://github.com/holman/boom) ⭐ 1,319 | 🐛 7 | 🌐 Ruby | 📅 2023-02-19 - Store links and snippets in the command line
* [bashhub](https://github.com/rcaloras/bashhub-client) ⭐ 1,305 | 🐛 26 | 🌐 Python | 📅 2026-08-28 - :cloud: Bash history in the cloud. Indexed and searchable.
* [hr](https://github.com/LuRsT/hr) ⭐ 1,301 | 🐛 2 | 🌐 Roff | 📅 2025-03-08 - `<hr />` for your terminal
* [resh](https://github.com/curusarn/resh) ⭐ 1,056 | 🐛 67 | 🌐 Go | 📅 2023-05-13 - Contextual shell history for Zsh and Bash
* [spot](https://github.com/rauchg/spot) ⭐ 954 | 🐛 7 | 🌐 Shell | 📅 2024-01-02 - Tiny file search utility
* [eureka](https://github.com/simeg/eureka/) ⭐ 873 | 🐛 6 | 🌐 Rust | 📅 2026-08-28 - :bulb: CLI tool to input and store your ideas without leaving the terminal
* [bartib](https://github.com/nikolassv/bartib) ⭐ 845 | 🐛 19 | 🌐 Rust | 📅 2026-03-25 - A simple timetracker for the command line. It saves a log of all tracked activities as a plaintext file and allows you to create flexible reports.
* [has](https://github.com/kdabir/has) ⭐ 818 | 🐛 20 | 🌐 Shell | 📅 2026-02-26 - `has` helps you check presence of various command line tools and their versions on path
* [gitmux](https://github.com/arl/gitmux) ⭐ 791 | 🐛 9 | 🌐 Go | 📅 2026-02-17 - Show Git status in Tmux status bar
* [loop](https://github.com/Miserlou/Loop) ⭐ 697 | 🐛 29 | 🌐 Rust | 📅 2022-09-30 - Write and control complex loops with as one-liners
* [funky](https://github.com/bbugyi200/funky) ⭐ 671 | 🐛 26 | 🌐 Python | 📅 2025-07-15 - Extends functionality of shell functions making them more powerful and flexible.
* [aliases](https://github.com/sebglazebrook/aliases) ⭐ 624 | 🐛 16 | 🌐 Rust | 📅 2024-10-28 - Contextual, dynamic, organized aliases for bash
* [qfc](https://github.com/pindexis/qfc) ⭐ 583 | 🐛 25 | 🌐 Python | 📅 2022-02-20 - File-completion widget for Bash and Zsh
* [fz](https://github.com/changyuheng/fz) ⭐ 574 | 🐛 9 | 🌐 Shell | 📅 2024-02-25 - Seamless fuzzy tab completion for z
* [cod](https://github.com/dim-an/cod) ⭐ 552 | 🐛 22 | 🌐 Go | 📅 2026-07-10 — A completion daemon for shell that learns when you invoke `--help` commands
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) ⭐ 494 | 🐛 13 | 🌐 Shell | 📅 2024-03-04 - Colorize words in a command output
* [SHML](https://github.com/odb/shml) ⭐ 454 | 🐛 2 | 🌐 Shell | 📅 2019-01-25 - Style framework for the terminal (Shell Markup Language)
* [pdd](https://github.com/jarun/pdd) ⭐ 406 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - Tiny date, time diff calculator with timers
* [hss](https://github.com/six-ddc/hss) ⭐ 380 | 🐛 9 | 🌐 C | 📅 2025-10-17 - An interactive parallel ssh client featuring autocomplete and asynchronous execution
* [spark.fish](https://github.com/jorgebucaran/spark.fish) ⭐ 380 | 🐛 0 | 🌐 Shell | 📅 2021-01-16 - ▁▂▃▅ Sparkline Generator
* [slugify](https://github.com/benlinton/slugify) ⭐ 316 | 🐛 4 | 🌐 Groff | 📅 2022-03-02 - Command that converts filenames and directories to a web friendly format
* [sman](https://github.com/tokozedg/sman) ⭐ 301 | 🐛 3 | 🌐 Go | 📅 2017-12-20 - :bug: A command-line snippet manager
* [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile) ⭐ 293 | 🐛 0 | 📅 2026-08-14 - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin.
* [await](https://github.com/slavaGanzin/await) ⭐ 276 | 🐛 2 | 🌐 Python | 📅 2026-08-08 - single binary that run list of commands in parallel and waits for their termination
* [sheet](https://github.com/oscardelben/sheet) ⭐ 270 | 🐛 7 | 🌐 Ruby | 📅 2023-01-09 -  Text snippets for the command line
* [lowcharts](https://github.com/juan-leon/lowcharts) ⭐ 250 | 🐛 10 | 🌐 Rust | 📅 2025-12-22 - Draw low-resolution graphs in terminal
* [shell-history](https://github.com/pawamoy/shell-history) ⭐ 115 | 🐛 14 | 🌐 Python | 📅 2026-03-25 - Visualize your shell usage with Highcharts
* [ok-sh](https://github.com/secretGeek/ok-bash) ⭐ 102 | 🐛 6 | 🌐 Shell | 📅 2025-03-24 - Do you work on many different projects? And in each project, are there commands you use that are specific to that project? You need a .ok file.
* [CloudClip](https://github.com/skywind3000/CloudClip) ⭐ 83 | 🐛 0 | 🌐 Python | 📅 2018-03-15 - Your own clipboard in the cloud, copy and paste text with gist between different systems
* [q](https://github.com/cal2195/q) ⭐ 70 | 🐛 5 | 🌐 Shell | 📅 2020-04-29 - Vim like macro registers for your Bash and Zsh Shell
* [googlr](https://github.com/Astranno/googlr) ⚠️ Archived - Command line tool that lets you search Google from your terminal.
* [lf.sh](https://github.com/suewonjp/lf.sh) ⭐ 46 | 🐛 0 | 🌐 Shell | 📅 2025-04-28 - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
* [foxy](https://github.com/s-p-k/foxy) ⭐ 45 | 🐛 0 | 🌐 Shell | 📅 2018-06-10 - Plain text bookmarks for Firefox and surf browsers.
* [k alias](https://github.com/lingtalfi/k) ⭐ 25 | 🐛 0 | 🌐 Shell | 📅 2016-02-09 - get kool aliases (and more) working with a simple one-liner
* [byobu](https://www.byobu.org) - Text-based window manager and terminal multiplexer
* [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* [parallel](https://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pass](https://www.passwordstore.org/) - Manage passwords from the command line with GPG encryption and optional git integration.
* [screen](https://www.gnu.org/software/screen/) - GNU terminal multiplexer

- [snips](https://github.com/srijanshetty/snips) ⭐ 84 | 🐛 1 | 🌐 TypeScript | 📅 2024-02-27 - Command line tool to manage snippets of code.

* [thefuck](https://github.com/nvbn/thefuck) ⭐ 97,748 | 🐛 456 | 🌐 Python | 📅 2024-07-19 - Fix common shell mistakes by using an easy to remember command
* [xsv](https://github.com/BurntSushi/xsv) ⚠️ Archived - a fast CSV command line toolkit written in Rust
* [usql](https://github.com/xo/usql) ⭐ 10,091 | 🐛 118 | 🌐 Go | 📅 2026-06-19 - Universal command-line interface for SQL databases.
* [xxh](https://github.com/xxh/xxh) ⭐ 6,077 | 🐛 30 | 🌐 Python | 📅 2026-06-02 - Bring your favorite shell wherever you go through the SSH.
* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,813 | 🐛 13 | 🌐 Rust | 📅 2026-08-25 -  A hackable, minimal, fast TUI file explorer
* [xiki](https://github.com/trogdoro/xiki) ⭐ 3,754 | 🐛 118 | 🌐 Ruby | 📅 2020-01-03 - Makes the shell console more friendly and powerful
* [wemux](https://github.com/zolrath/wemux) ⭐ 3,673 | 🐛 37 | 🌐 Shell | 📅 2022-10-03 - Multi-User Tmux Made Easy
* [tere](https://github.com/mgunyho/tere) ⭐ 1,801 | 🐛 16 | 🌐 Rust | 📅 2026-03-09 - A faster alternative to cd + ls
* [sshfs](https://github.com/osxfuse/sshfs) ⭐ 1,204 | 🐛 30 | 🌐 C | 📅 2022-09-06 - A tool for mounting remote file systems over SSH
* [tldr](https://github.com/raylee/tldr-sh-client) ⭐ 738 | 🐛 0 | 🌐 Shell | 📅 2026-01-27 - A fully-functional bash client for tldr, simplified and community-driven man pages
* [sqlline](https://github.com/julianhyde/sqlline) ⭐ 658 | 🐛 63 | 🌐 Java | 📅 2023-07-07 - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support)
* [v](https://github.com/rupa/v) ⭐ 459 | 🐛 14 | 🌐 Roff | 📅 2019-07-08 - z for vim.
* [td-cli](https://github.com/darrikonn/td-cli) ⭐ 214 | 🐛 11 | 🌐 Python | 📅 2026-04-14 - A todo command line manager to organize and manage your todos across multiple projects.
* [undollar](https://github.com/xtyrrell/undollar) ⭐ 207 | 🐛 2 | 🌐 JavaScript | 📅 2018-09-14 - undollar bites the dollar sign off the tip of the command you just pasted into your terminal
* [sudocabulary](https://github.com/badarsh2/Sudocabulary) ⭐ 163 | 🐛 2 | 🌐 Shell | 📅 2017-05-29 - Learn English Vocabulary from your terminal
* [task-manager](https://github.com/lingtalfi/task-manager) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2017-04-18 - Execute all your scripts with just two or three keystrokes.
* [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* [tmux](https://tmux.github.io/) - Amazing terminal multiplexer

### Directory Navigation

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 38,995 | 🐛 139 | 🌐 Rust | 📅 2026-08-28 - A faster way to navigate your filesystem, written in Rust
* [z](https://github.com/rupa/z) ⭐ 17,043 | 🐛 107 | 🌐 Shell | 📅 2024-06-19 - z is the new j, yo
* [autojump](https://github.com/wting/autojump) ⭐ 16,963 | 🐛 231 | 🌐 Python | 📅 2025-02-27 - A cd command that learns - easily navigate directories from the command line
* [z.lua](https://github.com/skywind3000/z.lua) ⭐ 3,144 | 🐛 73 | 🌐 Lua | 📅 2026-08-10 - A new cd command that helps you navigate faster by learning your habits
* [enhancd](https://github.com/b4b4r07/enhancd) ⭐ 2,711 | 🐛 17 | 🌐 Shell | 📅 2025-01-24 - :rocket: A next-generation cd command with an interactive filter
* [bashmarks](https://github.com/huyng/bashmarks) ⭐ 1,968 | 🐛 31 | 🌐 Shell | 📅 2026-07-05 - Directory bookmarks for the shell
* [jump](https://github.com/gsamokovarov/jump) ⭐ 1,944 | 🐛 2 | 🌐 Go | 📅 2026-08-06 - Jump helps you navigate your file system faster by learning your habits.
* [bd](https://github.com/vigneshwaranr/bd) ⭐ 928 | 🐛 29 | 🌐 Shell | 📅 2022-09-15 - Quickly go back to a parent directory
* [goto](https://github.com/iridakos/goto) ⭐ 904 | 🐛 16 | 🌐 Shell | 📅 2024-07-26 - A shell utility for navigation to aliased directories supporting auto-completion
* [commacd](https://github.com/shyiko/commacd) ⭐ 365 | 🐛 4 | 🌐 Shell | 📅 2019-11-07 - A faster way to move around in Bash
* [up](https://github.com/shannonmoeller/up) ⭐ 183 | 🐛 1 | 🌐 Shell | 📅 2020-07-26 - Ascend directories by name or count; for bash, zsh, and fish.
* [aliasme](https://github.com/Jintin/aliasme) ⭐ 130 | 🐛 1 | 🌐 Shell | 📅 2026-08-03 - alias helper to change directory quickly
* [zpyi](https://github.com/sakshamsharma/zpyi) ⭐ 113 | 🐛 6 | 🌐 Shell | 📅 2017-08-13 - Python in Zsh - Easy python scripting in shell
* [lazy-cd](https://github.com/pedramamini/lazy-cd) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2020-04-22 - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion.

## Customization

*Custom prompts, color themes, etc.*

* [powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 54,987 | 🐛 150 | 🌐 Shell | 📅 2026-08-15 - Super flexible awesome powerline ZSH theme
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) ⭐ 10,298 | 🐛 3 | 🌐 Shell | 📅 2026-08-27 - Color Scheme for Gnome Terminal
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) ⭐ 6,937 | 🐛 35 | 🌐 Shell | 📅 2026-04-10 - An informative and fancy Bash prompt for Git users
* [liquidprompt](https://github.com/nojhan/liquidprompt) ⭐ 4,675 | 🐛 30 | 🌐 Shell | 📅 2026-08-23 - A full-featured & carefully designed adaptive prompt for Bash & Zsh
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) ⭐ 3,715 | 🐛 56 | 🌐 Shell | 📅 2022-06-30 - An opinionated git prompt for bash and zsh
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh) ⭐ 2,839 | 🐛 93 | 🌐 Makefile | 📅 2024-07-29 - :bullettrain\_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
* [emojify](https://github.com/mrowa44/emojify) ⭐ 1,584 | 🐛 10 | 🌐 Shell | 📅 2024-01-08 Emoji on the command line :scream:
* [bashstrap](https://github.com/barryclark/bashstrap) ⭐ 1,556 | 🐛 3 | 🌐 Shell | 📅 2019-05-22 - A quick way to spruce up OSX terminal
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) ⭐ 1,156 | 🐛 2 | 🌐 Shell | 📅 2025-11-21 - Bash prompt with colors, Git statuses, and Git branches
* [synth-shell](https://github.com/andresgongora/synth-shell) ⭐ 1,133 | 🐛 21 | 🌐 Shell | 📅 2026-08-22 - Greeter with a customizable status report and a fancy bash prompt
* [geometry](https://github.com/geometry-zsh/geometry) ⭐ 997 | 🐛 13 | 🌐 Shell | 📅 2025-01-13 - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [bash-powerline](https://github.com/riobard/bash-powerline) ⭐ 911 | 🐛 16 | 🌐 Shell | 📅 2023-07-06 - Powerline-style Bash prompt in pure Bash script
* [base16-builder](https://github.com/base16-builder/base16-builder) ⭐ 454 | 🐛 49 | 🌐 HTML | 📅 2021-06-10 - Base16-Builder
* [git-prompt](https://github.com/lvv/git-prompt) ⭐ 327 | 🐛 16 | 🌐 Shell | 📅 2024-05-05 - Bash prompt with Git, SVN and HG modules
* [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) ⭐ 198 | 🐛 3 | 🌐 Shell | 📅 2022-01-21 - Powerful prompt with screen, tmux, git support and many more
* [polyglot](https://github.com/agkozak/polyglot) ⭐ 195 | 🐛 5 | 🌐 Shell | 📅 2026-05-29 - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, oksh, dash, yash, busybox sh, and osh
* [aphrodite-terminal-theme](https://github.com/win0err/aphrodite-terminal-theme) ⭐ 176 | 🐛 2 | 🌐 Shell | 📅 2025-08-04 — Minimalistic Aphrodite theme (prompt) for sexy terminals that works in bash, fish and zsh
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) ⭐ 107 | 🐛 0 | 🌐 Python | 📅 2020-12-01 -  Colorization for mysql comand-line client
* [gittify](https://github.com/momeni/gittify) ⭐ 80 | 🐛 0 | 🌐 Shell | 📅 2022-04-02 - A colorful Bash prompt + customized Git aliases
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* [oh-my-posh](https://ohmyposh.dev) - Prompt theme engine for any shell and platform written in go.
* [starship](https://starship.rs/) - Fast, customisable, cross-shell prompt written in rust

## For Developers

*Command-line development, version control, and deployment.*

* [just](https://github.com/casey/just) ⭐ 35,532 | 🐛 171 | 🌐 Rust | 📅 2026-08-20 - Task runner for saving and running project-specific commands.
* [dokku](https://github.com/dokku/dokku) ⭐ 32,113 | 🐛 26 | 🌐 Shell | 📅 2026-08-28 - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
* [cloc](https://github.com/AlDanial/cloc) ⭐ 23,474 | 🐛 27 | 🌐 Perl | 📅 2026-08-08 - Count Lines of Code
* [hub](https://github.com/github/hub) ⭐ 22,956 | 🐛 294 | 🌐 Go | 📅 2024-02-02 - hub helps you win at git.
* [git-extras](https://github.com/tj/git-extras) ⭐ 18,097 | 🐛 95 | 🌐 Shell | 📅 2026-08-27 - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
* [bocker](https://github.com/p8952/bocker) ⭐ 12,671 | 🐛 15 | 🌐 Shell | 📅 2017-12-09 - Docker implemented in 100 lines of bash
* [git-quick-stats](https://github.com/arzzen/git-quick-stats) ⭐ 7,000 | 🐛 3 | 🌐 Shell | 📅 2026-04-18 - Git quick statistics is a simple and efficient way to access various statistics in git repository.
* [slap](https://github.com/slap-editor/slap) ⭐ 6,188 | 🐛 115 | 🌐 JavaScript | 📅 2021-11-01 - Sublime-like terminal-based text editor that runs on Node.js
* [forgit](https://github.com/wfxr/forgit) ⭐ 5,071 | 🐛 12 | 🌐 Shell | 📅 2026-08-25 - Utility tool for `git` taking advantage of fuzzy finder fzf.
* [rebound](https://github.com/shobrook/rebound) ⭐ 4,114 | 🐛 24 | 🌐 Python | 📅 2022-02-16 - Instantly browse Stack Overflow results in your terminal when you get a compiler error
* [overcommit](https://github.com/sds/overcommit) ⭐ 4,007 | 🐛 33 | 🌐 Ruby | 📅 2026-08-12 - A fully configurable and extendable Git hook manager
* [git-open](https://github.com/paulirish/git-open) ⭐ 3,455 | 🐛 49 | 🌐 Shell | 📅 2026-05-25 - Type `git open` to open the GitHub page or website for a repository in your browser
* [gita](https://github.com/nosarthur/gita) ⭐ 1,932 | 🐛 36 | 🌐 Python | 📅 2026-07-06 - A command-line tool to manage multiple git repos.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) ⭐ 1,168 | 🐛 4 | 🌐 Shell | 📅 2026-08-28 - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
* [git-sh](https://github.com/rtomayko/git-sh) ⚠️ Archived - A customized Bash environment suitable for Git work
* [add-gitignore](https://github.com/TejasQ/add-gitignore) ⭐ 730 | 🐛 5 | 🌐 JavaScript | 📅 2023-11-20 - Interactive CLI that generates a .gitignore for your project based on your needs.
* [bitwise](https://github.com/mellowcandle/bitwise) ⭐ 720 | 🐛 12 | 🌐 C | 📅 2026-08-22 - Terminal based interactive bit manipulator in curses.
* [nve](https://github.com/ehmicky/nve) ⭐ 711 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-04 - Run any command on specific Node.js versions.
* [bcal](https://github.com/jarun/bcal) ⭐ 699 | 🐛 0 | 🌐 C | 📅 2026-08-16 - Byte CALculator for storage conversions and calculations
* [tag](https://github.com/aykamko/tag) ⭐ 612 | 🐛 12 | 🌐 Go | 📅 2023-01-24 - Instantly jump to your ag matches.
* [shipit](https://github.com/sapegin/shipit) ⭐ 566 | 🐛 2 | 🌐 Shell | 📅 2020-04-08 - Minimalistic SSH deployment
* [git-semver](https://github.com/markchalloner/git-semver) ⭐ 395 | 🐛 12 | 🌐 Shell | 📅 2020-01-21 - Git plugin for easing semantic versioning and changelog validation
* [mkdkr](https://github.com/rosineygp/mkdkr) ⭐ 382 | 🐛 0 | 🌐 Shell | 📅 2021-05-27 - Makefile + Docker = CI Pipeline
* [repren](https://github.com/jlevy/repren) ⭐ 374 | 🐛 14 | 🌐 Python | 📅 2026-08-26 - Command-line search-and-replace and file-renaming swiss army knife
* [wipe-modules](https://github.com/bntzio/wipe-modules) ⭐ 360 | 🐛 4 | 🌐 Shell | 📅 2023-01-30 - A little agent that removes the node\_modules folder of non-active projects
* [starring](https://github.com/ritz078/starring) ⭐ 155 | 🐛 2 | 🌐 JavaScript | 📅 2017-09-09 - Automatically star the npm-packages that you are using on GitHub.
* [vmn](https://github.com/final-israel/vmn) ⭐ 65 | 🐛 47 | 🌐 Python | 📅 2026-08-09 - git-based automatic versioning and state recovery solution agnostic to language or architecture
* [doclt](https://github.com/omgimanerd/doclt) ⭐ 47 | 🐛 2 | 🌐 JavaScript | 📅 2018-09-13 - A command line interface to Digital Ocean
* [licins](https://github.com/dogoncouch/licins) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2022-07-04 - Insert commented software licenses into source code.
* [1Password SSH Agent](https://developer.1password.com/docs/ssh/) - Authenticate Git and SSH workflows with biometric unlock using 1Password
* [ack](https://beyondgrep.com/) - A grep-like search tool optimized for source code.
* [mr](https://myrepos.branchable.com) - Multiple Repository management tool
* [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* [trunk](https://www.npmjs.com/package/@trunkio/launcher) - Blazingly fast meta code checker and formatter

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [bat](https://github.com/sharkdp/bat) ⭐ 60,288 | 🐛 424 | 🌐 Rust | 📅 2026-08-11 - A `cat` clone with wings
* [btop](https://github.com/aristocratos/btop) ⭐ 34,284 | 🐛 534 | 🌐 C++ | 📅 2026-08-26 - Linux/OSX/FreeBSD resource monitor
* [glances](https://github.com/nicolargo/glances) ⭐ 33,459 | 🐛 109 | 🌐 Python | 📅 2026-08-27 - Glances an Eye on your system
* [exa](https://github.com/ogham/exa) ⭐ 24,444 | 🐛 213 | 🌐 Rust | 📅 2024-09-24 - A modern version of `ls`.
* [goaccess](https://github.com/allinurl/goaccess) ⭐ 20,877 | 🐛 457 | 🌐 C | 📅 2026-08-20 - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
* [lsd](https://github.com/Peltoche/lsd) ⭐ 16,199 | 🐛 205 | 🌐 Rust | 📅 2026-08-17 - LSDeluxe, rewrite of GNU ls with lot of added features like colors, icons, tree-view and more formatting options.
* [progress](https://github.com/Xfennec/progress) ⭐ 8,858 | 🐛 66 | 🌐 C | 📅 2024-11-19 - Linux tool to show progress for `cp`, `rm`, `dd`, and more...
* [htop](https://github.com/hishamhm/htop) ⚠️ Archived - A ncurses based interactive process viewer which aims to be a better `top`
* [mtr](https://github.com/traviscross/mtr) ⭐ 3,339 | 🐛 137 | 🌐 C | 📅 2026-06-16 - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* [ccat](https://github.com/owenthereal/ccat) ⭐ 3,208 | 🐛 41 | 🌐 Go | 📅 2022-09-05 - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
* [tiptop](https://github.com/nschloe/tiptop) ⭐ 2,123 | 🐛 25 | 🌐 Python | 📅 2025-09-04 - Graphical command-line system monitor.
* [hblock](https://github.com/hectorm/hblock) ⭐ 1,981 | 🐛 24 | 🌐 Shell | 📅 2026-07-01 - Hosts-file based adblocker
* [maza](https://github.com/tanrax/maza-ad-blocking) ⭐ 1,870 | 🐛 2 | 🌐 Shell | 📅 2026-08-14 - Local ad blocker. Like Pi-hole but local and using your operating system.
* [bmon](https://github.com/tgraf/bmon) ⭐ 1,385 | 🐛 38 | 🌐 C | 📅 2026-08-24 - Real-time network bandwidth monitor and rate estimator with human-friendly visual output
* [powertop](https://github.com/fenrus75/powertop) ⭐ 1,331 | 🐛 102 | 🌐 C++ | 📅 2026-08-18 - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
* [prettyping](https://github.com/denilsonsa/prettyping) ⭐ 1,287 | 🐛 31 | 🌐 Shell | 📅 2025-06-01 - Making the output of `ping` prettier, more colorful, more compact, and easier to read.
* [stronghold](https://github.com/alichtman/stronghold) ⭐ 1,191 | 🐛 10 | 🌐 Python | 📅 2025-02-24 - Easily configure MacOS security settings from the terminal.
* [xiringuito](https://github.com/ivanilves/xiringuito) ⭐ 1,160 | 🐛 8 | 🌐 Shell | 📅 2021-12-29 - SSH-based "VPN for poors"
* [lsp](https://github.com/dborzov/lsp) ⭐ 532 | 🐛 13 | 🌐 Go | 📅 2021-02-21 - An improved `ls`, with file descriptions in plain language and intelligent file grouping
* [ls++](https://github.com/trapd00r/ls--) ⭐ 514 | 🐛 14 | 🌐 Perl | 📅 2024-06-08 - Colorized ls on steroids
* [nmtui](https://github.com/NetworkManager/NetworkManager) ⭐ 506 | 🐛 2 | 🌐 C | 📅 2026-08-28 - Text User Interface for controlling NetworkManager
* [quick-secure](https://github.com/marshyski/quick-secure) ⭐ 425 | 🐛 1 | 🌐 Shell | 📅 2020-03-09 - Quickly secure and harden UNIX/Linux systems
* [catcli](https://github.com/deadc0de6/catcli) ⚠️ Archived -  The command line catalog tool for your offline data
* [logdissect](https://github.com/dogoncouch/logdissect) ⭐ 161 | 🐛 3 | 🌐 Python | 📅 2024-08-07 - CLI utility and Python API for analyzing log files and other data.
* [histstat](https://github.com/vesche/histstat) ⭐ 98 | 🐛 1 | 🌐 Python | 📅 2022-01-26 - History for netstat
* [wifi-wand](https://github.com/keithrbennett/wifiwand) ⭐ 80 | 🐛 1 | 🌐 Ruby | 📅 2026-07-13 - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`)
* [procdog](https://github.com/jlevy/procdog) ⭐ 79 | 🐛 3 | 🌐 Python | 📅 2018-09-14 - Lightweight command-line control of long-lived processes like servers
* [rng](https://github.com/nickolasburr/rng) ⭐ 36 | 🐛 0 | 🌐 C | 📅 2026-03-17 - Copy range of lines from file or stdin to stdout.
* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* [lnav](https://lnav.org) - An advanced log file viewer for the small-scale
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [yt-dlp](https://github.com/yt-dlp/yt-dlp) ⭐ 187,573 | 🐛 2,596 | 🌐 Python | 📅 2026-08-27 - Command-line program to download videos from YouTube.com and other video sites
* [aria2](https://github.com/aria2/aria2) ⭐ 41,857 | 🐛 1,175 | 🌐 C++ | 📅 2026-06-25 - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
* [httpie](https://github.com/httpie/httpie) ⭐ 38,465 | 🐛 335 | 🌐 Python | 📅 2024-12-17 - HTTPie is a command line HTTP client, a user-friendly cURL replacement
* [xh](https://github.com/ducaale/xh) ⭐ 8,042 | 🐛 38 | 🌐 Rust | 📅 2026-08-23 - Friendly and fast tool for sending HTTP requests
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) ⭐ 6,599 | 🐛 161 | 🌐 Shell | 📅 2024-06-04 - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
* [HTTPLab](https://github.com/gchaincl/httplab) ⭐ 4,139 | 🐛 13 | 🌐 Go | 📅 2024-02-05 - The interactive web server, let you inspect HTTP requests and forge responses.
* [resty](https://github.com/micha/resty) ⭐ 2,653 | 🐛 17 | 🌐 Shell | 📅 2023-02-17 - Little command line REST client that you can use in pipelines
* [bashttpd](https://github.com/avleen/bashttpd) ⭐ 1,553 | 🐛 15 | 🌐 Shell | 📅 2026-07-24 - A web server written in Bash
* [shell2http](https://github.com/msoap/shell2http) ⭐ 1,504 | 🐛 6 | 🌐 Go | 📅 2026-08-08 - HTTP-server to execute shell commands. Designed for development, prototyping or remote control
* [bitpocket](https://github.com/sickill/bitpocket) ⭐ 1,034 | 🐛 28 | 🌐 Shell | 📅 2023-08-12 - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
* [balls](https://github.com/jneen/balls) ⭐ 869 | 🐛 5 | 🌐 Shell | 📅 2016-07-29 - Bash on Balls
* [Kapow!](https://github.com/BBVA/kapow) ⭐ 623 | 🐛 32 | 🌐 Go | 📅 2024-10-23 - If you can script it, you can HTTP it.
* [bashhub-server](https://github.com/nicksherron/bashhub-server) ⭐ 317 | 🐛 13 | 🌐 Go | 📅 2023-03-30 - Private cloud shell history. Open source server for bashhub
* [vesper](https://github.com/chris-rock/vesper) ⭐ 213 | 🐛 1 | 🌐 Shell | 📅 2019-11-28 - 🍸Vesper is a HTTP framework for Bash/Unix Shell
* [ngincat](https://github.com/jaburns/ngincat) ⭐ 183 | 🐛 0 | 🌐 Shell | 📅 2014-07-18 - Tiny Bash HTTP server using netcat
* [tshare](https://github.com/trikko/tshare) ⭐ 142 | 🐛 0 | 🌐 D | 📅 2023-12-13 - File sharing from commandline.

## Multimedia and File Formats

*Tools for handling video and audio files.*

* [jq](https://github.com/stedolan/jq) ⭐ 35,504 | 🐛 472 | 🌐 C | 📅 2026-08-23 - Sed for json data. You can use it to slice and filter and map and transform structured data
* [fx](https://github.com/antonmedv/fx) ⭐ 20,603 | 🐛 26 | 🌐 Go | 📅 2026-08-26 - Command-line JSON processing tool by anononymus JavaScript functions
* [yq](https://github.com/mikefarah/yq) ⭐ 15,901 | 🐛 288 | 🌐 Go | 📅 2026-08-27 - yq is a portable command-line YAML processor
* [Beets](https://github.com/beetbox/beets) ⭐ 15,597 | 🐛 715 | 🌐 Python | 📅 2026-08-27 - Music library manager and MusicBrainz tagger
* [visidata](https://github.com/saulpw/visidata) ⭐ 9,256 | 🐛 80 | 🌐 Python | 📅 2026-08-28 - A terminal spreadsheet multitool for exploring and arranging data (csv/json/xml/xls/yaml/etc)
* [jc](https://github.com/kellyjonbrazil/jc) ⭐ 8,669 | 🐛 40 | 🌐 Python | 📅 2026-08-28 - Convert command output, file-types, and common strings to JSON or YAML for easier use in scripts.
* [dasel](https://github.com/tomwright/dasel) ⭐ 8,028 | 🐛 25 | 🌐 Go | 📅 2026-08-16 - Query and update data structures using selectors from the command line. Comparable to [jq](https://github.com/stedolan/jq) ⭐ 35,504 | 🐛 472 | 🌐 C | 📅 2026-08-23 / [yq](https://github.com/kislyuk/yq) ⭐ 2,972 | 🐛 23 | 🌐 Python | 📅 2026-07-11 but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [cmus](https://github.com/cmus/cmus) ⭐ 6,227 | 🐛 219 | 🌐 C | 📅 2026-08-12 - Cross-platform cli audio player.
* [jo](https://github.com/jpmens/jo) ⭐ 4,863 | 🐛 7 | 🌐 C | 📅 2025-06-20 - A small utility to create JSON objects from command-line arguments.
* [PiCAST](https://github.com/lanceseidman/PiCAST) ⭐ 1,795 | 🐛 26 | 🌐 Shell | 📅 2026-03-28 - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
* [imgp](https://github.com/jarun/imgp) ⭐ 1,091 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - Blazing fast batch image resizer and rotator
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) ⭐ 1,076 | 🐛 4 | 🌐 Shell | 📅 2021-02-19 - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
* [xidel](https://github.com/benibela/xidel/) ⭐ 843 | 🐛 26 | 🌐 Pascal | 📅 2025-02-22 - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
* [image-scraper](https://github.com/sananth12/ImageScraper) ⭐ 774 | 🐛 25 | 🌐 Python | 📅 2018-01-04 - A cool command line image scraper with a lot of features.
* [gifgen](https://github.com/lukechilds/gifgen) ⭐ 565 | 🐛 2 | 🌐 Shell | 📅 2023-01-22 - Simple high quality GIF encoding
* [sejda](https://github.com/torakiki/sejda/) ⭐ 548 | 🐛 49 | 🌐 Java | 📅 2026-08-23 - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
* [library](https://github.com/chapmanjacobd/library) ⭐ 480 | 🐛 7 | 🌐 Python | 📅 2026-08-29 - Create SQLITE databases for folders of music, video, images, or online media. Play and track media like Plex but a CLI-only interface with many sorting options.
* [korkut](https://github.com/oguzhaninan/korkut) ⭐ 385 | 🐛 6 | 🌐 TypeScript | 📅 2022-12-03 - Quick and simple image processing at the command line.
* [dzr](https://github.com/yne/dzr) ⭐ 263 | 🐛 3 | 🌐 Shell | 📅 2026-03-15 - Cross-platform Deezer.com audio player.
* [adb-export](https://github.com/sromku/adb-export) ⭐ 116 | 🐛 2 | 🌐 Shell | 📅 2022-09-08 - Export Android content providers to CSV format
* [nehm](https://github.com/bogem/nehm) ⚠️ Archived - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
* [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.

## Applications

*Command line-based applications or command line access to existing services.*

* [wttr.in](https://github.com/chubin/wttr.in) ⭐ 30,434 | 🐛 330 | 🌐 Go | 📅 2026-08-02 - :partly\_sunny: The right way to check the weather (curl wttr.in)
* [ranger](https://github.com/ranger/ranger) ⭐ 17,374 | 🐛 898 | 🌐 Python | 📅 2026-08-15 - A console file manager with VI key bindings.
* [taskbook](https://github.com/klaussinani/taskbook) ⭐ 9,339 | 🐛 101 | 🌐 JavaScript | 📅 2025-11-03 - Tasks, boards & notes for the command-line habitat
* [wego](https://github.com/schachmat/wego) ⭐ 8,540 | 🐛 16 | 🌐 Go | 📅 2026-08-01 - Weather app for the terminal
* [jrnl](https://github.com/jrnl-org/jrnl) ⭐ 7,304 | 🐛 151 | 🌐 Python | 📅 2026-08-27 - A simple command line journal application that stores your journal in a plain text file
* [ticker](https://github.com/achannarasappa/ticker) ⭐ 6,221 | 🐛 33 | 🌐 Go | 📅 2026-06-28 — Terminal stock ticker with live updates and position tracking
* [carbon-now-cli](https://github.com/mixn/carbon-now-cli) ⭐ 6,031 | 🐛 8 | 🌐 TypeScript | 📅 2025-11-14 - 🎨 Beautiful images of your code — from right inside your terminal.
* [ledger](https://github.com/ledger/ledger) ⭐ 6,020 | 🐛 19 | 🌐 C++ | 📅 2026-08-28 - Command line accounting
* [editly](https://github.com/mifi/editly) ⭐ 5,479 | 🐛 80 | 🌐 TypeScript | 📅 2025-05-12 - Command line video editor
* [SAWS](https://github.com/donnemartin/saws) ⭐ 5,303 | 🐛 39 | 🌐 Python | 📅 2024-04-02 - A Supercharged AWS CLI
* [awless](https://github.com/wallix/awless) ⭐ 4,956 | 🐛 119 | 🌐 Go | 📅 2022-08-02 - A powerful, innovative and small surface CLI to manage AWS.
* [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) ⚠️ Archived - Browse Reddit from your terminal
* [cointop](https://github.com/miguelmota/cointop) ⚠️ Archived - The fastest and most interactive terminal based UI application for tracking cryptocurrencies
* [haxor-news](https://github.com/donnemartin/haxor-news) ⭐ 4,089 | 🐛 42 | 🌐 Python | 📅 2022-04-22 - Browse Hacker News like a haxor
* [gcalcli](https://github.com/insanum/gcalcli) ⭐ 3,758 | 🐛 170 | 🌐 Python | 📅 2025-10-25 - Google Calendar command line interface
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) ⭐ 2,090 | 🐛 205 | 🌐 Python | 📅 2021-02-06 - Command line evernote client
* [ansiweather](https://github.com/fcambus/ansiweather) ⭐ 1,946 | 🐛 0 | 🌐 Shell | 📅 2026-07-24 - Weather in your terminal, with ANSI colors and Unicode symbols
* [bashblog](https://github.com/cfenollosa/bashblog) ⭐ 1,928 | 🐛 35 | 🌐 Shell | 📅 2026-07-09 - A Bash script that handles blog posting
* [fanyi](https://github.com/afc163/fanyi) ⭐ 1,554 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-24 - Translate English to Chinese in terminal
* [dstask](https://github.com/naggie/dstask) ⭐ 1,202 | 🐛 43 | 🌐 Go | 📅 2026-05-11 - Single binary terminal-based TODO manager with git-based sync + markdown notes per task
* [kanban.bash](https://github.com/coderofsalvation/kanban.bash) ⭐ 956 | 🐛 6 | 🌐 Shell | 📅 2026-07-15 - commandline asciii kanban board for minimalist productivity bash hackers (csv-based)
* [terjira](https://github.com/keepcosmos/terjira) ⭐ 909 | 🐛 30 | 🌐 Ruby | 📅 2023-03-15 - Command line power tool for Jira
* [nomino](https://github.com/yaa110/nomino) ⭐ 709 | 🐛 6 | 🌐 Rust | 📅 2025-08-07 - Batch rename utility using regex, sort and map file options.
* [pcalc](https://github.com/alt-romes/programmer-calculator) ⭐ 589 | 🐛 5 | 🌐 C | 📅 2025-11-06 - Calculator made for programmers working with multiple number representations, sizes, and overall close to the bits.
* [pockyt](https://github.com/achembarpu/pockyt) ⭐ 498 | 🐛 5 | 🌐 Python | 📅 2024-04-25 - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection.
* [hn-cli](https://github.com/rafaelrinaldi/hn-cli) ⚠️ Archived - Browse Hacker News from the comfort of your Terminal
* [facebook-cli](https://github.com/specious/facebook-cli) ⭐ 404 | 🐛 18 | 🌐 Ruby | 📅 2022-05-12 - Facebook command line tool
* [whales](https://github.com/Gueils/whales) ⭐ 395 | 🐛 4 | 🌐 Ruby | 📅 2019-05-27 - A tool to automatically dockerize your applications
* [iponmap](https://github.com/nogizhopaboroda/iponmap) ⭐ 330 | 🐛 4 | 🌐 JavaScript | 📅 2016-09-28 - Draw point on world map using ip address
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) ⭐ 236 | 🐛 6 | 🌐 Shell | 📅 2023-10-04 - Bash interface to the PushBullet API
* [moviemon](https://github.com/iCHAIT/moviemon) ⭐ 229 | 🐛 6 | 🌐 Python | 📅 2016-11-19 - Everything about your movies within the command line.
* [whereami](https://github.com/rafaelrinaldi/whereami) ⚠️ Archived - Get your geolocation information from the CLI
* [pushblast](https://github.com/alebcay/pushblast) ⭐ 99 | 🐛 1 | 🌐 Shell | 📅 2015-12-18 - Get PushBullet notifications when a shell program exits
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) ⭐ 78 | 🐛 1 | 🌐 Python | 📅 2020-05-28 - Choose an OSS license from the comfort of your terminal
* [isitup](https://github.com/lord63/isitup) ⭐ 68 | 🐛 0 | 🌐 Python | 📅 2026-03-15 - Check whether a website is up or down
* [md2png](https://github.com/weaming/md2png) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2018-11-01 - Convert markdown to PNG image
* [licen](https://github.com/lord63/licen) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2026-04-14 - Generate your license. Yet another lice, but implement with Jinja2 and docopt
* [vl](https://github.com/ellisonleao/vl) ⭐ 30 | 🐛 5 | 🌐 Go | 📅 2024-06-24 - URL link checker on text documents
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048](https://github.com/mydzor/bash2048) ⭐ 910 | 🐛 0 | 🌐 Shell | 📅 2024-04-30 - Bash implementation of 2048 game
* [piu-piu](https://github.com/vaniacer/piu-piu-SH) ⭐ 746 | 🐛 3 | 🌐 Shell | 📅 2025-05-28 - Horizontal scroller game in bash with multiplayer mode!
* [sedtris](https://github.com/uuner/sedtris) ⭐ 567 | 🐛 5 | 🌐 Shell | 📅 2020-06-06 - Tetris in sed
* [nudoku](https://github.com/jubalh/nudoku) ⭐ 374 | 🐛 2 | 🌐 C | 📅 2026-07-08 - ncurses based sudoku game written in C
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) ⭐ 358 | 🐛 24 | 🌐 C | 📅 2025-05-03 - Play solitaire in your terminal!
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) ⭐ 66 | 🐛 4 | 🌐 Shell | 📅 2020-05-29 - Bash implementation of minesweeper
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) ⭐ 46 | 🐛 0 | 📅 2013-02-12 - Arkanoid and Sokoban written using sed
* [SHTAP](https://notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* [bash-it](https://github.com/Bash-it/bash-it) ⭐ 15,151 | 🐛 5 | 🌐 Shell | 📅 2026-08-09 - A community Bash framework
* [vcsh](https://github.com/RichiH/vcsh) ⭐ 2,275 | 🐛 73 | 🌐 Shell | 📅 2025-12-29 - Config manager based on Git
* [homeshick](https://github.com/andsens/homeshick) ⭐ 2,193 | 🐛 17 | 🌐 Shell | 📅 2026-08-28 - Git dotfile synchronizer written in Bash
* [dotdrop](https://github.com/deadc0de6/dotdrop) ⭐ 1,942 | 🐛 5 | 🌐 Python | 📅 2026-08-28 - Save your dotfiles once, deploy them everywhere
* [shallow-backup](https://github.com/alichtman/shallow-backup) ⭐ 1,336 | 🐛 23 | 🌐 Python | 📅 2026-03-21 - Easily create lightweight documentation of installed packages, dotfiles, and more
* [basher](https://github.com/basherpm/basher) ⭐ 1,301 | 🐛 15 | 🌐 Shell | 📅 2025-11-18 - A package manager for shell scripts
* [fresh](https://github.com/freshshell/fresh) ⭐ 1,229 | 🐛 42 | 🌐 Ruby | 📅 2026-06-24 - Keep your dotfiles fresh
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) ⭐ 254 | 🐛 7 | 🌐 Python | 📅 2025-08-23 – Shell agnostic git based dotfiles package manager, written in Python.
* [shundle](https://github.com/javier-lopez/shundle) ⭐ 85 | 🐛 5 | 🌐 Shell | 📅 2020-01-29 - Plugin manager for shell scripts
* [bashing](https://github.com/xsc/bashing) ⚠️ Archived - Smashing Bash into Pieces
* [bpkg](https://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* [yadm](https://yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [shellcheck](https://github.com/koalaman/shellcheck) ⭐ 39,951 | 🐛 1,138 | 🌐 Haskell | 📅 2026-08-04 - Static analysis tool for shell scripts
* [shfmt](https://github.com/mvdan/sh) ⭐ 9,019 | 🐛 97 | 🌐 Go | 📅 2026-08-28 - A shell parser, formatter, and interpreter with bash support; includes shfmt
* [bats](https://github.com/bats-core/bats-core) ⭐ 6,238 | 🐛 127 | 🌐 Shell | 📅 2026-07-26 - Bash Automated Testing System
* [bash-language-server](https://github.com/bash-lsp/bash-language-server) ⭐ 2,775 | 🐛 135 | 🌐 TypeScript | 📅 2026-08-28 - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server
* [sub](https://github.com/basecamp/sub) ⭐ 1,761 | 🐛 9 | 🌐 Shell | 📅 2021-08-24 - A delicious way to organize programs
* [shunit2](https://github.com/kward/shunit2) ⭐ 1,737 | 🐛 46 | 🌐 Shell | 📅 2026-03-15 - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* [shellspec](https://github.com/shellspec/shellspec) ⭐ 1,394 | 🐛 110 | 🌐 Shell | 📅 2025-11-24 - A full-featured BDD unit testing framework for dash, bash, ksh, zsh and all POSIX shells
* [shellfire](https://github.com/shellfire-dev/shellfire) ⭐ 1,225 | 🐛 15 | 🌐 Shell | 📅 2015-12-14 -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
* [ansi](https://github.com/fidian/ansi) ⭐ 838 | 🐛 2 | 🌐 Shell | 📅 2021-11-28 - ANSI escape codes in pure bash - change text color, position the cursor, much more
* [bashful](https://github.com/jmcantrell/bashful) ⚠️ Archived - A collection of libraries to simplify writing Bash scripts
* [mo](https://github.com/tests-always-included/mo) ⭐ 606 | 🐛 11 | 🌐 Shell | 📅 2026-01-19 - Mustache templates in pure bash
* [getoptions](https://github.com/ko1nksm/getoptions) ⭐ 520 | 🐛 16 | 🌐 Shell | 📅 2024-11-18 - An elegant option parser for shell scripts (sh, bash and all POSIX shells)
* [assert.sh](https://github.com/lehmannro/assert.sh) ⭐ 491 | 🐛 17 | 🌐 Shell | 📅 2022-01-21 - Bash unit testing framework
* [rerun](https://github.com/rerun/rerun) ⭐ 462 | 🐛 40 | 🌐 Shell | 📅 2018-05-16 - A modular shell automation framework to organize your keeper scripts
* [critic.sh](https://github.com/Checksum/critic.sh) ⭐ 456 | 🐛 2 | 🌐 Shell | 📅 2020-08-11 - Dead simple testing framework for Bash with coverage reporting
* [shpec](https://github.com/rylnd/shpec) ⭐ 386 | 🐛 20 | 🌐 Shell | 📅 2022-12-19 - A shell testing framework
* [Fishtape](https://github.com/jorgebucaran/fishtape) ⭐ 383 | 🐛 4 | 🌐 Shell | 📅 2024-05-26 - TAP producer and test harness for fish
* [composure](https://github.com/erichs/composure) ⭐ 345 | 🐛 2 | 🌐 Shell | 📅 2022-11-17 - Compose, document, version and organize your shell functions
* [bashew](https://github.com/pforret/bashew) ⭐ 296 | 🐛 1 | 🌐 Shell | 📅 2026-08-24 - bash script creator - from small stand-alone script to complex projects with CI/CD and testing
* [semver\_bash](https://github.com/cloudflare/semver_bash) ⭐ 268 | 🐛 13 | 🌐 Shell | 📅 2026-04-24 - Semantic Versioning in Bash
* [esh](https://github.com/jirutka/esh) ⭐ 241 | 🐛 6 | 🌐 Shell | 📅 2026-03-31 - A simple templating engine based on shell, implemented in \~290 lines of POSIX shell and awk.
* [getopts.fish](https://github.com/jorgebucaran/getopts.fish) ⭐ 235 | 🐛 0 | 🌐 Shell | 📅 2025-04-15 - CLI parser for fish
* [zunit](https://github.com/zunit-zsh/zunit) ⭐ 226 | 🐛 18 | 🌐 Shell | 📅 2023-08-14 - A powerful unit testing framework for ZSH
* [is.sh](https://github.com/qzb/is.sh) ⭐ 174 | 🐛 5 | 🌐 Shell | 📅 2019-11-20 - An alternative for builtin test command, it will make your "if" statements pretty
* [powscript](https://github.com/coderofsalvation/powscript) ⭐ 168 | 🐛 15 | 🌐 Shell | 📅 2024-12-13 - bash transpiler written in bash (coffeescript for bash)
* [optparse](https://github.com/nk412/optparse) ⭐ 164 | 🐛 19 | 🌐 Shell | 📅 2022-01-01 - A BASH wrapper for getopts, for simple command line arguments.
* [revolver](https://github.com/molovo/revolver) ⭐ 163 | 🐛 7 | 🌐 Shell | 📅 2024-07-15 - A reusable progress spinner for shell scripts
* [bash-modules](https://github.com/vlisivka/bash-modules) ⭐ 151 | 🐛 2 | 🌐 Shell | 📅 2025-08-27 - functions for developing with [unofficial strict mode](http://redsymbol.net/articles/unofficial-bash-strict-mode/) enabled.
* [bashmanager](https://github.com/lingtalfi/bashmanager) ⭐ 102 | 🐛 0 | 🌐 Shell | 📅 2016-02-27 - mini bash framework for creating command line tools
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) ⚠️ Archived - A command line argument parser in 50 lines of portable shell script.
* [Bashlets](https://github.com/reale/bashlets) ⭐ 84 | 🐛 0 | 🌐 Shell | 📅 2021-05-03 - A modular extensible toolbox for Bash
* [rebash](https://github.com/jandob/rebash) ⭐ 80 | 🐛 2 | 🌐 Shell | 📅 2022-02-27 - Scripting library/framework. Features: imports, exceptions, doc-tests ...
* [crash](https://github.com/molovo/crash) ⭐ 69 | 🐛 1 | 🌐 Shell | 📅 2017-03-28 - Proper error handling, exceptions and try/catch for ZSH
* [ts](https://github.com/thinkerbot/ts) ⭐ 61 | 🐛 9 | 🌐 Shell | 📅 2020-12-06 - A shell test script
* [lumberjack](https://github.com/molovo/lumberjack) ⭐ 47 | 🐛 1 | 🌐 Shell | 📅 2016-09-14 - A logging interface for shell scripts
* [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails) ⭐ 33 | 🐛 0 | 🌐 Shell | 📅 2023-07-21 - a Bash framework written just for fun with testing, dependency management & packaging
* [sh-semver](https://github.com/qzb/sh-semver) ⭐ 29 | 🐛 2 | 🌐 Shell | 📅 2021-08-12 - Semver tool for bash - finds versions matching to specified rules
* [phases](https://github.com/sorokine/phases) ⭐ 15 | 🐛 1 | 🌐 Shell | 📅 2018-05-15 - Minimally invasive bash preprocessor, select sections of your script to run
* [bashly](https://bashly.dannyb.co/) - Bash command line framework and CLI generator
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* [urchin](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands

# Guides

* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) ⭐ 162,178 | 🐛 257 | 📅 2024-06-25
* [A guide to learn bash](https://github.com/Idnan/bash-guide) ⭐ 12,373 | 🐛 27 | 📅 2024-08-11
* [Bash Official Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
* [Bash Hackers Wiki](https://web.archive.org/web/20230406205817/https://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](https://mywiki.wooledge.org).
  Specifically [Bash Guide](https://mywiki.wooledge.org/BashGuide), [Bash FAQ](https://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](https://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](https://tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics)
* [Shell Field Guide](https://raimonster.com/scripting-field-guide/)

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) ⭐ 3,203 | 🐛 25 | 📅 2024-07-31 and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,634 | 🐛 61 | 🌐 Ruby | 📅 2024-06-02.

### See also

* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) ⭐ 20,274 | 🐛 0 | 🌐 Shell | 📅 2026-08-22
* [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy) ⭐ 13,094 | 🐛 150 | 🌐 Shell | 📅 2024-07-26
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [awesome-bash][awesome-bash]

[awesome-badge]: https://raw.githubusercontent.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

[awesome-fish]: https://github.com/jorgebucaran/awsm.fish

[awesome-link]: https://github.com/sindresorhus/awesome

[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins

[awesome-bash]: https://github.com/awesome-lists/awesome-bash

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
