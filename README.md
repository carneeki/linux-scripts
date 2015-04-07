# linux-scripts
Assorted scripts I find useful that I place in ```~/bin```

```./dirs``` is a directory which contains sub-directories for software that are
not installed system wide. Things like my own private Eclipse builds.

```./links``` is a directory which contains symlinks to binaries, mostly they
are going to be in ```./dirs``` but not necessarily. Add ```~/bin``` and
```~/bin/links``` to your ```$PATH``` environment variable, then fill your links
directory with links to the application binaries in ```./dirs```.

```./once``` is a directory containing scripts that need to be run once. Mostly
this is a list of PPAs and system wide packages that I like to have set up when
I set up a new system. apt-fast, Git, TeX Live, things like that.

## Files
### builder-atom
[Atom](http://atom.io) is a really neat text editor. It's highly hackable. One
of the problems that this presents though is that sometimes you want to live on
the bleeding edge. This means having to pull the source, compile, and install
it. This script does all that.
