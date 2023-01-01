Wiki:            https://wiki.termux.com
Community forum: https://termux.com/community
Gitter chat:     https://gitter.im/termux/termux
IRC channel:     #termux on freenode

Working with packages:

 * Search packages:   pkg search <query>
 * Install a package: pkg install <package>
 * Upgrade packages:  pkg upgrade

Subscribing to additional repositories:

 * Root:     pkg install root-repo
 * Unstable: pkg install unstable-repo
 * X11:      pkg install x11-repo

Report issues at https://termux.com/issues

$ pkg instal git
Testing the available mirrors:
[*] https://dl.bintray.com/termux/termux-packages-24: bad
[*] https://grimler.se/termux-packages-24: ok
[*] https://main.termux-mirror.ml: ok
[*] https://termux.mentality.rip/termux-packages-24: ok
Picking mirror: https://termux.mentality.rip/termux-packages-24
Get:1 https://termux.mentality.rip/termux-packages-24 stable InRelease [14.0 kB]
Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
Get:4 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 Packages [481 kB]
Err:5 https://dl.bintray.com/grimler/game-packages-24 games Release
  404  Not Found
Err:6 https://dl.bintray.com/grimler/science-packages-24 science Release
  404  Not Found
Reading package lists... Done
E: The repository 'https://dl.bintray.com/grimler/game-packages-24 games Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
E: The repository 'https://dl.bintray.com/grimler/science-packages-24 science Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
$ pkg installation python
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree... Done
The following additional packages will be installed:
  clang gdbm glib libandroid-posix-semaphore
  libcompiler-rt libexpat libffi libllvm libsqlite
  libxml2 lld llvm make ncurses ncurses-ui-libs
  ndk-sysroot pcre2 pkg-config
Suggested packages:
  python-tkinter
The following NEW packages will be installed:
  clang gdbm glib libandroid-posix-semaphore
  libcompiler-rt libexpat libffi libllvm libsqlite
  libxml2 lld llvm make ncurses-ui-libs ndk-sysroot
  pcre2 pkg-config python
The following packages will be upgraded:
  ncurses
