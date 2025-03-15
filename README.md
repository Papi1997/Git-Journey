!Admin@DESKTOP-DR2RQ97 MINGW64 ~
$ git --version
git version 2.48.1.windows.1

!Admin@DESKTOP-DR2RQ97 MINGW64 ~
$ git config --global user.name "Tonny Onwonga"
git config --global user.email "lordjarvis02@gmail.com"

!Admin@DESKTOP-DR2RQ97 MINGW64 ~
$ mkdir myproject
cd myproject
mkdir: cannot create directory ‘myproject’: File exists

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject (master)
$ mkdir myprojectPapi
cd myprojectPapi

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git init
Initialized empty Git repository in C:/Users/!Admin/myproject/myprojectPapi/.git
/

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ ls
index.html
bash: index.html: command not found

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git add index.html
fatal: pathspec 'index.html' did not match any files

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git add --all

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ <!DOCTYPE html>
<html>
<head>
<title>Hello World!</title>
<link rel="stylesheet" href="bluestyle.css">
</head>
<body>

<h1>Hello world!</h1>
<p>This is the first file in my new Git Repo.</p>

</body>
</html>
bash: !DOCTYPE: event not found
bash: syntax error near unexpected token `newline'
bash: syntax error near unexpected token `newline'
bash: !: event not found
bash: syntax error near unexpected token `newline'
bash: syntax error near unexpected token `newline'
bash: syntax error near unexpected token `newline'
bash: !: event not found
bash: syntax error near unexpected token `newline'
bash: syntax error near unexpected token `newline'
bash: syntax error near unexpected token `newline'

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git add --all

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ ^C

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git commit -m "First release of Hello World!"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git add papa
fatal: pathspec 'papa' did not match any files

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git add--papito
git: 'add--papito' is not a git command. See 'git --help'.

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy
-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envva
r>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Reset current HEAD to the specified state
   switch     Switch branches
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

!Admin@DESKTOP-DR2RQ97 MINGW64 ~/myproject/myprojectPapi (master)
$ git help -a
See 'git help <command>' to read about a specific subcommand

Main Porcelain Commands
   add                     Add file contents to the index
   am                      Apply a series of patches from a mailbox
   archive                 Create an archive of files from a named tree
   backfill                Download missing objects in a partial clone
   bisect                  Use binary search to find the commit that introduced
a bug
   branch                  List, create, or delete branches
   bundle                  Move objects and refs by archive
   checkout                Switch branches or restore working tree files
   cherry-pick             Apply the changes introduced by some existing commits
   citool                  Graphical alternative to git-commit
   clean                   Remove untracked files from the working tree
   clone                   Clone a repository into a new directory
   commit                  Record changes to the repository
   describe                Give an object a human readable name based on an avai
lable ref
   diff                    Show changes between commits, commit and working tree
, etc
   fetch                   Download objects and refs from another repository
   format-patch            Prepare patches for e-mail submission
   gc                      Cleanup unnecessary files and optimize the local repo
sitory
   gitk                    The Git repository browser
   grep                    Print lines matching a pattern
   gui                     A portable graphical interface to Git
   init                    Create an empty Git repository or reinitialize an exi
sting one
   log                     Show commit logs
   maintenance             Run tasks to optimize Git repository data
   merge                   Join two or more development histories together
   mv                      Move or rename a file, a directory, or a symlink
   notes                   Add or inspect object notes
   pull                    Fetch from and integrate with another repository or a
 local branch
   push                    Update remote refs along with associated objects
   range-diff              Compare two commit ranges (e.g. two versions of a bra
nch)
   rebase                  Reapply commits on top of another base tip
   reset                   Reset current HEAD to the specified state
   restore                 Restore working tree files
   revert                  Revert some existing commits
   rm                      Remove files from the working tree and from the index
...skipping...


                   SUMMARY OF LESS COMMANDS

      Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 ---------------------------------------------------------------------------

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.
  d  ^D             *  Forward  one half-window (and set half-window to N).
  u  ^U             *  Backward one half-window (and set half-window to N).
  ESC-)  RightArrow *  Right one half screen width (or N positions).
  ESC-(  LeftArrow  *  Left  one half screen width (or N positions).
  ESC-}  ^RightArrow   Right to last column displayed.
  ESC-{  ^LeftArrow    Left  to first column.
  F                    Forward forever; like "tail -f".
  ESC-F                Like F but stop when search pattern is found.
  r  ^R  ^L            Repaint screen.
  R                    Repaint screen, discarding buffered input.
        ---------------------------------------------------
        Default "window" is the screen height.
        Default "half-window" is half of the screen height.
 ---------------------------------------------------------------------------

                          SEARCHING

  /pattern          *  Search forward for (N-th) matching line.
  ?pattern          *  Search backward for (N-th) matching line.
  n                 *  Repeat previous search (for N-th occurrence).
  N                 *  Repeat previous search in reverse direction.
  ESC-n             *  Repeat previous search, spanning files.
  ESC-N             *  Repeat previous search, reverse dir. & spanning files.
  ^O^N  ^On         *  Search forward for (N-th) OSC8 hyperlink.
  ^O^P  ^Op         *  Search backward for (N-th) OSC8 hyperlink.
  ^O^L  ^Ol            Jump to the currently selected OSC8 hyperlink.
  ESC-u                Undo (toggle) search highlighting.
  ESC-U                Clear search highlighting.
  &pattern          *  Display only matching lines.
        ---------------------------------------------------
        A search pattern may begin with one or more of:
        ^N or !  Search for NON-matching lines.
        ^E or *  Search multiple files (pass thru END OF FILE).
        ^F or @  Start search at FIRST file (for /) or last file (for ?).
        ^K       Highlight matches, but don't move (KEEP position).
        ^R       Don't use REGULAR EXPRESSIONS.
        ^S n     Search for match in n-th parenthesized subpattern.
        ^W       WRAP search if no match found.
        ^L       Enter next character literally into pattern.
 ---------------------------------------------------------------------------

                           JUMPING

  g  <  ESC-<       *  Go to first line in file (or line N).
  G  >  ESC->       *  Go to last line in file (or line N).
  p  %              *  Go to beginning of file (or N percent into file).
  t                 *  Go to the (N-th) next tag.
  T                 *  Go to the (N-th) previous tag.
  {  (  [           *  Find close bracket } ) ].
  }  )  ]           *  Find open bracket { ( [.
  ESC-^F <c1> <c2>  *  Find close bracket <c2>.
  ESC-^B <c1> <c2>  *  Find open bracket <c1>.
        ---------------------------------------------------
        Each "find close bracket" command goes forward to the close bracket
          matching the (N-th) open bracket in the top line.
        Each "find open bracket" command goes backward to the open bracket
          matching the (N-th) close bracket in the bottom line.

  m<letter>            Mark the current top line with <letter>.
  M<letter>            Mark the current bottom line with <letter>.
  '<letter>            Go to a previously marked position.
  ''                   Go to the previous position.
  ^X^X                 Same as '.
  ESC-m<letter>        Clear a mark.
        ---------------------------------------------------
        A mark is any upper-case or lower-case letter.
        Certain marks are predefined:
             ^  means  beginning of the file
             $  means  end of the file
 ---------------------------------------------------------------------------

                        CHANGING FILES
HELP --
