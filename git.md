Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git init
Reinitialized existing Git repository in C:/Users/Mauri/OneDrive/Área de Trabalho/Projeto Git/.git/

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git add readme.md

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md


Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git commit -m "primeiro commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Mauri@DESKTOP-L599E27.(none)')

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md


Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git config --global user.email "mauriezerpa^C

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git config --global user.email "mauriezerpa@gmail.com"

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git comited -m "primeiro commit"
git: 'comited' is not a git command. See 'git --help'.

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git commit -m "primeiro commit"
[master (root-commit) bd7acf8] primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git status
On branch master
nothing to commit, working tree clean

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (master)
$ git branch -M "main"

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ git remote add origin https://github.com/mauriezerpa/ProjetoGit-.git

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ git push -U origin main
error: unknown switch `U'
usage: git push [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --repo <repository>   repository
    --all                 push all refs
    --mirror              mirror all refs
    -d, --delete          delete refs
    --tags                push tags (can't be used with --all or --mirror)
    -n, --dry-run         dry run
    --porcelain           machine-readable output
    -f, --force           force updates
    --force-with-lease[=<refname>:<expect>]
                          require old value of ref to be at this value
    --force-if-includes   require remote updates to be integrated locally
    --recurse-submodules (check|on-demand|no)
                          control recursive pushing of submodules
    --thin                use thin pack
    --receive-pack <receive-pack>
                          receive pack program
    --exec <receive-pack>
                          receive pack program
    -u, --set-upstream    set upstream for git pull/status
    --progress            force progress reporting
    --prune               prune locally removed refs
    --no-verify           bypass pre-push hook
    --follow-tags         push missing but relevant tags
    --signed[=(yes|no|if-asked)]
                          GPG sign the push
    --atomic              request atomic transaction on remote side
    -o, --push-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only


Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 238.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mauriezerpa/ProjetoGit-.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ ^C

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ ^C

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$ ^C

Mauri@DESKTOP-L599E27 MINGW64 ~/OneDrive/Área de Trabalho/Projeto Git (main)
$
