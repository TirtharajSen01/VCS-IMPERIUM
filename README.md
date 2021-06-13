# VCS-IMPERIUM
This is a version control system similar to git made in c++ for Linux and Mac OS.

# RUN-IMPERIUM-IN-YOUR-SYSTEM
Download the files and run build.sh file in the  terminal.

### RUNNING THE BUILD.SH FILE
Just navigate to the path where the build.sh file is
Then do CHMOD +x build.sh

I have also created a Imperium function which ensures that everytime we don't have to run build.sh command in the terminal.Just run ./imperium for the first time and it will work.

## USING IMPERIUM


### -:   IMPERIUM COMMANDS   :-

> imperium - Get the Commands List.

> imperium init - Initialize an empty repository.

> imperium add <path> - Add directories or files to repository. If you want to set the path as root, just type \"imperium add .\

> imperium commit \"commit message\" - Commit the currently staged files.

> imperium log - See the commit log until now.

> imperium status - See the current status of files which are created/modified as staged or unstaged for commit.

> imperium checkout <commitHashID> - Checkout the files committed in the required commit with given commitHash to the root.

> imperium revert <commitHashID> - Revert the commit with given commitHash.

> imperium resolve - Resolve Merge Conflicts and make the system ready for making commits.

All these commands can always be found after installation of the imperium in your system by just typing the command -- "imperium" in your terminal window.