1 upgraded, 18 newly installed, 0 to remove and 52 not upgraded.
Need to get 81.0 MB of archives.
After this operation, 500 MB of additional disk space will be used.
Do you want to continue? [Y/n]
Get:1 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 ncurses aarch64 6.3-5 [512 kB]
Get:2 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libffi aarch64 3.4.4 [30.7 kB]
Get:3 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libxml2 aarch64 2.10.3 [535 kB]
Get:4 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libllvm aarch64 15.0.6 [22.9 MB]
Get:5 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libcompiler-rt aarch64 15.0.6 [2966 kB]
Get:6 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 lld aarch64 15.0.6 [1944 kB]
Get:7 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 llvm aarch64 15.0.6 [8302 kB]
Get:8 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 ndk-sysroot aarch64 25b-3 [1418 kB]
Get:9 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 clang aarch64 15.0.6 [28.3 MB]
Get:10 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 gdbm aarch64 1.23 [142 kB]
Get:11 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 pcre2 aarch64 10.42 [856 kB]
Get:12 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 glib aarch64 2.74.4-1 [1238 kB]
Get:13 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libandroid-posix-semaphore aarch64 0.1-3 [4128 B]
Get:14 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libexpat aarch64 2.5.0 [81.7 kB]
Get:15 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libsqlite aarch64 3.40.1 [572 kB]
Get:16 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 make aarch64 4.4 [238 kB]
Get:17 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 ncurses-ui-libs aarch64 6.3-5 [31.9 kB]
Get:18 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 pkg-config aarch64 0.29.2-2 [31.4 kB]
Get:19 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 python aarch64 3.11.1 [10.8 MB]
Fetched 81.0 MB in 51s (1573 kB/s)
(Reading database ... 3457 files and directories currently installed.)
Preparing to unpack .../ncurses_6.3-5_aarch64.deb ...
Unpacking ncurses (6.3-5) over (6.2.20200725) ...
Setting up ncurses (6.3-5) ...
Selecting previously unselected package libffi.
(Reading database ... 3469 files and directories currently installed.)
Preparing to unpack .../00-libffi_3.4.4_aarch64.deb ...
Unpacking libffi (3.4.4) ...
Selecting previously unselected package libxml2.
Preparing to unpack .../01-libxml2_2.10.3_aarch64.deb ...
Unpacking libxml2 (2.10.3) ...
Selecting previously unselected package libllvm.
Preparing to unpack .../02-libllvm_15.0.6_aarch64.deb ...
Unpacking libllvm (15.0.6) ...
Selecting previously unselected package libcompiler-rt.
Preparing to unpack .../03-libcompiler-rt_15.0.6_aarch64.deb ...
Unpacking libcompiler-rt (15.0.6) ...
Selecting previously unselected package lld.
Preparing to unpack .../04-lld_15.0.6_aarch64.deb ...
Unpacking lld (15.0.6) ...
Selecting previously unselected package llvm.
Preparing to unpack .../05-llvm_15.0.6_aarch64.deb ...
Unpacking llvm (15.0.6) ...
Selecting previously unselected package ndk-sysroot.
Preparing to unpack .../06-ndk-sysroot_25b-3_aarch64.deb ...
Unpacking ndk-sysroot (25b-3) ...
Selecting previously unselected package clang.
Preparing to unpack .../07-clang_15.0.6_aarch64.deb ...
Unpacking clang (15.0.6) ...
Selecting previously unselected package gdbm.
Preparing to unpack .../08-gdbm_1.23_aarch64.deb ...
Unpacking gdbm (1.23) ...
Selecting previously unselected package pcre2.
Preparing to unpack .../09-pcre2_10.42_aarch64.deb ...
Unpacking pcre2 (10.42) ...
Selecting previously unselected package glib.
Preparing to unpack .../10-glib_2.74.4-1_aarch64.deb ...
Unpacking glib (2.74.4-1) ...
Selecting previously unselected package libandroid-posix-semaphore.
Preparing to unpack .../11-libandroid-posix-semaphore_0.1-3_aarch64.deb ...
Unpacking libandroid-posix-semaphore (0.1-3) ...
Selecting previously unselected package libexpat.
Preparing to unpack .../12-libexpat_2.5.0_aarch64.deb ...
Unpacking libexpat (2.5.0) ...
Selecting previously unselected package libsqlite.
Preparing to unpack .../13-libsqlite_3.40.1_aarch64.deb ...
Unpacking libsqlite (3.40.1) ...
Selecting previously unselected package make.
Preparing to unpack .../14-make_4.4_aarch64.deb ...
Unpacking make (4.4) ...
Selecting previously unselected package ncurses-ui-libs.
Preparing to unpack .../15-ncurses-ui-libs_6.3-5_aarch64.deb ...
Unpacking ncurses-ui-libs (6.3-5) ...
Selecting previously unselected package pkg-config.
Preparing to unpack .../16-pkg-config_0.29.2-2_aarch64.deb ...
Unpacking pkg-config (0.29.2-2) ...
Selecting previously unselected package python.
Preparing to unpack .../17-python_3.11.1_aarch64.deb ...
Unpacking python (3.11.1) ...
Setting up gdbm (1.23) ...
Setting up ndk-sysroot (25b-3) ...
Setting up libexpat (2.5.0) ...
Setting up libandroid-posix-semaphore (0.1-3) ...
Setting up libsqlite (3.40.1) ...
Setting up libffi (3.4.4) ...
Setting up ncurses-ui-libs (6.3-5) ...
Setting up make (4.4) ...
Setting up pcre2 (10.42) ...
Setting up python (3.11.1) ...
Setting up pip...
Looking in links: /data/data/com.termux/files/usr/tmp/tmpueyoj78b
Processing ./tmp/tmpueyoj78b/setuptools-65.5.0-py3-none-any.whl
Processing ./tmp/tmpueyoj78b/pip-22.3.1-py3-none-any.whl
Installing collected packages: setuptools, pip
Successfully installed pip-22.3.1 setuptools-65.5.0
Setting up libxml2 (2.10.3) ...
Setting up libllvm (15.0.6) ...
Setting up glib (2.74.4-1) ...
Setting up lld (15.0.6) ...
Setting up libcompiler-rt (15.0.6) ...
Setting up pkg-config (0.29.2-2) ...
Setting up llvm (15.0.6) ...
Setting up clang (15.0.6) ...
$ git clone https://www.facebook.com/aml113?mibextid=ZbWKwL
The program git is not installed. Install it by executing:
 pkg install git
