# learn2code
Resources for helping a friend learn to code

Alright, so you want to learn to code, but efore going off and doing a bootcamp or whatever its good to
get some basics down and learn how to code a bit on your own. There are two reasons for doing this:

1. Discover if you actually like coding, since if you don't this process is going to be long and painful.
   * Even if you like coding this process is still pretty difficult and will require some commitment.
2. Assuming you actually like this stuff and want to go further, learning some basics now will help you
decide if you want to do a bootcamp or continue on your own (possible, but harder). And could help you get
into well regarded bootcamps like the ([Recurse Center](https://www.recurse.com/).

So to start off we're gonna learn [Python](https://www.python.org/).

Why Python:
1. Extensive corpus of high-quality learning resources.
   * It's very Googleable and searching for ["how to do X in Python"](https://www.google.com/search?q=how+to+do+X+in+Python)
   where `X` is something like "read a file line by line" (that said [Python - Learn X in Y Minutes](https://learnxinyminutes.com/docs/python/))
   is a good site, but requires some knowledge of the language.
1. It's not a bad language and is well suited for teaching fundamental programing basics.
1. It's a [scripting language](https://en.wikipedia.org/wiki/Scripting_language) that can also be used for
serious production systems (it's used extensively at Lyft, Dropbox and other companies for mission critical
systems).

Whats nice about scripting languages is that you can save this snippet of code as `hello.py`:
```python
for what in ['World', 'Charlie', 'now GTFO']:
    print(f'Hello, {what}!')
```
Run it with:
```sh
$ python hello.py
```
And it just works - which is kinda cool and makes learning the language much easier!

Why not Python:
1. Will explain this later since it can be a distraction and won't be helpful at this
moment. Python is a good language, but there are many programming languages and
programming paradigms, and one thing you'll learn is that programmers have strong
opinions about them (for better or worse).

<!--
1. Python2: basically the transition to Python3 was a shit show so some things
still use Python2, which is EOL (end-of-life) so no longer supported and has a
slightly different syntax. Additionally, Python2 is the default on MacOS so you
have to install a different version.
1. It's a [dynamic programming language](https://en.wikipedia.org/wiki/Type_system#DYNAMIC).
 -->

## Text Editor

[Visual Studio Code](https://code.visualstudio.com/) is: new to the scene but has become tremendously popular
and "just works" for almost any languge; exensively backed by Microsoft (who actually make amazing developer
tools), easy to use; works on any platform (Linux. macOS, Windows); and is very easy to find well written guides for.
* [Getting started / install](https://code.visualstudio.com/docs/setup/setup-overview)
* Follow [this guide](https://code.visualstudio.com/docs/languages/python) to setup Visual Studio Code for Python.

_Note:_ PyCharm is also good and worth taking a look at but is a bit harder to get set up and very Python specific.

## Resources

* [Learn Python the Hard Way](https://learnpythonthehardway.org/book/): start here.
* [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/): came highly recommended from a coworker.

**TOOD:** Add more resources

## Bootcamps:

1. [Recurse Center](https://www.recurse.com/): formally known as the Hacker School ("hacking" as in bad dudes,
but "hacking" in the [classical sense](https://en.wikipedia.org/wiki/Hacker_culture)) until they realized
that it was making it hard for their foreign students to get visas. This is the best school and I believe
its free, but hard to get into.
1. [Flatiron School](https://flatironschool.com/): comes highly recommended from my coworkers.

## Setup

**TODO:** this section requires more work (see [comments](https://raw.githubusercontent.com/charlievieth/learn2code/master/README.md)) and may not be necessary.

<!--
**WARN:** do not follow these instructions as they are incomplete, require further explanation,
and may not be necessary.

Install [xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12), you likely won't ever use it,
but installing it also installs Apple's developer tools, which some things require.

Once you've installed xcode, open it, it will prompt you to install the "Command Line Tools" - click yes
to install them and wait for the install to complete - you can than close xcode and basically forget that
it exists.

Install the [homebrew](https://brew.sh/) package manager:

Open the terminal application (search for "terminal" in finder its also located at `/Applications/Utilities/Terminal`)
and past in the following line then press [ENTER] (**NOTE:** do not include the `$` when pasting the line - the use
of a `$` indicates that this command should be run from a terminal):
```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Package managers are tools for installing software and libraries and keeping them up to date.
They are a true godsend since doing this on your own is a massive PIA.

Install Python:
```
brew install python
```

Update your [`PATH`](https://en.wikipedia.org/wiki/PATH_(variable)) to make Python3 the default Python
otherwise Python2 is the default on Mac and you don't want that.
Make `python` point to Python3
```
$ echo '"PATH="/usr/local/opt/python/libexec/bin:$PATH"' >> ~/.bashrc
```
 -->
