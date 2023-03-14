
D:\Users\admin\Downloads\cmder
λ pwd
D:\Users\admin\Downloads\cmder

D:\Users\admin\Downloads\cmder
λ mkdir ejercicios

D:\Users\admin\Downloads\cmder
λ cd ejercicios

D:\Users\admin\Downloads\cmder\ejercicios
λ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


D:\Users\admin\Downloads\cmder\ejercicios
λ global
"global" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

D:\Users\admin\Downloads\cmder\ejercicios
λ --global Pablilloo
"--global" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

D:\Users\admin\Downloads\cmder\ejercicios
λ $ git config --global user.name "Pablilloo
"$" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

D:\Users\admin\Downloads\cmder\ejercicios
λ git config --global user.name "Pablilloo

D:\Users\admin\Downloads\cmder\ejercicios
λ git config --global user.email Pablilloo

D:\Users\admin\Downloads\cmder\ejercicios
λ git config --global user.email pabloaguirre2007@outlook.es

D:\Users\admin\Downloads\cmder\ejercicios
λ git config --list
core.symlinks=false
core.autocrlf=true
core.fscache=true
color.interactive=true
color.ui=auto
help.format=html
diff.astextplain.textconv=astextplain
rebase.autosquash=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
credential.helper=helper-selector
user.name=Pablilloo
user.email=pabloaguirre2007@outlook.es

D:\Users\admin\Downloads\cmder\ejercicios
λ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in D:/Users/admin/Downloads/cmder/ejercicios/.git/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ cd D:\Users\admin\Downloads\cmder\ejercicios git init
El sistema no puede encontrar la ruta especificada.

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git init cd D:\Users\admin\Downloads\cmder\ejercicios
usage: git init [-q | --quiet] [--bare] [--template=<template-directory>]
         [--separate-git-dir <git-dir>] [--object-format=<format>]
         [-b <branch-name> | --initial-branch=<branch-name>]
         [--shared[=<permissions>]] [<directory>]

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git init D:\Users\admin\Downloads\cmder\ejercicios
Reinitialized existing Git repository in D:/Users/admin/Downloads/cmder/ejercicios/.git/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ cd D:\Users\admin\Downloads\cmder\ejercicios

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git init
Reinitialized existing Git repository in D:/Users/admin/Downloads/cmder/ejercicios/.git/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ cd D:\Users\admin\Downloads\cmder\ejercicios

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git init
Reinitialized existing Git repository in D:/Users/admin/Downloads/cmder/ejercicios/.git/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicio1/
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m 'Version Inicial
error: pathspec 'Inicial' did not match any file(s) known to git

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m 'Version inicial
error: pathspec 'inicial' did not match any file(s) known to git

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add git commit -m 'Version inicial
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --sparse              allow updating entries outside of the sparse-checkout cone
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m 'Version Inicial
error: pathspec 'Inicial' did not match any file(s) known to git

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m 'Version inicial'
error: pathspec 'inicial'' did not match any file(s) known to git

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m 'version inicial
error: pathspec 'inicial' did not match any file(s) known to git

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicio1/
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add git commit -m "Version Inicial"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --sparse              allow updating entries outside of the sparse-checkout cone
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add ejercicio1/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add git commit -m "Version Inicial"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --sparse              allow updating entries outside of the sparse-checkout cone
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
[master (root-commit) 2a340d7] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add ejercicio1/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ
D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add ejercicio1/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ D:\Users\admin\Downloads\cmder\ejercicios
"D:\Users\admin\Downloads\cmder\ejercicios" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git add ejercicio1/

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ git commit -m "Version Inicial"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicios - Acceso directo.lnk

nothing added to commit but untracked files present (use "git add" to track)

D:\Users\admin\Downloads\cmder\ejercicios (master)
λ