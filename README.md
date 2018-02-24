C:\Users\Michaela>mkdir uloha

C:\Users\Michaela>cd uloha

C:\Users\Michaela\uloha>git init
Initialized empty Git repository in C:/Users/Michaela/uloha/.git/

C:\Users\Michaela\uloha>cd..

C:\Users\Michaela>git clone https://github.com/fhi-imapl/uloha1.git
Cloning into 'uloha1'...
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.

C:\Users\Michaela>cd skuska
The system cannot find the path specified.

C:\Users\Michaela>git add file
fatal: pathspec 'file' did not match any files

C:\Users\Michaela>echo "Ahoj">michaela.horvathova.txt

C:\Users\Michaela>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        Filmy/
        IntelGraphicsProfiles/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TM.blf
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        michaela.horvathova.txt
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini
        uloha1/
        "v\303\275platn\303\251 p\303\241sky/"

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Michaela>git add michaela.horvathova.txt

C:\Users\Michaela>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   michaela.horvathova.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        Filmy/
        IntelGraphicsProfiles/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TM.blf
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini
        uloha1/
        "v\303\275platn\303\251 p\303\241sky/"


C:\Users\Michaela>cd uloha

C:\Users\Michaela\uloha>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\Michaela\uloha>git commit -m "len som pridala subor

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Michaela@DESKTOP-IMVQBO4.(none)')

C:\Users\Michaela\uloha>cd ..

C:\Users\Michaela>git commit -m "skuska"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Michaela@DESKTOP-IMVQBO4.(none)')

C:\Users\Michaela>git >michaela.horvathova.txt

C:\Users\Michaela>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   michaela.horvathova.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   michaela.horvathova.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        Filmy/
        IntelGraphicsProfiles/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TM.blf
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{47a6a17a-a514-11e7-a94e-ec0d9a05c860}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini
        uloha1/
        "v\303\275platn\303\251 p\303\241sky/"


C:\Users\Michaela>git log
fatal: your current branch 'master' does not have any commits yet

C:\Users\Michaela>git desktop
git: 'desktop' is not a git command. See 'git --help'.

C:\Users\Michaela>git pull
fatal: No remote repository specified.  Please, specify either a URL or a
remote name from which new revisions should be fetched.

C:\Users\Michaela>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\Users\Michaela>cd uloha1

C:\Users\Michaela\uloha1>cd michaela.horvathova.txt
The system cannot find the path specified.

C:\Users\Michaela\uloha1>git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com': ^C
C:\Users\Michaela\uloha1>git pull
Already up to date.

C:\Users\Michaela\uloha1>git push
Everything up-to-date
