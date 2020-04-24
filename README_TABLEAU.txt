I'm trying to be able to set up tableau so it integrates with .CSV files stored on github.
Currently, I'm trying that with the Our World in Data COVID files, as they are the easiest to integrate with tableau.
This is a fork of the main COVID Github for OWID, but in order to be able to get daily updates, I've configured it so that the directory has two upstream  sources - one is *master, which is the branch of my fork of the repository. the other one is the remote branch of the main OWID branch. I can thus pull from that source to keep my fork up to date, yet still modify my fork with stuff like this README.

Information on how I did what I did:
https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

A git bash cheat sheet:
https://gist.github.com/hofmannsven/6814451