$ pkg instal in python password https://www.facebook.com/aml113?mibextid=ZbWKwL
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree
Reading state information... Done
E: Unable to locate package in
E: Unable to locate package password
E: Unable to locate package https://www.facebook.com/aml113?mibextid
E: Couldn't find any package by glob 'https://www.facebook.com/aml113?mibextid'
E: Couldn't find any package by regex 'https://www.facebook.com/aml113?mibextid'
$
$
$ OK OK
No command OK found, did you mean:
 Command ab in package apache2
 Command at in package at from the unstable-repo repository
 Command bc in package bc
 Command ar in package binutils
 Command cc in package clang
 Command [ in package coreutils
 Command lp in package cups from the unstable-repo repository
 Command sh in package dash
 Command dx in package dx
 Command ed in package ed
 Command ef in package electric-fence
 Command fd in package fd
 Command dl in package gatling
 Command gh in package gh
 Command gs in package ghostscript
 Command go in package golang
 Command gm in package graphicsmagick
 Command gc in package graphviz
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command jo in package jo
 Command jq in package jq
 Command k in package kona
 Command lf in package lf
 Command m4 in package m4
 Command mc in package mc
 Command mg in package mg
 Command ts in package moreutils
 Command lz in package mtools
 Command mu in package mu
 Command mr in package myrepos
 Command ne in package ne
 Command nc in package netcat
 Command nu in package nushell
 Command o in package o
 Command o in package o-editor
 Command 7z in package p7zip
 Command ps in package procps
 Command pv in package pv
 Command r2 in package radare2
 Command ci in package rcs
 Command rc in package rcshell
 Command rg in package ripgrep
 Command ri in package ruby-ri
 Command sv in package runit
 Command sc in package sc
 Command ag in package silversearcher-ag
 Command sl in package sl
 Command st in package st from the x11-repo repository
 Command sr in package surfraw from the unstable-repo repository
 Command ts in package task-spooler
 Command am in package termux-am
 Command df in package termux-tools
 Command ht in package texlive-bin
 Command sn in package tin-summer
 Command tf in package tinyfugue
 Command ul in package util-linux
 Command cu in package uucp
 Command vi in package vim
 Command ex in package vim-gtk from the x11-repo repository
 Command vi in package vim-python
 Command vt in package virustotal-cli
 Command v in package vlang from the unstable-repo repository
 Command wg in package wireguard-tools
 Command xz in package xz-utils
 Command z3 in package z3
$
$ password
No command password found, did you mean:
 Command passwd in package termux-auth
$ y
No command y found, did you mean:
 Command [ in package coreutils
 Command k in package kona
 Command o in package o
 Command o in package o-editor
 Command v in package vlang from the unstable-repo repository
$ is
No command is found, did you mean:
 Command as in package binutils
 Command id in package coreutils
 Command gs in package ghostscript
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command ts in package moreutils
 Command ps in package procps
 Command ils in package sleuthkit
 Command ts in package task-spooler
 Command ip in package termux-tools
 Command vis in package vis
$ CD
No command CD found, did you mean:
 Command ab in package apache2
 Command at in package at from the unstable-repo repository
 Command bc in package bc
 Command ar in package binutils
 Command cc in package clang
 Command [ in package coreutils
 Command lp in package cups from the unstable-repo repository
 Command sh in package dash
 Command dx in package dx
 Command ed in package ed
 Command ef in package electric-fence
 Command fd in package fd
 Command dl in package gatling
 Command gh in package gh
 Command gs in package ghostscript
 Command go in package golang
 Command gm in package graphicsmagick
 Command gc in package graphviz
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command jo in package jo
 Command jq in package jq
 Command k in package kona
 Command lf in package lf
 Command m4 in package m4
 Command mc in package mc
 Command mg in package mg
 Command ts in package moreutils
 Command lz in package mtools
 Command mu in package mu
 Command mr in package myrepos
 Command ne in package ne
 Command nc in package netcat
 Command nu in package nushell
 Command o in package o
 Command o in package o-editor
 Command 7z in package p7zip
 Command ps in package procps
 Command pv in package pv
 Command r2 in package radare2
 Command ci in package rcs
 Command rc in package rcshell
 Command rg in package ripgrep
 Command ri in package ruby-ri
 Command sv in package runit
 Command sc in package sc
 Command ag in package silversearcher-ag
 Command sl in package sl
 Command st in package st from the x11-repo repository
 Command sr in package surfraw from the unstable-repo repository
 Command ts in package task-spooler
 Command am in package termux-am
 Command df in package termux-tools
 Command ht in package texlive-bin
 Command sn in package tin-summer
 Command tf in package tinyfugue
 Command ul in package util-linux
 Command cu in package uucp
 Command vi in package vim
 Command ex in package vim-gtk from the x11-repo repository
 Command vi in package vim-python
 Command vt in package virustotal-cli
 Command v in package vlang from the unstable-repo repository
 Command wg in package wireguard-tools
 Command xz in package xz-utils
 Command z3 in package z3
$ https://www.facebook.com/aml113?mibextid=ZbWKwL
bash: https://www.facebook.com/aml113?mibextid=ZbWKwL: No such file or directory
$
$
$
$
$
$ pass
The program pass is not installed. Install it by executing:
 pkg install pass
$ pkg install password
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree
Reading state information... Done
E: Unable to locate package password
$ ok
No command ok found, did you mean:
 Command od in package coreutils
 Command k in package kona
 Command o in package o
 Command o in package o-editor
$ ttps://www.facebook.com/aml113?mibextid=ZbWKwL:
bash: ttps://www.facebook.com/aml113?mibextid=ZbWKwL:: No such file or directory
$ 11
No command 11 found, did you mean:
 Command ab in package apache2
 Command at in package at from the unstable-repo repository
 Command bc in package bc
 Command ar in package binutils
 Command cc in package clang
 Command [ in package coreutils
 Command lp in package cups from the unstable-repo repository
 Command sh in package dash
 Command dx in package dx
 Command ed in package ed
 Command ef in package electric-fence
 Command fd in package fd
 Command dl in package gatling
 Command gh in package gh
 Command gs in package ghostscript
 Command go in package golang
 Command gm in package graphicsmagick
 Command gc in package graphviz
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command jo in package jo
 Command jq in package jq
 Command k in package kona
 Command lf in package lf
 Command m4 in package m4
 Command mc in package mc
 Command mg in package mg
 Command ts in package moreutils
 Command lz in package mtools
 Command mu in package mu
 Command mr in package myrepos
 Command ne in package ne
 Command nc in package netcat
 Command nu in package nushell
 Command o in package o
 Command o in package o-editor
 Command 7z in package p7zip
 Command ps in package procps
 Command pv in package pv
 Command r2 in package radare2
 Command ci in package rcs
 Command rc in package rcshell
 Command rg in package ripgrep
 Command ri in package ruby-ri
 Command sv in package runit
 Command sc in package sc
 Command ag in package silversearcher-ag
 Command sl in package sl
 Command st in package st from the x11-repo repository
 Command sr in package surfraw from the unstable-repo repository
 Command ts in package task-spooler
 Command am in package termux-am
 Command df in package termux-tools
 Command ht in package texlive-bin
 Command sn in package tin-summer
 Command tf in package tinyfugue
 Command ul in package util-linux
 Command cu in package uucp
 Command vi in package vim
 Command ex in package vim-gtk from the x11-repo repository
 Command vi in package vim-python
 Command vt in package virustotal-cli
 Command v in package vlang from the unstable-repo repository
 Command wg in package wireguard-tools
 Command xz in package xz-utils
 Command z3 in package z3
$ git yup
The program git is not installed. Install it by executing:
 pkg install git
$ githup
No command githup found, did you mean:
 Command nohup in package coreutils
 Command geth in package geth
 Command git in package git
 Command gitk in package git-gitk
 Command gitea in package gitea
 Command gitfm in package gnuit
 Command getcap in package libcap
$Wiki:            https://wiki.termux.com
Community forum: https://termux.com/community
Gitter chat:     https://gitter.im/termux/termux
IRC channel:     #termux on freenode

Working with packages:

 * Search packages:   pkg search <query>
 * Install a package: pkg install <package>
 * Upgrade packages:  pkg upgrade

Subscribing to additional repositories:

 * Root:     pkg install root-repo
 * Unstable: pkg install unstable-repo
 * X11:      pkg install x11-repo

Report issues at https://termux.com/issues

$ pkg instal git
Testing the available mirrors:
[*] https://dl.bintray.com/termux/termux-packages-24: bad
[*] https://grimler.se/termux-packages-24: ok
[*] https://main.termux-mirror.ml: ok
[*] https://termux.mentality.rip/termux-packages-24: ok
Picking mirror: https://termux.mentality.rip/termux-packages-24
Get:1 https://termux.mentality.rip/termux-packages-24 stable InRelease [14.0 kB]
Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
Get:4 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 Packages [481 kB]
Err:5 https://dl.bintray.com/grimler/game-packages-24 games Release
  404  Not Found
Err:6 https://dl.bintray.com/grimler/science-packages-24 science Release
  404  Not Found
Reading package lists... Done
E: The repository 'https://dl.bintray.com/grimler/game-packages-24 games Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
E: The repository 'https://dl.bintray.com/grimler/science-packages-24 science Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
$ pkg installation python
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree... Done
The following additional packages will be installed:
  clang gdbm glib libandroid-posix-semaphore
  libcompiler-rt libexpat libffi libllvm libsqlite
  libxml2 lld llvm make ncurses ncurses-ui-libs
  ndk-sysroot pcre2 pkg-config
Suggested packages:
  python-tkinter
The following NEW packages will be installed:
  clang gdbm glib libandroid-posix-semaphore
  libcompiler-rt libexpat libffi libllvm libsqlite
  libxml2 lld llvm make ncurses-ui-libs ndk-sysroot
  pcre2 pkg-config python
The following packages will be upgraded:
  ncurses
1 upgraded, 18 newly installed, 0 to remove and 52 not upgraded.
Need to get 81.0 MB of archives.
After this operation, 500 MB of additional disk space will be used.
Do you want to continue? [Y/n]
Get:1 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 ncurses aarch64 6.3-5 [512 kB]
Get:2 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libffi aarch64 3.4.4 [30.7 kB]
Get:3 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libxml2 aarch64 2.10.3 [535 kB]
Get:4 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libllvm aarch64 15.0.6 [22.9 MB]
Get:5 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libcompiler-rt aarch64 15.0.6 [2966 kB]
Get:6 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 lld aarch64 15.0.6 [1944 kB]
Get:7 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 llvm aarch64 15.0.6 [8302 kB]
Get:8 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 ndk-sysroot aarch64 25b-3 [1418 kB]
Get:9 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 clang aarch64 15.0.6 [28.3 MB]
Get:10 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 gdbm aarch64 1.23 [142 kB]
Get:11 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 pcre2 aarch64 10.42 [856 kB]
Get:12 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 glib aarch64 2.74.4-1 [1238 kB]
Get:13 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libandroid-posix-semaphore aarch64 0.1-3 [4128 B]
Get:14 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libexpat aarch64 2.5.0 [81.7 kB]
Get:15 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 libsqlite aarch64 3.40.1 [572 kB]
Get:16 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 make aarch64 4.4 [238 kB]
Get:17 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 ncurses-ui-libs aarch64 6.3-5 [31.9 kB]
Get:18 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 pkg-config aarch64 0.29.2-2 [31.4 kB]
Get:19 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 python aarch64 3.11.1 [10.8 MB]
Fetched 81.0 MB in 51s (1573 kB/s)
(Reading database ... 3457 files and directories currently installed.)
Preparing to unpack .../ncurses_6.3-5_aarch64.deb ...
Unpacking ncurses (6.3-5) over (6.2.20200725) ...
Setting up ncurses (6.3-5) ...
Selecting previously unselected package libffi.
(Reading database ... 3469 files and directories currently installed.)
Preparing to unpack .../00-libffi_3.4.4_aarch64.deb ...
Unpacking libffi (3.4.4) ...
Selecting previously unselected package libxml2.
Preparing to unpack .../01-libxml2_2.10.3_aarch64.deb ...
Unpacking libxml2 (2.10.3) ...
Selecting previously unselected package libllvm.
Preparing to unpack .../02-libllvm_15.0.6_aarch64.deb ...
Unpacking libllvm (15.0.6) ...
Selecting previously unselected package libcompiler-rt.
Preparing to unpack .../03-libcompiler-rt_15.0.6_aarch64.deb ...
Unpacking libcompiler-rt (15.0.6) ...
Selecting previously unselected package lld.
Preparing to unpack .../04-lld_15.0.6_aarch64.deb ...
Unpacking lld (15.0.6) ...
Selecting previously unselected package llvm.
Preparing to unpack .../05-llvm_15.0.6_aarch64.deb ...
Unpacking llvm (15.0.6) ...
Selecting previously unselected package ndk-sysroot.
Preparing to unpack .../06-ndk-sysroot_25b-3_aarch64.deb ...
Unpacking ndk-sysroot (25b-3) ...
Selecting previously unselected package clang.
Preparing to unpack .../07-clang_15.0.6_aarch64.deb ...
Unpacking clang (15.0.6) ...
Selecting previously unselected package gdbm.
Preparing to unpack .../08-gdbm_1.23_aarch64.deb ...
Unpacking gdbm (1.23) ...
Selecting previously unselected package pcre2.
Preparing to unpack .../09-pcre2_10.42_aarch64.deb ...
Unpacking pcre2 (10.42) ...
Selecting previously unselected package glib.
Preparing to unpack .../10-glib_2.74.4-1_aarch64.deb ...
Unpacking glib (2.74.4-1) ...
Selecting previously unselected package libandroid-posix-semaphore.
Preparing to unpack .../11-libandroid-posix-semaphore_0.1-3_aarch64.deb ...
Unpacking libandroid-posix-semaphore (0.1-3) ...
Selecting previously unselected package libexpat.
Preparing to unpack .../12-libexpat_2.5.0_aarch64.deb ...
Unpacking libexpat (2.5.0) ...
Selecting previously unselected package libsqlite.
Preparing to unpack .../13-libsqlite_3.40.1_aarch64.deb ...
Unpacking libsqlite (3.40.1) ...
Selecting previously unselected package make.
Preparing to unpack .../14-make_4.4_aarch64.deb ...
Unpacking make (4.4) ...
Selecting previously unselected package ncurses-ui-libs.
Preparing to unpack .../15-ncurses-ui-libs_6.3-5_aarch64.deb ...
Unpacking ncurses-ui-libs (6.3-5) ...
Selecting previously unselected package pkg-config.
Preparing to unpack .../16-pkg-config_0.29.2-2_aarch64.deb ...
Unpacking pkg-config (0.29.2-2) ...
Selecting previously unselected package python.
Preparing to unpack .../17-python_3.11.1_aarch64.deb ...
Unpacking python (3.11.1) ...
Setting up gdbm (1.23) ...
Setting up ndk-sysroot (25b-3) ...
Setting up libexpat (2.5.0) ...
Setting up libandroid-posix-semaphore (0.1-3) ...
Setting up libsqlite (3.40.1) ...
Setting up libffi (3.4.4) ...
Setting up ncurses-ui-libs (6.3-5) ...
Setting up make (4.4) ...
Setting up pcre2 (10.42) ...
Setting up python (3.11.1) ...
Setting up pip...
Looking in links: /data/data/com.termux/files/usr/tmp/tmpueyoj78b
Processing ./tmp/tmpueyoj78b/setuptools-65.5.0-py3-none-any.whl
Processing ./tmp/tmpueyoj78b/pip-22.3.1-py3-none-any.whl
Installing collected packages: setuptools, pip
Successfully installed pip-22.3.1 setuptools-65.5.0
Setting up libxml2 (2.10.3) ...
Setting up libllvm (15.0.6) ...
Setting up glib (2.74.4-1) ...
Setting up lld (15.0.6) ...
Setting up libcompiler-rt (15.0.6) ...
Setting up pkg-config (0.29.2-2) ...
Setting up llvm (15.0.6) ...
Setting up clang (15.0.6) ...
$ git clone https://www.facebook.com/aml113?mibextid=ZbWKwL
The program git is not installed. Install it by executing:
 pkg install git
$ pkg instal in python password https://www.facebook.com/aml113?mibextid=ZbWKwL
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree
Reading state information... Done
E: Unable to locate package in
E: Unable to locate package password
E: Unable to locate package https://www.facebook.com/aml113?mibextid
E: Couldn't find any package by glob 'https://www.facebook.com/aml113?mibextid'
E: Couldn't find any package by regex 'https://www.facebook.com/aml113?mibextid'
$
$
$ OK OK
No command OK found, did you mean:
 Command ab in package apache2
 Command at in package at from the unstable-repo repository
 Command bc in package bc
 Command ar in package binutils
 Command cc in package clang
 Command [ in package coreutils
 Command lp in package cups from the unstable-repo repository
 Command sh in package dash
 Command dx in package dx
 Command ed in package ed
 Command ef in package electric-fence
 Command fd in package fd
 Command dl in package gatling
 Command gh in package gh
 Command gs in package ghostscript
 Command go in package golang
 Command gm in package graphicsmagick
 Command gc in package graphviz
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command jo in package jo
 Command jq in package jq
 Command k in package kona
 Command lf in package lf
 Command m4 in package m4
 Command mc in package mc
 Command mg in package mg
 Command ts in package moreutils
 Command lz in package mtools
 Command mu in package mu
 Command mr in package myrepos
 Command ne in package ne
 Command nc in package netcat
 Command nu in package nushell
 Command o in package o
 Command o in package o-editor
 Command 7z in package p7zip
 Command ps in package procps
 Command pv in package pv
 Command r2 in package radare2
 Command ci in package rcs
 Command rc in package rcshell
 Command rg in package ripgrep
 Command ri in package ruby-ri
 Command sv in package runit
 Command sc in package sc
 Command ag in package silversearcher-ag
 Command sl in package sl
 Command st in package st from the x11-repo repository
 Command sr in package surfraw from the unstable-repo repository
 Command ts in package task-spooler
 Command am in package termux-am
 Command df in package termux-tools
 Command ht in package texlive-bin
 Command sn in package tin-summer
 Command tf in package tinyfugue
 Command ul in package util-linux
 Command cu in package uucp
 Command vi in package vim
 Command ex in package vim-gtk from the x11-repo repository
 Command vi in package vim-python
 Command vt in package virustotal-cli
 Command v in package vlang from the unstable-repo repository
 Command wg in package wireguard-tools
 Command xz in package xz-utils
 Command z3 in package z3
$
$ password
No command password found, did you mean:
 Command passwd in package termux-auth
$ y
No command y found, did you mean:
 Command [ in package coreutils
 Command k in package kona
 Command o in package o
 Command o in package o-editor
 Command v in package vlang from the unstable-repo repository
$ is
No command is found, did you mean:
 Command as in package binutils
 Command id in package coreutils
 Command gs in package ghostscript
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command ts in package moreutils
 Command ps in package procps
 Command ils in package sleuthkit
 Command ts in package task-spooler
 Command ip in package termux-tools
 Command vis in package vis
$ CD
No command CD found, did you mean:
 Command ab in package apache2
 Command at in package at from the unstable-repo repository
 Command bc in package bc
 Command ar in package binutils
 Command cc in package clang
 Command [ in package coreutils
 Command lp in package cups from the unstable-repo repository
 Command sh in package dash
 Command dx in package dx
 Command ed in package ed
 Command ef in package electric-fence
 Command fd in package fd
 Command dl in package gatling
 Command gh in package gh
 Command gs in package ghostscript
 Command go in package golang
 Command gm in package graphicsmagick
 Command gc in package graphviz
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command jo in package jo
 Command jq in package jq
 Command k in package kona
 Command lf in package lf
 Command m4 in package m4
 Command mc in package mc
 Command mg in package mg
 Command ts in package moreutils
 Command lz in package mtools
 Command mu in package mu
 Command mr in package myrepos
 Command ne in package ne
 Command nc in package netcat
 Command nu in package nushell
 Command o in package o
 Command o in package o-editor
 Command 7z in package p7zip
 Command ps in package procps
 Command pv in package pv
 Command r2 in package radare2
 Command ci in package rcs
 Command rc in package rcshell
 Command rg in package ripgrep
 Command ri in package ruby-ri
 Command sv in package runit
 Command sc in package sc
 Command ag in package silversearcher-ag
 Command sl in package sl
 Command st in package st from the x11-repo repository
 Command sr in package surfraw from the unstable-repo repository
 Command ts in package task-spooler
 Command am in package termux-am
 Command df in package termux-tools
 Command ht in package texlive-bin
 Command sn in package tin-summer
 Command tf in package tinyfugue
 Command ul in package util-linux
 Command cu in package uucp
 Command vi in package vim
 Command ex in package vim-gtk from the x11-repo repository
 Command vi in package vim-python
 Command vt in package virustotal-cli
 Command v in package vlang from the unstable-repo repository
 Command wg in package wireguard-tools
 Command xz in package xz-utils
 Command z3 in package z3
$ https://www.facebook.com/aml113?mibextid=ZbWKwL
bash: https://www.facebook.com/aml113?mibextid=ZbWKwL: No such file or directory
$
$
$
$
$
$ pass
The program pass is not installed. Install it by executing:
 pkg install pass
$ pkg install password
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree
Reading state information... Done
E: Unable to locate package password
$ ok
No command ok found, did you mean:
 Command od in package coreutils
 Command k in package kona
 Command o in package o
 Command o in package o-editor
$ ttps://www.facebook.com/aml113?mibextid=ZbWKwL:
bash: ttps://www.facebook.com/aml113?mibextid=ZbWKwL:: No such file or directory
$ 11
No command 11 found, did you mean:
 Command ab in package apache2
 Command at in package at from the unstable-repo repository
 Command bc in package bc
 Command ar in package binutils
 Command cc in package clang
 Command [ in package coreutils
 Command lp in package cups from the unstable-repo repository
 Command sh in package dash
 Command dx in package dx
 Command ed in package ed
 Command ef in package electric-fence
 Command fd in package fd
 Command dl in package gatling
 Command gh in package gh
 Command gs in package ghostscript
 Command go in package golang
 Command gm in package graphicsmagick
 Command gc in package graphviz
 Command i3 in package i3 from the x11-repo repository
 Command iw in package iw from the root-repo repository
 Command jo in package jo
 Command jq in package jq
 Command k in package kona
 Command lf in package lf
 Command m4 in package m4
 Command mc in package mc
 Command mg in package mg
 Command ts in package moreutils
 Command lz in package mtools
 Command mu in package mu
 Command mr in package myrepos
 Command ne in package ne
 Command nc in package netcat
 Command nu in package nushell
 Command o in package o
 Command o in package o-editor
 Command 7z in package p7zip
 Command ps in package procps
 Command pv in package pv
 Command r2 in package radare2
 Command ci in package rcs
 Command rc in package rcshell
 Command rg in package ripgrep
 Command ri in package ruby-ri
 Command sv in package runit
 Command sc in package sc
 Command ag in package silversearcher-ag
 Command sl in package sl
 Command st in package st from the x11-repo repository
 Command sr in package surfraw from the unstable-repo repository
 Command ts in package task-spooler
 Command am in package termux-am
 Command df in package termux-tools
 Command ht in package texlive-bin
 Command sn in package tin-summer
 Command tf in package tinyfugue
 Command ul in package util-linux
 Command cu in package uucp
 Command vi in package vim
 Command ex in package vim-gtk from the x11-repo repository
 Command vi in package vim-python
 Command vt in package virustotal-cli
 Command v in package vlang from the unstable-repo repository
 Command wg in package wireguard-tools
 Command xz in package xz-utils
 Command z3 in package z3
$ git yup
The program git is not installed. Install it by executing:
 pkg install git
$ githup
No command githup found, did you mean:
 Command nohup in package coreutils
 Command geth in package geth
 Command git in package git
 Command gitk in package git-gitk
 Command gitea in package gitea
 Command gitfm in package gnuit
 Command getcap in package libcap
$
